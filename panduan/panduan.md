---
title: Panduan Singkat
description: Halaman ini berisi informasi dan panduan singkat Bluesky sebagai pedoman bagi pengguna baru 🙌
layout: default
nav_order: 2
has_toc: true
permalink: /panduan
last_modified_date: 2024-01-11 22:13
---

{: .no_toc }
Laman ini berisi panduan singkat dan pandangan sekilas tentang isi dari keseluruhan situs **Bluesky 101** sebagai pedoman bagi pengguna baru 🙌
{: .fs-6 .fw-300 }

Mungkin Anda akan bertanya-tanya, "*Apa itu Bluesky?*", *Mengapa username di Bluesky panjang?*", "*Mengapa timeline-nya sepi? Bagaimana cara mencari mutual di Bluesky?*" atau "*Mengapa Bluesky minim fitur dibanding aplikasi lain?*", dsb.

Panduan ini akan mencoba menjawab sebagian besar dari banyak pertanyaan yang muncul terkait Bluesky dan ATProto. Setiap panduan dalam laman ini akan disertasi tautan yang mengarahkan Anda pada laman baru berisi informasi yang lebih lengkap, rincian fitur, atau panduan lebih lanjut.

{: .catatan }
Situs ini akan diperbarui secara berkala dengan informasi terbaru seiring perkembangan Bluesky dan ATProto.

<details open markdown="block">
  <summary>
    Daftar Isi
  </summary>
  {: .no_toc .text-delta }
1. TOC
{:toc}
</details>

---

## Bagian 1: Panduan Dasar
Setelah berhasil mendaftar, berikut beberapa hal yang perlu Anda ketahui sebagai dasar pengetahuan Anda tentang Bluesky:

