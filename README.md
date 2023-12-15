**Bluesky 101** berisi informasi, panduan tertulis, dan semua yang berkaitan dengan Bluesky, PBLLC (AT Protocol) dalam bahasa Indonesia.

Situs ini dibuat atas inisiasi [@oops.wtf](https://bsky.app/profile/oops.wtf) untuk kemudian diserahkan kepada komunitas Bluesky Indonesia untuk dikelola bersama.

# Skema Kontribusi

Setelah Anda membaca atau menggunakan Bluesky 101, Anda dapat berkontribusi dalam pengembangannya.
Sebelum mulai berkontribusi, mohon baca dokumen berikut supaya Anda mengerti dengan alur kontribusi, dan proyek ini dapat dikerjakan dengan lancar.

# Bentuk Kontribusi

Anda dapat berkontribusi dengan cara apapun. Contoh:

1. Menuliskan ulasan (*review*), menambahkan tulisan, atau laman baru
2. Memberikan masukan, misalnya ketika ada informasi baru, perubahan pada roadmap Bluesky, maupun panduan yang kurang jelas
3. Melaporkan adanya penjelasan yang kurang tepat
4. Melaporkan kesalahan pengetikan
5. Mengerjakan isu terbuka (ditunjukkan dengan label *open*) yang diangkat orang lain (kontribusi Anda sangat dibutuhkan!)

Untuk kontribusi semacam poin 1 sampai poin 4, Anda perlu [menuliskan isu](#menuliskan-isu) terlebih dahulu. Tujuannya untuk mendiskusikan jalan keluar dan tindakan apa yang akan dilakukan setelah isu tersebut diangkat.

# Menuliskan Isu

Anda dapat menuliskan isu yang berhubungan dengan **informasi dan panduan** terkait Bluesky.

Seluruh masukan yang Anda berikan dituliskan pada [GitHub Issue Tracker](https://github.com/oops-wtf/bsky-docs/issues). Untuk menuliskan isu, Anda perlu memiliki akun [GitHub](http://github.com/). Beberapa hal yang perlu diperhatikan:

1. Periksa apakah isu yang akan Anda angkat sudah pernah dikerjakan. Caranya dengan mengacu pada [branch master](https://github.com/oops-wtf/bsky-docs) dan memastikan isu yang akan Anda angkat masih perlu diselesaikan.
2. Periksa apakah isu yang serupa sudah pernah diangkat. Caranya dengan melihat daftar [GitHub Issue Tracker](https://github.com/oops-wtf/bsky-docs/issues).

Tata cara penulisan isu:

1. Tulis isu dengan Bahasa Indonesia.
2. Judul isu merupakan garis besar tentang apa yang Anda angkat sebagai isu, tuliskan dengan singkat dan jelas. Khusus untuk isu yang menyangkut suatu informasi atau panduan, tulis dalam format "\<judul\>: \<isu Anda\>". Beberapa contoh penulisan isu: "Aplikasi: tambahan aplikasi klien skynet", "Perulangan lanjut: perbaikan typo".
3. Isi isu merupakan penjelasan tentang apa yang Anda angkat sebagai isu, tuliskan dengan jelas dan tidak ambigu (tidak menimbulkan pertanyaan dari kontributor lainnya). Jika isu yang diangkat mengacu pada suatu materi, tuliskan di slide ke berapa. Jika mengacu pada penulisan kata-kata, tuliskan di mana kata tersebut muncul. Jika isu yang diangkat adalah penulisan materi baru, cukup tuliskan secara garis besar apa yang akan Anda tulis.

Setelah isu dituliskan, kontributor akan menanggapi masukan Anda dan membahasnya pada isu yang Anda tambahkan. Hasil akhir dari pembahasan adalah keputusan apakah masukan tersebut akan diimplementasikan pada situs ini. Jika diputuskan bahwa masukan itu akan diimplementasikan, Anda boleh memutuskan apakah Anda yang akan mengimplementasikannya atau tidak. Jika ya, ikuti [tata cara implementasi](#tata-cara-implementasi). Jika tidak, isu tersebut akan menjadi *open issue* dan dapat dikerjakan oleh kontributor lainnya (mengacu pada poin 5 pada [bentuk kontribusi](#bentuk-kontribusi)).

# Tata Cara Implementasi

Anda diharapkan paham perintah-perintah dasar git seperti clone, checkout, branch, add, commit, push, dan pull. Tutorial penggunaan git sudah banyak beredar di internet. Salah satu yang singkat dan mudah dipahami: https://try.github.io/levels/1/challenges/1

Selain itu, Anda juga diharapkan memiliki pengetahuan tentang penulisan dengan Markdown.

Jika Anda baru pertama kali akan melakukan kontribusi, lakukan langkah-langkah berikut:

1. Fork repository dengan pergi ke [halaman utama](https://github.com/oops-wtf/bsky-docs), lalu pilih fork di ujung kanan atas.
2. Pilih username Anda untuk melakukan fork.
3. Lakukan clone terhadap repository yang sudah Anda fork, dengan mengetikkan `git clone https://github.com/<username Anda>/bsky-docs.git`.
4. Lakukan `git remote add upstream https://github.com/oops-wtf/bsky-docs`. Perintah ini bertujuan untuk membuat sebuah remote bernama `upstream` yang merujuk pada repository bsky-doc, sehingga Anda bisa melakukan pull dari repository bsky-doc ke repository hasil fork Anda.

Setelah itu, Anda bisa mulai bekerja dengan:

1. Pastikan Anda berada di branch master. Caranya dengan mengetikkan perintah `git status` dan pastikan ada tulisan `On branch master`. Jika Anda belum berada di branch master, ketikkan `git checkout master`.
2. Checkout branch baru dengan cara mengetikkan `git checkout -b <nama branch>`. Gunakan nama branch dalam bahasa Inggris (*camelCase*), mudah dipahami, dan berkaitan dengan isu yang mau Anda selesaikan. Contoh nama branch: "addRecursiveExample", "modifyMergeSortMaterial".
3. Lakukan perubahan secukupnya. Anda bebas melakukan add, commit, atau push. Namun sebaiknya Anda tidak melakukan merge atau pull. Hal ini akan mengakibatkan struktur graph git menjadi kurang rapi. Ketimbang melakukan merge atau pull, lakukan rebase atau pull --rebase, atau tidak sama sekali.
4. Setelah Anda selesai mengerjakan, lakukan `git push origin <nama branch>`.
5. Kemudian lakukan pull request dengan:
 1. Pergi ke halaman [pull request](https://github.com/oops-wtf/bsky-docs/pulls).
 2. Pilih `New pull request`.
 3. Kemudian pilih link `compare across forks`.
 4. Pilih `base fork: oops-wtf/bsky-docs`, `base: master`, `head fork: <username Anda>/bsky-docs`, dan `compare: <nama branch yang mau di-push>`.
 5. Pilih `Create pull request`, isi judul dan penjelasan singkat tentang apa saja yang sudah Anda kerjakan, lalu pilih lagi `Create pull request`.
 6. Pastikan hasil push Anda lulus build dari CI (jika tidak lulus, lihat pesan kesalahannya, perbaiki, lalu commit lagi).
6. Kontributor akan melakukan review terhadap perubahan yang Anda lakukan. Jika belum disepakati, perubahan Anda akan diberi ulasan dan Anda dapat memperbaikinya. Jika sudah disepakati, kontribusi Anda akan digunakan dan dimasukkan ke dalam panduan Bluesky.
7. Anda bisa kembali ke branch master dengan cara mengetikkan `git checkout master`.
8. Jika kontribusi Anda sudah digabungkan dengan master, Anda bisa melakukan pull dengan mengetikkan `git pull upstream master` untuk mendapatkan perubahan dari repository.

# Panduan Menulis

Pada beberapa laman, masih terdapat beberapa tulisan kosong atau kurang lengkap. Artinya laman ini masih butuh pengembangan tulisan dan Anda bisa menambahkannya sesuai petunjuk.

Untuk membuat tulisan konsisten antar materi, berikut konvensi yang ditetapkan:

1. Gunakan kata "Anda" (diawali huruf kapital) untuk merujuk pada pembaca, bukan "kamu", atau "kalian".
2. Gunakan kata "kita" untuk merujuk pada pembaca dan penulis.
3. Jangan ada penjelasan yang disampaikan dari sudut pandang orang pertama, seperti "saya akan menjelaskan bagaimana ini bekerja..." atau "penulis akan memberi contoh...".
4. Jika Anda menambahkan gambar, masukkan gambar tersebut di folder aset. Masukkan juga berkas mentah gambar tersebut (misalnya .svg, .pdf). Hindari hanya memasukkan gambar jadinya (misalnya .png atau .jpg) karena gambar tidak bisa diedit lagi (kecuali gambar tersebut memang screenshot). Lebih disarankan menggunakan .svg dan pengolah gambar [inkscape](https://inkscape.org/).
