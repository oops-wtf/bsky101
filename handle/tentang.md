---
title: Tentang Domain Handle
description:
layout: default
nav_order: 1
parent: Bluesky Handle
grand_parent: Pengaturan dan Fitur
has_children: false
permalink: /tentang-domain
last_modified_date: 2023-12-28 14:02
---

## Tentang Domain
Setiap perangkat yang terhubung di internet pada dasarnya memiliki alamat IP unik seperti `172.217.6.196`. Meskipun demikan, Anda tentu akan lebih mudah untuk mengingat `google.com` sebagai nama domain dibanding alamat IP-nya.

Domain adalah nama unik untuk mengidentifikasi situs web di internet. Sebagai contoh, domain Bluesky adalah [bsky.app](https://bsky.app) atau situs berita Kompas.com dengan domain [kompas.com](https://kompas.com). Domain dapat dibagi lagi menjadi subdomain. Misalnya, jika domain Anda adalah `contoh.com` tetapi Anda memiliki blog yang di-host di `blog.contoh.com`, maka *blog* adalah subdomain.

Secara teknis, AT Protocol -lah yang memungkinkan Anda untuk menggunakan domain sebagai handle. Sedangkan Bluesky (app) adalah aplikasi klien yang dibuat Bluesky (team) di atas protokol ini, di mana Anda dapat menggunakan domain ***.bluesky.social** sebagai handle.

## Pengganti Centang Biru
{: .no_toc }
Sama halnya dengan username di Mastodon, handle di Bluesky mungkin akan terlihat lebih panjang jika dibandingkan dengan Twitter.

Perbedaanya, Mastodon menggunakan konsep domain sebagai username untuk mengidentifikasi *instance* (server) mana akun tersebut dibuat. Misalnya akun `@nama@mastodon.social`, menunjukkan akun `nama` dibuat di instance [mastodon.social](https://mastodon.social). Jika Anda ingin mengubah username Mastodon dari `@nama@mastodon.social` menjadi `@ini@namasaya.com` Anda harus membuat *instance* sendiri dengan domain `namasaya.com`.

Berikut beberapa alasan AT Protocol menggunakan domain sebagai handle dan memprioritaskannya sebagai fitur utama Bluesky:
0. **Identitas** : Anda dapat menggunakan handle yang sama untuk berbagai layanan sosial media ATProto. Bluesky (app) adalah salah satu contoh aplikasi yang dibangun di atas ATProto. Jika sekarang Anda memiliki domain `@contoh.com` sebagai handle di Bluesky, maka Anda dapat menggunakan handle tersebut di aplikasi ATProto yang lain sebagai identitas.
0. **Verifikasi** : Anda bisa mengetahui akun mana yang benar-benar asli berdasarkan identitas domain atau situs web yang terkait dengannya. Seperti pada sebuah situs web, domain handle di Bluesky menunjukkan kepemilikan *user* atas domain tersebut. Sebagai contoh, ruang redaksi The New York Times dapat mengubah handle mereka menjadi [@nytimes.com](https://bsky.app/profile/nytimes.com), Kemudian setiap jurnalis yang ingin diverifikasi dapat menggunakan subdomain seperti `@nama.nytimes.com`. Demikianlah alasan mengapa tidak ada akun dengan 'centang biru' di Bluesky.
0. **Portabilitas** : Anda tetap dapat menggunakan domain handle Anda ketika berpindah server. Ketika Bluesky sudah [terdesentralisasi]({% link atproto/desentralisasi.md %}) akan ada banyak [PDS (*instance server*)]({$ link atproto/pds-bgs-appview.md $}) selain [bsky.app](https://bsky.app). Anda bisa beralih ke berbagai server yang berbeda tanpa perlu mengganti domain handle.

{: .catatan }
Lihat akun reporter [@thomas.gizmodo.com](https://bsky.app/profile/thomas.gizmodo.com) untuk situs berita [@gizmodo.com](https://bsky.app/profile/gizmodo.com)
