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
Setelah membaca panduan tentang [cara kerja feed]({% link feed/cara-kerja-feed.md %}) dan beberapa metode penyajian feed, berikut cara membuat feed sederhana menggunakan aplikasi pihak ketiga:

## Merancang Feed
Berikut langkah-langkah yang perlu Anda lakukan sebelum membuat feed di Bluesky:

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

#### Daftar alat untuk membuat feed:
* Skyfeed.com
* Blueskyfeed.com
* [Contrails](https://github.com/jcsalterego/Contrails): Feed Generator menggunakan Cloudflare Workers dan Bluesky Search. 

## Membuat feed generator sendiri

{: .catatan }
Bantu kami untuk mengisi halaman ini... 🥺