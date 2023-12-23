---
title: Bluesky Handle
description: Meskipun berbeda dalam penyebutannya, handle di Bluesky sama dengan username di media sosial lain.
layout: default
nav_order: 2
parent: Pengaturan dan Fitur
permalink: /domain
last_modified_date: 2023-12-20 14:04
---

# Bluesky (*username*) Handle
{: .no_toc }
Meskipun berbeda dalam penyebutannya, *handle* di Bluesky sama dengan *username* di media sosial lain.
{: .fs-6 .fw-300 }

<details open markdown="block">
  <summary>
    Daftar Isi
  </summary>
  {: .no_toc .text-delta }
1. TOC
{:toc}
</details>

---
## Tentang Domain
Setiap perangkat yang terhubung di internet pada dasarnya memiliki alamat IP unik seperti `172.217.6.196`. Meskipun demikan, Anda tentu akan lebih mudah untuk mengingat `google.com` sebagai nama domain dibanding alamat IP-nya.

Domain adalah nama unik untuk mengidentifikasi situs web di internet. Sebagai contoh, domain Bluesky adalah [bsky.app](https://bsky.app) atau situs berita Kompas.com dengan domain [kompas.com](https://kompas.com). Domain dapat dibagi lagi menjadi subdomain. Misalnya, jika domain Anda adalah `contoh.com` tetapi Anda memiliki blog yang di-host di `blog.contoh.com`, maka *blog* adalah subdomain.

Secara teknis, AT Protocol -lah yang memungkinkan Anda untuk menggunakan domain sebagai handle. Sedangkan Bluesky (app) adalah aplikasi klien yang dibuat Bluesky (team) di atas protokol ini, di mana Anda dapat menggunakan domain ***.bluesky.social** sebagai handle.

### Pengganti Centang Biru
{: .no_toc }
Sama halnya dengan username di Mastodon, handle di Bluesky mungkin akan terlihat lebih panjang jika dibandingkan dengan Twitter.

Perbedaanya, Mastodon menggunakan konsep domain sebagai username untuk mengidentifikasi *instance* (server) mana akun tersebut dibuat. Misalnya akun `@nama@mastodon.social`, menunjukkan akun `nama` dibuat di instance [mastodon.social](https://mastodon.social). Jika Anda ingin mengubah username Mastodon dari `@nama@mastodon.social` menjadi `@ini@namasaya.com` Anda harus membuat *instance* sendiri dengan domain `namasaya.com`.

Berikut beberapa alasan AT Protocol menggunakan domain sebagai handle dan memprioritaskannya sebagai fitur utama Bluesky:
0. **Identitas** : Anda dapat menggunakan handle yang sama untuk berbagai layanan sosial media ATProto. Bluesky (app) adalah salah satu contoh aplikasi yang dibangun di atas ATProto. Jika sekarang Anda memiliki domain `@contoh.com` sebagai handle di Bluesky, maka Anda dapat menggunakan handle tersebut di aplikasi ATProto yang lain sebagai identitas.
0. **Verifikasi** : Anda bisa mengetahui akun mana yang benar-benar asli berdasarkan identitas domain atau situs web yang terkait dengannya. Seperti pada sebuah situs web, domain handle di Bluesky menunjukkan kepemilikan *user* atas domain tersebut. Sebagai contoh, ruang redaksi The New York Times dapat mengubah handle mereka menjadi [@nytimes.com](https://bsky.app/profile/nytimes.com), Kemudian setiap jurnalis yang ingin diverifikasi dapat menggunakan subdomain seperti `@nama.nytimes.com`. Demikianlah alasan mengapa tidak ada akun dengan 'centang biru' di Bluesky.
0. **Portabilitas** : Anda tetap dapat menggunakan domain handle Anda ketika berpindah server. Ketika Bluesky sudah [terdesentralisasi]({% link atproto/desentralisasi.md %}) akan ada banyak [PDS (*instance server*)]({$ link atproto/pds-bgs-appview.md $}) selain [bsky.app](https://bsky.app). Anda bisa beralih ke berbagai server yang berbeda tanpa perlu mengganti domain handle.

{: .catatan }
Lihat akun reporter [@thomas.gizmodo.com](https://bsky.app/profile/thomas.gizmodo.com) untuk situs berita [@gizmodo.com](https://bsky.app/profile/gizmodo.com)

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

## Daftar Rekomendasi Domain

Berikut ini adalah daftar layanan di mana Anda dapat membuat nama handle Anda sendiri untuk Bluesky dengan domain khusus.

{: .catatan }
Kirim permintaan di [Github kami](https://github.com/oops-wtf/bsky-docs/tree/main/pengaturan/handle.md) untuk menambahkan layanan Anda!

Perubahan terakhir: `20 Desember 2023`

#### Domain dengan Dukungan Resmi
{: .no_toc }

| Handles   | Type  | PDS?  | Open? | Free? | Auth  | Maintainer    | Links |
|:--- |:---:|:---:|:---:|:---:|:---:|:---:|:---:|
| `*.bsky.social` | http | ✅ | ❌ | ✅ | password | [Bluesky PBLLC](https://bsky.app/profile/did:plc:z72i7hdynmk6r22z27h6tvur) | [bsky.app](https://bsky.app/)<br>([github](https://github.com/bluesky-social)) |
| `*.bsky.to`| dns | - | ✅ | ✅ | none | [@andrew.bsky.to](https://bsky.app/profile/andrew.bsky.to) | [bsky.to](https://bsky.to)
| `*.tired.io`<br>`*.bsky.cool`<br>`*.bsky.fish`<br>`*.bsky.lgbt`<br>`*.bsky.finance`<br>`*.vibes.cool`<br>`*.excuseme.wtf`<br>`*.bluesky.zip`<br>`*.skeets.online` | dns | - | ✅ | ✅ | password | [@darn.fish](https://bsky.app/profile/did:plc:7qw3ldjppmwmtjoak3egctdb) | [skyna.me](https://skyna.me/)<br>[github](https://github.com/darnfish/skyname) |
| `*.is-extremely.gay`<br>`*.the-gay.cat`<br>`*.woke.cat`<br>`*.lesbian.cat` | dns | - | ✅ | ✅ | none | [@domi.zip](https://bsky.app/profile/did:plc:7bwr7mioqql34n2mrqwqypbz) | [handles.domi.zip](https://handles.domi.zip/)<br>[github](https://github.com/SlickDomique/open-handles) |
| `*.bsky.london` | dns | - | ✅ | ✅ | none | [@pfrazees.monster](https://bsky.app/profile/did:plc:p2cp5gopk7mgjegy6wadk3ep) | [bsky.london](https://bsky.london/) |
| `*.swifties.social` | dns | - | ✅ | ✅ | none | [@pfrazees.monster](https://bsky.app/profile/did:plc:p2cp5gopk7mgjegy6wadk3ep) | [swifties.social](https://swifties.social/) |
| `*.gwei.cz` | dns | - | ✅ | ✅ | external:matrix | [@gwei.cz](https://bsky.app/profile/did:plc:2bs6eyzyjkqb5gmqbfurccx2) | [element chat](https://app.element.io/#/room/bluesky:gwei.cz)<br>([github](https://github.com/gweicz/atproto-handle-matrix-bot)) |
| `*.ish.ninja` | dns | - | ✅ | ✅ | password | [@ishaanbedi.in](https://bsky.app/profile/did:plc:d5d2pdxfn2feddaqrxg337ta) | [ish.ninja](https://www.ish.ninja/)<br>([github](https://github.com/ishaanbedi/ish.ninja)) |
| `*.grows.green`<br>`*.knows.green`<br>`*.loves.green`<br>`*.smokes.green`<br>`*.rolls.green`<br>`*.thequeenof.green`<br>`*.thekingof.green` | dns | - | ✅ | ✅ | none | [@Adirondack.Green](https://bsky.app/profile/did:plc:r2jsoijmenfb67klwdc3hyav) | [grows.green](https://grows.green)<br>[knows.green](https://knows.green)<br>[loves.green](https://loves.green)<br>[smokes.green](https://smokes.green)<br>[rolls.green](https://rolls.green)<br>[thequeenof.green](https://thequeenof.green)<br>[thekingof.green](https://thekingof.green) |

#### Domain Tidak Resmi
{: .no_toc }

| Handles | Type | Open? | Auth | Maintainer | Links | Notes |
|:--- |:---:|:---:|:---:|:---:|:---:|:---:|
| `*.github.io` | http | ✅ | multiple | Github | [github.com](https://github.com) | Github Pages |
| `*.deno.dev` | http | ✅ | multiple | Deno Land Inc. | [deno.dev](https://deno.com/deploy) |  |
| `*.messwithdns.com` | dns | ✅ | none | wizard zines | [messwithdns.com](http://messwithdns.com/) | only temporary, suitable for testing |