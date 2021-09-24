 +++
author = "Ferilee"
title = "Membuat Personal Website dengan Hugo Static Site Generator"
date = "2021-09-17"
description = "Framework pembuat website tercepat di dunia."
tags = ["hugo", "website"]
categories = ["idetorial","web design"]
series = ["Themes Guide"]
aliases = ["migrate-from-jekyl"]
image = "hugo-logo-wide.png"
+++

## Pengantar
Memiliki website pribadi (***personal website/blog***) di zaman sekarang sangatlah penting. Selain sebagai identitas di dunia maya, memiliki website juga dapat menambah rasa percaya diri karena tulisan Anda akan diketahui dan dikenal oleh banyak orang di seantero jagad maya hehehee ...
<!--more-->

Pandemi Covid-19 membawa dampak yang luar biasa di semua bidang kehidupan. Pandemi juga mengubah cara kita berinteraksi dengan dunia yaitu menggunakan internet. Lihatlah transformasi digital yang akhir-akhir ini sedang mengubah pola pikir dan kehidupan kita. Terciptanya *marketplace* yang memanjakan konsumen hingga _e-course_ yang membantu memberikan edukasi tanpa sekat ruang dan waktu bagi para pelajar. Sebagian besar memanfaatkan website sebagai media bisnis dan sarana pendidikan.

Setidaknya ada 5 manfaat yang bisa diambil dari adanya website:
1. Sebagai identitas digital dan portofolio
2. Memberikan informasi secara cepat
3. Bisa diakses kapan saja dan dimana saja selama ada koneksi internet
4. Menjangkau lebih banyak viewer
5. Menghemat waktu

Tahukah Anda bahwa membuat website atau blog itu sangatlah mudah ? banyak penyedia website yang gratis dan open source yang bisa Anda manfaatkan. Mungkin Anda pernah mendengar istilah blogger, wordpress, wix, tumblr, hugo, dan penyedia website lainnya ?

Kali ini IDT membuat panduan/ tutorial membuat website statis yang keren dan cepat menggunakan generator website statis "hugo", netlify, dan forestry. Dengan hugo Anda bisa membuat blog, website perusahaan, single landing page, portofolio, atau website dengan banyak halaman.

>**Anda tertarik untuk mulai membuat website ? `good !`**

## Persiapan
Sebelum mulai membuat website dengan Hugo, pastikan Anda memiliki ketiga akun ini terlebih dahulu:
* [github](github.com)
* [netlify](netlify.com)
* [forestry](forestry.io)

## Hugo Template
Hugo menyediakan puluhan template yang keren dan siap pakai. Untuk keperluan latihan kali ini, Anda bisa menggunakan salah satu template yang dipilihkan oleh Trainer IDT yaitu Hugo Profile.
Langkah-langkah menggunakan template ini:
1. Login ke akun github Anda
2. klik >> https://github.com/gurusabarish/hugo-profile
3. klik tombol `use this template` untuk menggunakan template ini.
![](01-use-this-template.png)
4. Isikan nama repository baru yang akan digunakan untuk menyimpan template. Sebagai contoh, penulis memberikan nama `blog` sebagai nama repository baru seperti pada gambar berikut.
5. Klik tombol `Create repository from template` untuk mulai menyalin template ke repository Anda.
![](02-nama-repo.png)

## Netlify
Anda kini telah memiliki repository yang berisi template hugo-profile di github. Langkah berikutnya adalah men-deploy repository tersebut menggunakan netlify sehingga website Anda bisa diakses oleh orang lain.
Langkah-langkah men-deploy repository:
1. Login [netlify](https://app.netlify.com) menggunakan akun github Anda.
2. Klik tombol `New site from Git`
![](03-new-site-from-git.png)
3. Hubungkan dengan provider Git, pilih `Github`.
![](04-connect-to-git.png)
4. Pilih repository yang sudah dibuat di Github sebelumnya.
![](05-pilih-repo-netlify.png)
5. Klik tombol `Deploy site` untuk mulai men-deploy repository Anda.
![](06-deploy-site.png)
6. Ganti nama website Anda melalui menu `Site settings > Change site name`
![](07-site-setting.png)\
![](08-change-site-name.png)\
![](09-site-name.png)
7. Simpan alamat website Anda dan bagikan kepada teman/ saudara/ kenalan melalui media sosial (facebook/ whatsapp/ telegram/ instagram atau yang lainnya)
![](10-alamat-netlify.png)
8. Berikut adalah tampilan website yang sudah berhasil Anda deploy.
![](11-preview-site.png)

## Forestry
Forestry adalah sebuah CMS yang akan membantu Anda membuat artikel/ _post_ secara cepat tanpa harus menguasai bahasa pemrograman.
Langkah-langkah membuat artikel dengan menggunakan forestry:
1. Login [forestry](https://forestry.io/) menggunakan akun github Anda.
![](12-login-forestry.png)
![](13-login-via-github.png)
2. Tambahkan website dengan menekan tombol `Add site`
![](14-tambahkan-situs.png)
3. Pada Static Site Generator, pilih `Hugo`.
![](15-pilih-ssg.png)
4. Pilih `Github` pada provider Git.
![](16-pilih-provider-git.png)
5. Pilih repository yang ingin Anda pakai dan pada bagian `config path` ketikkan `website/config.yaml`. Klik tombol `check for config` untuk mencari keberadaan file konfigurasi website Anda. Klik tombol `Next` jika file konfirasi ditemukan (_config file found_).
![](17-pilih-repository.png)
6. Klik tombol `mark as done` pada proses setup, lalu klik tombol `complete setup` untuk menuntaskan pengaturan.
![](18-mark-all-as-done.png)\
![](19-complete-setup.png)
### Membuat Artikel (_Post_) Baru
1. Template yang Anda salin di bagian awal tutorial ini memberikan 4 artikel sebagai contoh. Artikel ini bisa Anda edit/ ganti atau hapus jika tidak diperlukan.
![](20-jumlah-post.png)
2. Untuk membuat artikel (_post_) baru, klik tombol `Create New > Blog`
![](21-membuat-post-baru.png)
3. Buat template untuk artikel baru `(Create template)`
![](22-membuat-template-blog.png)
4. Buat template dari dokumen yang sudah tersedia `(Create based on existing document)`
![](23-pilih-dari-dokumen-yangada.png)
5. Isikan parameternya seperti contoh pada gambar berikut. Klik tombol `Create template` untuk mengakhiri.
![](24-isikan-parameternya.png)
6. Ketikkan judul artikel, nama penulis, dan isi artikel. Pastikan untuk menonaktifkan draft `(Draft > off)` lalu simpan/ save agar artikel muncul di website Anda.
![](25-isi-semua-field.png)
7. Lihat hasilnya di alamat website Anda.
![](26-view-site.png)
