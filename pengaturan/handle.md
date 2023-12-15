---
title: Domain Handle
layout: default
description: 
nav_order: 2
parent: Pengaturan dan Fitur
permalink: /domain
last_modified_date: 2023-12-15 10:45
---

{: .catatan }
Bantu kami untuk melengkapi halaman ini... 🥺

# Domain Handle

Meskipun berbeda dalam penyebutannya, *handle* Bluesky sama dengan *username* di media sosial lain. Handle bukanlah sesuatu yang mungkin akan sering Anda ubah, karena biasanya itu berkaitan dengan branding diri atau produk di suatu platform [^1]

## Pengganti centang biru

Bluesky berusaha memaksimalkan fungsi handle-nya, termasuk untuk penanda verifikasi akun. 

Mengubahnya handle Bluesky tidak sesulit mencari cara mendapatkan kode undangannya. Berikut ini adalah langkah-langkah yang perlu Anda lakukan:

0. Buka aplikasi atau web klien Bluesky di perangkat Anda.
0. Ketuk ikon hamburger pada samping kiri (ponsel) atau sidebar (web)
0. Pilih menu *Settings*
0. Gulir ke bawah dan ketuk *Change handle* di sub menu *Advanced* 
0. Masukkan handle baru Anda
0. Pilih *Save* untuk mengkonfirmasi ketersediaan handle pilihan Anda.

Perubahan ini akan disimpan jika handle pilihan Anda masih tersedia atau belum digunakan orang lain. Jika tidak, Anda akan diberitahu bahwa handle sudah digunakan, dan Anda diminta untuk mencoba yang lain.

## Custom domain sebagai handle

Berikut ini adalah daftar layanan di mana Anda dapat membuat handle (username) Anda sendiri untuk Bluesky.

Kirim PR untuk menambahkan layanan Anda!

Perubahan terakhir: `15 Desember 2023`

### Official

| Handles   | Type  | PDS?  | Open? | Free? | Auth  | Maintainer    | Links |
|---        |---    |---    |---    |---    |---    |---            |---    |
| `*.bsky.social` | http | ✅ | ❌ | ✅ | password | [Bluesky PBLLC](https://bsky.app/profile/did:plc:z72i7hdynmk6r22z27h6tvur) | [web](https://blueskyweb.xyz/), [git](https://github.com/bluesky-social) |
| `*.is-extremely.gay`<br>`*.the-gay.cat`<br>`*.woke.cat`<br>`*.lesbian.cat` | dns | - | ✅ | ✅ | none | [@domi.zip](https://bsky.app/profile/did:plc:7bwr7mioqql34n2mrqwqypbz) | [web](https://handles.domi.zip/), [git](https://github.com/SlickDomique/open-handles) |
| `*.bsky.london` | dns | - | ✅ | ✅ | none | [@pfrazees.monster](https://bsky.app/profile/did:plc:p2cp5gopk7mgjegy6wadk3ep) | [web](https://bsky.london/) |
| `*.swifties.social` | dns | - | ✅ | ✅ | none | [@pfrazees.monster](https://bsky.app/profile/did:plc:p2cp5gopk7mgjegy6wadk3ep) | [web](https://bsky.london/) |
| `*.gwei.cz` | dns | - | ✅ | ✅ | external:matrix | [@gwei.cz](https://bsky.app/profile/did:plc:2bs6eyzyjkqb5gmqbfurccx2) | [web](https://app.element.io/#/room/bluesky:gwei.cz), [git](https://github.com/gweicz/atproto-handle-matrix-bot) |
| `*.ish.ninja` | dns | - | ✅ | ✅ | password | [@ishaanbedi.in](https://bsky.app/profile/did:plc:d5d2pdxfn2feddaqrxg337ta) | [web](https://www.ish.ninja/), [git](https://github.com/ishaanbedi/ish.ninja) |

### Un-official (hack it!)

| Handles   | Type  | Open? | Auth  | Maintainer    | Links | Note  |
|---        |---    |---    |---    |---            |---    |---    |
| `*.deno.dev` | http | ✅ | multiple | Deno Land Inc. | [web](https://deno.com/deploy) |  |
| `*.messwithdns.com` | dns | ✅ | none | wizard zines | [web](http://messwithdns.com/) | only temporary, suitable for testing |

---

[^1]: [Cara Mengganti Nama Pengguna dan Nama Tampilan Bluesky](https://voi.id/teknologi/316925/cara-mengganti-nama-pengguna-dan-nama-tampilan-bluesky)