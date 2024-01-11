---
title: Moderasi
description: Semua data dan informasi di Bluesky bersifat terbuka dan publik. Moderasi akan dikembalikan ke masing-masing pengguna.
layout: home
has_children: true
permalink: /moderasi
nav_order: 6
last_modified_date: 2024-01-03 08:36
---

# Moderasi
Moderasi adalah fitur penting dalam ruang sosial. Begitulah cara perilaku buruk dibatasi, norma ditetapkan, dan perselisihan diselesaikan.
{: .fs-6 .fw-300 }

Bluesky (team) mempertahankan sistem [undangan]({% link panduan/undangan.md %}) sebelum melakukan [desentralisasi]({% link atproto/desentralisasi.md %}) dimaksudkan untuk memprioritaskan keselamatan pengguna sementara menyelesaikan [protokol]({% link atproto/0-atproto.md %}) dan sistem moderasi. Sistem moderasi ini akan menjadi fitur unggulan Bluesky dibanding platform lain. Mereka menerapkan fitur moderasi menggunakan pendekatan seperti [feed dan algoritma]({% link feed/0-feed.md %}) yang memungkinkan adanya ekosistem penyedia dari pihak ketiga.

Untuk feed misalnya, terdapat algoritma dasar berlaku hanya kepada akun yang Anda ikuti kemudian berkembang menjadi algoritma khusus yang lebih kompleks. Sama halnya untuk moderasi, harus ada standar dasar yang berlaku kemudian akan dibuat banyak filter khusus yang tersedia sebagai pilihan pelengkap di atasnya.

Semua data dan informasi di Bluesky pada dasarnya bersifat terbuka dan publik, proses moderasi akan dikembalikan ke masing-masing pengguna. Moderasi dalam skala kecil bisa dimulai dari cara termudah yaitu *mute, block, unfollow*. Sedangkan moderasi secara cepat, luas, dan masif, Anda bisa menggunakan daftar bisu (*mutelist*) atau [daftar moderasi]({% link moderasi/modlist.md %}) (*modlist*) yang dibuat sendiri atau yang sudah dibuat oleh pengguna lain.

ATProto dalam [roadmap]({% link panduan/roadmap.md %}) juga telah mempersiapkan layanan khusus terkait moderasi yang memungkinkan operator (admin) PDS server berlangganan [label komunitas]({% link moderasi/pelabelan.md %}#pelabelan-komunitas-roadmap) untuk proses moderasi tingkat server.