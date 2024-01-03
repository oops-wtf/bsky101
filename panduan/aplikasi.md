---
title: Aplikasi Bluesky
description: "Daftar pilihan aplikasi klien pihak ketiga bluesky"
layout: default
nav_order: 6
has_toc: true
permalink: /aplikasi
last_modified_date: 2024-01-02 11:51
---

Bluesky adalah platform microblogging sumber terbuka yang didukung oleh ATProto. Protokol ini memungkinkan pembuatan alat dan aplikasi pihak ketiga, yang terdaftar di sini untuk referensi.

{: .peringatan }
Jangan pernah menggunakan kata sandi utama Anda. Selalu gunakan [App Passwords]({% link pengaturan/password.md %})!

## Aplikasi Klien

| Nama | Versi | Tautan | Profil |
|:---:|:---:|:---:|:---:|
| Bluesky (official) | web, aplikasi | [bsky.app](https://bsky.app)  | [@bsky.app](https://bsky.app/profile/bsky.app) |
| Blue.deck | web | [deck.blue](deck.blue)  | [@deck.blue](https://bsky.app/profile/deck.blue) |
| Graysky | aplikasi | [Android](https://play.google.com/store/apps/details?id=dev.mozzius.graysky&pcampaignid=pcampaignidMKT-Other-global-all-co-prtnr-py-PartBadge-Mar2515-1) / [iOS](https://apps.apple.com/gb/app/graysky/id6448234181) | [@graysky.app](https://bsky.app/profile/graysky.app)
| Kite | web | [kite.black](https://kite.black) | [@arta.bsky.social](https://bsky.app/profile/arta.bsky.social) |
| Skeets | aplikasi (iOS) | [iOS (beta)](https://testflight.apple.com/join/B4oUcGn2) | [@skeetsapp.com](https://bsky.app/profile/skeetsapp.com)
| Skyfeed | web, aplikasi | [skyfeed.com](skyfeed.com) | [@skyfeed.app](https://bsky.app/profile/skyfeed.app)
| Tokimeki | web | [tokimeki.blue](https://tokimeki.blue) | [@tokimeki.blue](https://bsky.app/profile/tokimeki.blue)
| vSky | web | [vsky.social](https://www.vsky.social/) | [@vsky.social](https://bsky.app/profile/vsky.social)
| Skeetdeck | web | [skeetdeck.pages.dev](https://skeetdeck.pages.dev/) | [@mary.my.id](https://bsky.app/profile/mary.my.id)

## Alat dan Statistik

### API
* [Bluesky Social Wrapper](https://blue.amazingca.dev/) : Interactive Bluesky API Wrapper untuk uji coba kueri
* [Sky Bridge](https://skybridge.fly.dev/) : Mastodon Instance Proxy memungkinkan untuk menggunakan aplikasi Mastodon (saat ini hanya mendukung aplikasi Ivory) terhubung ke jaringan ATProto.

### Alat Moderasi
* [Blockenheimer](https://blockenheimer.click/) : Digunakan untuk membuat daftar moderasi secara cepat dan masif berdasarkan pengondisian seperti *keyword*, *liked post* dsb.. Berhati-hatilah saat menggunakan alat ini karena terkadang tidak akurat dalam mengidentifikasi akun.
* [ClearSky Search Tool](https://bsky.thieflord.dev/) : Digunakan untuk melihat registri blokir akun apa pun di kedua sisi (siapa yang memblokir mereka dan siapa yang mereka blokir) serta metrik backend lainnya.

### Feeds
* [Goodfeeds](https://goodfeeds.co/) : Layanan alternatif untuk mencari dan mengindeks feed. Juga memiliki tulisan yang bagus tentang feed ([The Guide to Feed](https://goodfeeds.co/the-guide)).
* [FireSky](https://firesky.tv/) : Visualisator arus utama jaringan ATProto (*firehose*) secara *real-time*.
* [SkyFeed](https://skyfeed.app/) : SkyFeed menyediakan metode blok untuk membuat dan mempublikasikan feed.

### Migrasi, Arsip, dan Cross-posting

* [Bluestream](https://bluestream.deno.dev) : RSS Feed generator untuk Bluesky.
* [Skeetgen](https://mary-ext.github.io/skeetgen/) : mengarsipkan postingan Bluesky dengan mudah
* [Follow The Sky](https://gggdomi.github.io/follow-the-sky/) : Temukan kembali orang-orang yang Anda ikuti di Twitter
* [Skeet](https://skeet.labnotes.org/) : Temukan mutual Twitter atau Mastodon Anda di Bluesky
* [Skeeter](https://skeeter.streamlit.app/) : Mencari pengguna Twitter/Mastodon di Bluesky
* [Sky Follower Bridge](https://github.com/kawamataryo/sky-follower-bridge) : Pengaya Chrome/Firefox untuk menemukan pengikut Twitter Anda di Bluesky

### Statistik dan Grafik
* [Atlas](https://bsky.jazco.dev) : Grafik sosial untuk Bluesky
* [Bluesky Posts Heatmap Generator](https://bluesky-heatmap.fly.dev/) ([Github](https://github.com/aliceisjustplaying/bluesky-heatmap))
* [Skycle](https://skycle.app/) : membuat visualisasi interaksi pertemanan Bluesky
* [Skystats](https://skystats.social/) : (statistik)
* [wolfgang.raios.xyz](https://wolfgang.raios.xyz) : Wolfgang menyediakan daftar interaksi, statistik pengikut dan blokir.
* [poll.blue](https://poll.blue) : (polling)

{: .catatan }
Buat PR di Github kami untuk menambahkan aplikasi ke dalam daftar