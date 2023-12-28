---
title: Cara Kerja Feed
description: Cakrawala menampilkan kiriman dari semua pengguna dalam klaster bahasa Indonesia.
layout: home
nav_order: 1
parent: Feed dan Algoritma
grand_parent: Pengaturan dan Fitur
permalink: /cara-kerja-feed
last_modified_date: 2023-12-29 00:19
---

# Cara Kerja Feed
Secara sederhana, cara kerja feed sebenarnya mirip seperti mesin pencari yang dapat menyaring sebuah kata kunci, menyaring kiriman berdasarkan akun pengguna (author), atau secara kompleks menggunakan grafik pengikut untuk menemukan akun lain dalam sebuah lingkaran pertemanan.

*Feed generator* memiliki 2 bagian penting:
0. Bagian pertama akan terhubung ke [*firehose*]({% link atproto/firehose.md %}), yang merupakan aliran utama semua peristiwa dan menyimpannya ke dalam basis data (*database*).
0. Bagian kedua menyediakan ruang untuk menjawab pertanyaan "*postingan mana yang akan muncul di feed?*" sesuai dengan pengondisian atau algoritma yang sudah ditetapkan sebelumnya. Melalui algoritma tersebut, feed akan mengambil kiriman dari *firehose* untuk ditampilkan kepada pengguna.

Setiap permintaan ke *feed generator* menyertakan token yang dapat diverifikasi mewakili permintaan pengguna.

# Metode Penyajian Feed
Berikut adalah berbagai metode penyajian feed, yang dapat dikombinasikan dalam berbagai cara.

0. ### Semua Post
Feed dapat menampilkan semua postingan dari *firehose* tanpa filter apapun.

0. ### Berdasarkan Kata Kunci
Sebuah feed dapat menampilkan postingan dengan mencocokan kiriman dengan kata kunci tertentu. Varian/subset yang populer saat ini adalah menggunakan emoji, misalnya 🧪, 🌱, atau 🤼‍♀️. Pencocokan teks yang lebih kompleks dapat menggunakan ekspresi reguler (RegEx), yang lebih fleksibel dalam kemampuan penyaringannya.

0. ### Berdasarkan Daftar Pengguna (Public List)
Feed dapat menyajikan kiriman dari daftar pengguna. Saat ini ada dua cara untuk mengumpulkan pengguna: mengikuti pengguna, atau membuat daftar pengguna (*user lists*) dan daftar moderasi (*moderation lists*).

0. ### Berdasarkan Daftar Pengguna (Private List)
Feed menyajikan kiriman dari sekumpulan pengguna yang disimpan secara privat. Daftar ini dapat disisipkan dalam kode, atau disimpan dalam *database*. Sering kali, daftar tersebut disimpan dalam bentuk DID; lihat [https://atproto.com/guides/identity](https://atproto.com/guides/identity) untuk informasi lebih lanjut.

0. ### Berdasarkan Permintaan Pengguna
Feed menyajikan postingan berdasarkan permintaan pengguna, seperti:
    * Permintaan atas skyline yang diikuti
    * Permintaan atas postingan yang disukai
    * Permintaan atas kiriman, disaring untuk jenis tertentu misalnya media, balasan, repost

0. ### Berdasarkan Segmentasi Pengguna
Feed akan menyajikan kiriman dari sebuah segmentasi pengguna. Seperti contoh feed [Teams](https://bsky.app/profile/did:plc:vwzwgnygau7ed7b7wt5ux7y2/feed/teams) yang membagi menjadi beberapa team yang berbeda tiap pengguna.

0. ### Berdasarkan Metadata (ALT text, Embeds, Labels)
Feed menyajikan postingan berdasarkan atribut yang mungkin tidak mudah dilihat di UI.
    * Teks alternatif (Alt text) adalah deskripsi teks yang disediakan pengguna untuk gambar yang disematkan
    * Tautan yang disematkan ke situs web eksternal akan memiliki judul situs web, tautan, dan deskripsi
    * Label diterapkan secara manual atau otomatis pada akun atau postingan, seperti: akun ditandai sebagai peniruan, atau postingan ditandai sebagai NSFW

0. ### Berdasarkan Konten (Tingkat Lanjut)
Feed menyajikan postingan berdasarkan konten itu sendiri, menggunakan strategi seperti:
    * Computer Vision (CV), atau deteksi gambar misalnya gambar anjing, kucing, burung, bunga, langit dsb.
    * Deteksi bahasa dengan bantuan NLP atau ChatGPT

0. ### Berdasarkan Social Signal
Feed menyajikan postingan berdasarkan jumlah likes, reposts, replies, dan/atau quotes.

0. ### Berdasarkan Social Signal dan Social Graph
Karena feed memiliki akses ke pengguna feed dan social graph (*who is following whom*) yang juga tersedia secara publik, feed dapat menarik kiriman dari pengguna lain berdasarkan sinyal-sinyal ini. Sebagai contoh:
    * Menampilkan kiriman yang paling disukai oleh orang yang Anda ikuti
    * Menampilkan kiriman yang paling disukai oleh orang yang diikuti oleh orang yang Anda ikuti
    * Menampilkan kiriman dengan balasan terbanyak oleh orang yang Anda ikuti

0. ### Fitur: Visibilitas Berdasarkan Permintaan Pengguna
Feed dapat memilih untuk menampilkan konten (atau mengembalikan feed kosong) berdasarkan kriteria pengguna yang meminta. Seperti pada contoh feed [Cool Club (test)](https://bsky.app/profile/did:plc:q6gjnaw2blty4crticxkmujt/feed/a:cool_club)

0. ### Fitur: Feed Statis, Kiriman yang Disematkan
Feed dapat memilih untuk menampilkan serangkaian postingan yang konstan (statis), baik untuk keseluruhan feed atau hanya di awal feed (*pinned*).