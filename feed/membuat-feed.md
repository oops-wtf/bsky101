---
title: Cara Membuat Feed
layout: home
nav_order: 3
parent: Feed dan Algoritma
grand_parent: Pengaturan dan Fitur
permalink: /membuat-feed
last_modified_date: 2023-12-29 00:19
---

# Cara Membuat Feed
Tidak perlu keterampilan khusus untuk membuat feed dengan 3rd-party app/service. Kecuali Anda berniat membuat feed generator sndiri. Untuk cara termudah misalnya, Anda dapat menggunakan aplikasi dari https://blueskyfeeds.com. Sebelum memulai, baca panduan tentang [cara kerja feed]({% link feed/cara-kerja-feed.md %}) dan beberapa metode penyajiannya. 

## Merancang Feed
Langkah-langkah yang perlu Anda lakukan sebelum membuat feed di Bluesky:

0. Tentukan tujuan feed yang ingin Anda buat. Feed dapat berupa informasi, melayani tujuan tertentu, atau menjadi "titik kumpul" untuk sebuah komunitas.
0. Pastikan belum ada feed lain yang serupa. Jika ada feed yang sama, apakah perlu membuat feed baru lagi yang terpisah? Jenis postingan seperti apa yang ingin Anda tampilkan di feed?
    Jika kemungkinan sudah ada feed lain yang sama, pertimbangkan:
    * Membuat komunitas yang lebih kecil (mis. feed daerah X) di dalam komunitas yang lebih besar (mis. indo klaster)
    * Membuat payung yang lebih besar (mis. feed kpopindo) yang berisi komunitas kecil yang sudah ada (mis. fanbase idol x, y, z)
    * Menyediakan tujuan khusus yang baru, misalnya feed yang menampilkan kiriman dengan balasan terbanyak dalam klaster bahasa Indonesia
0. Pahami tingkat pemeliharaanya. Banyak feed yang hanya dibuat sekali dan jarang diperbaharui. Beberapa feed mungkin perlu pemeliharaan atau pembaruan daftar pengguna, kurasi dan moderasi konten, dan atau pemecahan masalah (feed rusak/hilang).
0. Perhatikan pada kemudahan penggunaan dan kemudahan penemuan feed. Baik nama maupun deskripsi feed memiliki batas karakter. Nama feed harus sederhana, jelas, dan mudah dicari. Deskripsi feed akan memberikan gambaran yang jelas kepada pengguna berisi tentang tujuan dan cara kerja, misalnya "Feed menampilkan post dengan kata kunci #indonesia" atau "hubungi @username agar ditambahkan dalam list". Gambar avatar feed juga harus dapat dikenali dengan baik.

## Membuat feed dengan aplikasi pihak ketiga
Terdapat beberapa aplikasi pihak ketiga yang bisa Anda gunakan untuk membuat feed dengan mudah. Hampir sebagian besar dari aplikasi ini menggunakan kata kunci sebagai fitur utama dalam membuat feed. Selanjutnya perhatikan langkah-langkah berikut:

0. Gunakan *keyword* yang tidak terlalu umum untuk menghindari postingan yang masuk menjadi terlalu banyak dan tidak relevan. Menggunakan keyword yang unik dan spesifik akan membatasi jangkauan feed agar tidak terlalu luas dengan hasil lebih akurat.
0. Misalnya Anda ingin membuat feed dengan topik tentang pecinta buku dan literasi, maka Anda bisa menggunakan kata kunci berupa hashtag `#maribaca` atau dengan emoji seperti "📚". Namun menggunakan emoji "📚" sebagai kata kunci tentu akan menampilkan banyak kiriman yang mungkin tidak sesuai dengan topik yang Anda pilih. Maka cukup gunakan `#maribaca` saja sebagai hashtag.
0. Jika Anda menggunakan penyaringan bahasa di Skyfeed, maka feed hanya akan menampilkan kiriman sesuai dengan Post Language yang dipilih.

### Blueskyfeed.com ([@blueskyfeeds.com](https://bsky.app/profile/blueskyfeeds.com))
0. Buka [Blueskyfeed.com](https://blueskyfeed.com), halaman utama akan berisi daftar feed yang dibuat dengan Blueskyfeed dan beberapa rekomendasi feed lain yang terdaftar di jaringan ATProto.
0. Tekan tombol Login to create and manage your Feeds
0. Login menggunakan [handle]({% link handle/0-handle.md %}) dan [app passwords]({% link pengaturan/password.md %}) (**wajib**).
0. Setelah berhasil masuk, pilih tombol Make a new Feed untuk masuk ke laman pembuatan feed.
0. Maka akan muncul laman baru untuk memilih jenis feed seperti apa yang ingin Anda buat.
    * Latest Post with Keyword : Jika Anda ingin membuat feed menggunakan kata kunci tertentu atau hashtag untuk komunitas atau fandom
    * User's Latest Posts : Jika Anda ingin membuat feed untuk menampilkan kiriman terakhir dari 
    * My Posts : Jika Anda ingin membuat feed untuk menampilkan kiriman Anda sendiri dengan beberapa filter.
    * List of Posts : Feed berisi daftar kiriman spesifik misalnya untuk membuat penanda post atau markah.
    * Other : Kreasikan feed Anda untuk keperluan lain di samping pilihan di atas.
0. Apapun yang Anda pilih pada langkah sebelumnya, selanjutnya lakukan pengaturan untuk:
    * Feed Full Name : Isikan nama feed Anda
    * Unique Short Name : Isikan dengan nama singkat feed Anda untuk identitas unik
    * Description : Berisi informasi lengkap tentang feed dan cara kerjanya
    * Feed Avatar : Berisi gambar atau icon feed
    * Feed Privacy : Anda bisa memilih apakah feed ini bersifat terbuka, private, atau hanya terlihat bagi sebagian orang sesuai list tertentu
    * Mode
    * Show in Highlights on BlueskyFeeds.com?
    * Sticky Post URI or URL (This shows up at the 1st or 2nd position of your feed)
    * Sort Order
    * Post Type Filter
    * Picture Posts Filter
    * Language Filters
    * User Filters
    * Other User Filters
    * Keyword Filters (max 100)
    * File Backup

#### Daftar alat untuk membuat feed:
* [Skyfeed.app](https://skyfeed.com) : Feed generator dengan metode block
* [Blueskyfeed.com](https://blueskyfeed.com) : Feed generator dengan metode 
* [Contrails](https://github.com/jcsalterego/Contrails): Feed Generator menggunakan Cloudflare Workers dan Bluesky Search. 

## Membuat feed generator sendiri

{: .catatan }
Bantu kami untuk mengisi dan melengkapi halaman ini... 🥺