0. Bluesky adalah sosial media sumber terbuka dan [terdesentralisasi]({% link atproto/desentralisasi.md %}) seperti [Mastodon]{:target="_blank"}. Jika Mastodon menggunakan ActivityPub, Bluesky menggunakan protokol yang berbeda yaitu [AT Protocol]({% link atproto/0-atproto.md %}). (Lihat perbandingannya [di sini]({% link atproto/pros-cons.md %}))
0. Anda dapat mengakses situs utama Bluesky ([bsky.app]{:target="_blank"}) dengan browser atau melalui berbagai pilihan [aplikasi pihak ketiga]({% link panduan/aplikasi.md %}#aplikasi-klien) dari perangkat ponsel. Aplikasi dari pihak ketiga adalah pilihan alternatif dengan keunggulan fitur yang mungkin belum tersedia di aplikasi resmi.
0. Bluesky memiliki batas 300 karakter untuk satu kiriman teks, 1000 karakter untuk ALT (*caption*) teks, 4 gambar kolase dalam 1 kiriman dengan batas ukuran gambar masing-masing sebesar 1MB. Batas ukuran ini juga berlaku untuk foto profil dan header banner.
0. Lakukan perubahan pada nama, foto profil, bio, *header/banner*, dan [*handle*]({% link handle/0-handle.md %}). Foto profil dan *header* untuk saat ini hanya mendukung format `.jpg` dan `.png` (*non-transparent*), dengan aspect ratio 1:1 (*square*) dan 3:1 untuk *header*.
0. *Handle* (username) Bluesky akan terlihat panjang jika dibandingkan dengan Twitter (mis. **@nama.bsky.social**). Username ini bukan hanya berfungsi sebagai penanda saja, tetapi juga sebagai identitas pengganti "[centang biru]({% link handle/tentang.md %})".
0. Bluesky juga memungkinkan Anda untuk menggunakan [custom domain]({% link handle/mengubah-handle.md %}) sebagai handle seperti pada ruang redaksi [**@nytimes.com**](https://bsky.app/profile/nytimes.com) dan [**@npr.org**](https://bsky.app/profile/npr.org). Domain bisa didapat secara gratis maupun berbayar. Lihat daftar rekomendasi subdomain gratis [di sini]({% link handle/rekomendasi-domain.md %}#daftar-rekomendasi-domain).
0. Penting sebelum Anda melanjutkan lebih jauh, pastikan Anda membaca secara lengap tentang [panduan moderasi]({% link moderasi/0-moderasi.md %}) di situs ini. Selanjutnya buka pengaturan [Moderation](https://bsky.app/moderation){:target="_blank"} pada web atau aplikasi klien, lanjutkan ke menu Content Filtering untuk memilih jenis konten apa yang ingin ditampilkan atau dihilangkan dari feed atau *skyline* Anda. Berlaku untuk konten yang mengandung unsur pornografi, kekerasan, spam, atau akun dengan [label *impersonation*]({% link moderasi/0-moderasi.md %}#pelabelan).
0. Tampilan utama atau *skyline* Anda akan berisi feed bawaan seperti *Following*, *Discover*, atau *What's Hot*. Masing-masing tab mungkin akan terlihat kosong atau *random* dan akan berubah seiring waktu sesuai akun yang Anda ikuti dan interaksi yang Anda lakukan.
0. Feed [Following](https://bsky.app){:target="_blank"} berisi kiriman terbaru (*chronological*) dari pengguna lain yang Anda ikuti. Feed ini bisa dikustomisasi melalui pengaturan [Home Feed Preferences](https://bsky.app/settings/home-feed){:target="_blank"} seperti untuk menampilkan post saja, menampilkan atau menghilangkan *repost*, *quoted post*, atau menampilkan *replies* pengguna lain sesuai jumlah *likes* -nya.
0. Bluesky *by design* membebaskan Anda untuk menentukan timeline dengan algoritma versi Anda sendiri melalui [fitur feed]({% link feed/0-feed.md %}). Anda bisa membuat feed sendiri atau menggunakan feed yang sudah dibuat oleh orang lain. Untuk memulai, berikut adalah [daftar feed]({% link feed/rekomendasi-feed.md %}) yang kami rekomendasikan untuk Anda sebagai pengguna baru.
0. Jika Anda ingin menemukan kiriman dari pengguna lain dalam klaster bahasa Indonesia, gunakan feed [Cakrawala Indonesia]. Semua kiriman yang menggunakan [Post Language]({% link pengaturan/bahasa.md %}) berlabel `id-ID` atau `in-ID` akan muncul secara otomatis dalam Cakrawala. Lihat  [di sini]({% link feed/cakrawala-indonesia.md %}) untuk panduan cara menampilkan sebuah kiriman dalam feed.
0. Anda tidak dapat mengontrol kiriman yang muncul di feed manapun. Artinya sebagian kiriman yang masuk misalnya dalam feed Cakrawala mungkin tidak tersaring dengan baik. Silakan lihat kembali [panduan moderasi]({% link moderasi/0-moderasi.md %}), *subscribe* [daftar moderasi]({% link moderasi/modlist.md %}) yang direkomendasikan dan pelajari cara membuat daftar moderasi sendiri.
0. Jadikan feed cakrawala hanya sebagai tempat mencari teman (mutualan). Maksimalkan fungsi feed [Following]({% link feed/rekomendasi-feed.md %}#feed-algoritmik) sebagai feed utama Anda untuk membangun sirkel pertemanan di Bluesky. Setiap orang berhak menentukan sirkelnya masing-masing.
0. Lihat juga [daftar pertanyaan umum]({% link panduan/FAQ.md %}) yang sering diajukan terkait Bluesky dan ATProto.

## Bagian 2: Informasi Lanjutan
Apabila Anda sudah selesai membaca dan memahami panduan dasar di atas, lanjutkan dengan membaca beberapa informasi singkat di bawah ini:

0. **Semua informasi, data, aktivitas, dan kiriman di Bluesky bersifat terbuka dan publik!** Jangan memposting apa pun yang perlu dirahasiakan atau membagikan secara berlebihan.
0. Bluesky sampai saat ini (20 Desember 2023) masih dalam tahap *private-closed beta*. Anda harus memiliki [kode undangan]({% link panduan/undangan.md %}) (contoh: `bsky-social-q3egc-xzygv`) agar bisa mendaftarkan akun atau mengundang orang lain untuk mendaftar.
0. Secara otomatis setiap 7-14 hari setelah berhasil mendaftar, Anda akan mendapatkan 1 kode undangan Anda sendiri untuk digunakan atau dibagikan kepada orang lain. Berlaku kelipatan untuk kode baru maksimal sampai 7 kode undangan tiap akun.
0. Masing-masing kode undangan tersebut hanya dapat digunakan satu kali untuk mendaftarkan 1 akun baru. Admin dapat melihat siapa yang Anda undang dan siapa yang mengundang Anda, serta dapat mengambil tindakan yang tepat jika diperlukan. 
0. Untuk saat ini belum ada fitur seperti *DM, video, poll, private account, hashtag, circle, space, bookmark*, lihat rujukan pada [Pengaturan dan Fitur]({% link pengaturan/0-pengaturan.md %}) serta [Roadmap]({% link panduan/roadmap.md %}) untuk melihat perkembangan fitur terbaru.
0. Beberapa [aplikasi pihak ketiga]({% link panduan/aplikasi.md %}#aplikasi-klien) mungkin sudah lebih dulu mendukung fitur tertentu seperti *video*, *GIF*, *hashtag*, dan *mute by word*. Aplikasi [Bluemotion](https://bluemotion.app/) ([@bluemotion.bsky.social](https://bsky.app/profile/bluemotion.bsky.social)) misalnya, dapat digunakan untuk mengirim video seperti TwitPic di Twitter. (Lihat contoh kiriman dengan video dari Bluemotion [di sini](https://bsky.app/profile/oops.wtf/post/3k4j3pyzumz2d))
0. Semua pengguna Bluesky memiliki kesempatan yang sama, [tidak ada algoritma khusus]({% link feed/0-feed.md %}) untuk mendorong *engagement* di Bluesky. Hanya feed yang menentukan bagaimana postingan akan tampil dan ditampilkan dalam *skyline*. Anda bisa berinteraksi secara organik dengan pengguna lain untuk membangun *engagement*.
0. Menambahkan deskripsi gambar atau *alternative text* (*ALT text*) dalam sebuah kiriman akan membantu orang-orang yang menggunakan *screen reader* untuk memahami konteks sebuah kiriman atau secara umum membantu orang lain memahami detail pada gambar yang Anda posting. Baca artikel dari *Harvard's Digital Accessbility* berikut tentang bagaimana [cara menulis ALT text](https://accessibility.huit.harvard.edu/describe-content-images) yang baik.

## Bagian 3: Privasi dan Keamanan 🔒
Informasi tambahan terkait privasi dan keamanan pengguna Bluesky

0. **Tidak ada pengaturan *private account* di Bluesky**, artinya semua postingan dan informasi akun bersifat terbuka bagi pengguna lain dalam jaringan. Anda hanya bisa membatasi kiriman agar tidak bisa dibalas oleh akun tertentu. (Lihat pada bagian [roadmap]({% link panduan/roadmap.md %}) untuk perkembangan terbaru)
0. Per tanggal 22 Desember 2023, Bluesky sudah terindeks di mesin pencari dan dapat dibuka oleh publik. Artinya bahwa siapa pun dapat melihat profil dan kiriman Anda di Bluesky tanpa akun. Untuk membatasinya, buka menu Settings > Moderation, kemudian hidupkan pengaturan pada *Logged-out visibility*.
0. Khusus bagi pengguna feed [Cakrawala Indonesia]({% link feed/cakrawala-indonesia.md %}), gunakan salah satu hashtag berikut: `#nofeed`, `!nofeed`, `-nofeed`, `~nofeed`, atau `#private`, `#privat` untuk membatasi postingan Anda agar tidak muncul di feed. Meskipun belum menjadi standar secara global, sebagian feed sudah menerapkan hashtag ini.
0. Selalu gunakan [App Passwords]({% link pengaturan/password.md %}) (contoh: `tvhow-sizj-nweob-m4as`) setiap menggunakan aplikasi klien dari pihak ketiga. Berbeda dengan kata sandi saat pertama kali mendaftar, *app passwords* bersifat **sementara** dan **bisa dihapus** atau dibuat ulang untuk keperluan berbagai macam aplikasi. (Dapat dilihat di menu [Settings](https://bsky.app/settings) > [App Passwords](https://bsky.app/settings/app-passwords))
0. [*Block dan mute*]({% link moderasi/0-moderasi.md %}) akun adalah hal yang biasa terjadi di Bluesky. Anda dapat memanfaatkan fitur [*modlist*]({% link moderasi/0-moderasi.md %}#mutelist-dan-blocklist-moderation-lists) yang dibuat sendiri atau yang sudah dibuat oleh akun lain untuk melakukan *block and mute* secara masal.
0. Segera lakukan verifikasi email di menu [Settings](https://bsky.app/settings) untuk berjaga-jaga apabila Anda perlu mereset ulang password utama.

---

## Glosarium
Glosarium adalah urutan (A-Z) daftar istilah Bluesky secara khusus dan istilah dalam dunia teknologi secara umum, disertai dengan definisinya masing-masing.

101
: *Introduction to (I) Computers (01)*, merujuk pada seseorang yang tidak memiliki pengetahuan, keterampilan, atau belum terbiasa dalam penggunaan komputer dan teknologi lainnya.

ALT text
: Sebuah atribut HTML berupa tulisan yang menggambarkan isi, situasi, dan tema dari gambar. Berfungsi sebagai judul atau identitas gambar sehingga setiap konten visual dalam satu artikel bisa dibedakan dengan baik.

ATProto
: Protokol baru yang dikembangkan oleh Bluesky (team) dan digunakan dalam dasar pembuatan Bluesky (app).

Bluesky (app)
: Merujuk pada aplikasi dan web klien Bluesky.

Bluesky (team)
: Merujuk pada tim atau sekelompok orang yang mengembangkan Bluesky dan ATProto.

DID (*Decentralized Identifier*)
: Nomor identitas unik bersifat publik sebagai identitas akun Anda dalam jaringan desentralisasi ATProto.

Domain
: Alamat atau nama yang menjadi identitas sebuah website atau komputer agar bisa lebih mudah diakses oleh pengguna.

Desentralisasi
: Merujuk pada transfer kontrol dan pengambilan keputusan dari entitas terpusat (individu, organisasi, atau grup) ke jaringan terdistribusi.

Feed
: Merujuk pada aloritmik skyline/timeline di Bluesky.

Instance Server
: Server atau node individu (terdesentralisasi) yang membentuk jaringan yang lebih besar. Instance dapat dijalankan secara independen oleh individu atau organisasi untuk tema atau tujuan tertentu.

Moderasi
: Sistem filter otomatis yang secara proaktif menganalisis dan mengidentifikasi konten yang melanggar aturan.

Protokol
: Aturan yang ada dalam sebuah jaringan yang memungkinkan adanya hubungan komunikasi serta perpindahan data antar perangkat.

Post
: Merujuk pada semua kiriman di Bluesky yang secara resmi disebut *post*.

Skyline
: Istilah lain yang merujuk pada *timeline* di Bluesky

Skymate
: Merujuk pada pengguna Bluesky lain

Third-party app
: Aplikasi yang dibuat oleh entitas lain di luar Bluesky dan AT Protocol.

{: .catatan }
Bantu kami untuk melengkapi laman ini... 🥺

[bsky.app]: https://bsky.app
[Mastodon]: https://joinmastodon.org
[cakrawala indonesia]: https://bsky.app/profile/did:plc:7opjnfmb6gtbgjrsr3777ujx/feed/aaagz4bmp5o3c
[indo bangers]: https://bsky.app/profile/did:plc:7opjnfmb6gtbgjrsr3777ujx/feed/aaaniozhx2iem