---
title: Cara Mengubah Handle
description:
layout: default
nav_order: 2
parent: Bluesky Handle
grand_parent: Pengaturan dan Fitur
has_children: false
permalink: /mengubah-handle
last_modified_date: 2023-12-28 14:02
---

## Cara Mengubah Handle

Handle bukanlah sesuatu yang mungkin akan sering Anda ubah, karena biasanya itu berkaitan dengan branding diri atau produk di suatu platform.

Namun mengubah handle Bluesky tidak sesulit mencari cara mendapatkan kode undangannya. Berikut ini adalah langkah-langkah yang perlu Anda lakukan:

* Buka aplikasi atau web klien [bsky.app](https://bsky.app)
* Ketuk ikon hamburger pada samping kiri (ponsel) atau sidebar (web)
* Pilih menu [Settings](https://bsky.app/settings)
* Gulir ke bawah dan ketuk *Change handle* di sub menu *Advanced*

![](https://blueskyweb.xyz/images/blogposts/advanced-settings.jpg){:width="50%"}

* Masukkan handle baru Anda (misalnya: **@nama.bsky.social**)

![](https://blueskyweb.xyz/images/blogposts/change-my-handle.jpg){:width="50%"}

* Pilih *Save* untuk mengkonfirmasi ketersediaan handle pilihan Anda.

Perubahan ini akan disimpan jika handle pilihan Anda masih tersedia atau belum digunakan orang lain. Jika tidak, Anda akan diberitahu bahwa handle sudah digunakan, dan Anda diminta untuk mencoba yang lain.

{: .penting }
Jika Anda mengubah handle Bluesky bawaan (**.bsky.social*) menjadi domain, nama pengguna lama Anda akan tersedia untuk digunakan oleh orang lain. Namun, semua mention dan tag dengan handle lama akan tetap mengarah ke akun Anda.

## Mengganti Handle Dengan Domain Sendiri

Untuk mengganti handle dengan domain sendiri atau menggunakan domain dari [daftar rekomendasi](#daftar-rekomendasi-domain), ketuk pada *I have my own domain*, maka akan muncul seperti di bawah ini:

![](https://blueskyweb.xyz/images/blogposts/domain-txt-record.jpg){:width="50%"}

Kotak dialog di atas berisi informasi tambahan yang perlu Anda tambahkan ke registrar tempat Anda membeli domain.

Langkah-langkah spesifik ini bisa berbeda bergantung pada reseller/perusahaan domain yang Anda gunakan. Tambahkan TXT record ke domain Anda, biasanya berada di menu manajemen DNS. Isikan informasi akun Bluesky Anda sesuai kotak dialog sebelumnya.

Nomor DID seperti `did:plc:7opjnfmb6gtbgjrsr3777ujx` bersifat publik dan bukan merupakan informasi sensitif (Baca lebih lanjut tentang DID [di sini]({% link atproto/pds-bgs-appview.md %})).

```
Set the domain: _atproto
Set the type: TXT
Set the value: did=did:plc:[your value here]
```

Lihat pada contoh ilustrasi berikut:

<a href="https://www.youtube.com/embed/MGpJjq186bc"><img src="https://blueskyweb.xyz/images/domains.gif" alt=""></a>