---
title: Pelabelan
description:
layout: default
nav_order: 3
parent: Moderasi
has_children: false
permalink: /pelabelan
last_modified_date: 2024-01-10 14:02
---

## Pelabelan (*labeler*)
Label adalah tag yang disertakan dalam sebuah kiriman atau profil pengguna. Penyematan tanda ini digunakan untuk proses moderasi.

Beberapa contoh label yang sudah tersedia di Bluesky sebagai bagian dari moderasi konten:
* *nudity* : menandakan bahwa kiriman tersebut mengandung unsur ketelanjangan secara visual
* *self-harm* : menandakan kiriman tersebut berisi gambar atau diskusi tentang melukai diri sendiri
* *spam* : menandakan akun tersebut terlibat dalam interaksi yang berlebihan dan tidak diinginkan (non-organik)
* *impersonation* : menandakan akun yang mengaku sebagai seseorang yang bukan dirinya (peniruan)

Proses pelabelan akun di Bluesky berlaku sebagai berikut:
* Siapa pun dapat menentukan dan menerapkan label pada konten atau akun (misalnya: pornografi, kekerasan, spam, atau akun *impersonation*).
* Label dapat dibuat secara otomatis (melalui [aplikasi pihak ketiga]({% link panduan/aplikasi.md %}), atau dengan algoritma khusus) atau secara manual (oleh admin, atau oleh pengguna itu sendiri).
* Setiap orang atau layanan di jaringan dapat memilih bagaimana label ini digunakan.

## Pelabelan Komunitas [Roadmap]({% link panduan/roadmap.md %}){: .label }
Pelabelan komunitas memungkinkan pengguna Bluesky untuk memilih, mengintepretasi, dan menggunakan label yang dibuat dengan *labeling service*.

Labeling service mencakup seluruh jaringan ATProto dan dapat digunakan oleh pengguna manapun sehingga bukan hanya tugas operator (admin) server saja untuk memoderasi ruang mereka tetapi juga dapat dilakukan oleh pengguna secara umum dengan membuat layanan pelabelan sendiri. Label ini akan dipublikasikan secara global di jaringan ATProto dengan cara yang sama seperti fitur Feed.

![](/assets/gambar/panduan/moderasi/labeling-services.png)
<center><small>*Skema Labeling Services*</small></center>

Pengguna dapat memiliki lebih dari satu *labeling service*, dengan label bawaan yang diberikan oleh server dan beberapa pilihan (saran) yang bisa Anda pilih. Pengguna dapat memutuskan bagaimana label ini akan digunakan misalnya untuk menampilkan, menyembunyikan, memburamkan, atau melampirkan peringatan pada konten.

Untuk mengontrol Labeling Service, Bluesky (team) telah membuat aplikasi dengan kode nama **Ozone**. Aplikasi ini mencakup peralatan untuk melihat akun, kiriman, dan laporan yang dikirim oleh pengguna lain. Operator server (admin) dapat menggunakannya untuk menerapkan label atau mengapusnya akun yang dianggap melanggar.

Pelabelan otomatis juga dimungkinkan untuk mendeteksi beberapa jenis konten, seperti yang dilakukan Bluesky sekarang.
