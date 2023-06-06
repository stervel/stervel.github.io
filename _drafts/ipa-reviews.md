---
layout: post
tags: writing
title: draf-ipa
---

Saya cukup terganggu ketika font yang saya sukai tidak menampilkan karakter IPA dengan baik (diakritik yang salah tempat, tie-bar yang memotong huruf yang ditempelnya, dan lain sebagainya).Ketimbang melanjutkan menulis, yang tentu lebih penting, saya malah asyik tenggelam memilih-milih font baru yang indah dan komprehensif secara teknis. Tak ayal bahwa dokumentasi Bahasa Krewi jarang punya kemajuan yang substansial.

Ide kompilasi ini terpantik saat saya tahu bahwa daftar catatan tentang pilihan font IPA saya mulai terlihat banyak. Hal lain yang mendorong tulisan ini ada juga karena luar biasa besarnya jumlah waktu dan pengetahuan yang diperlukan untuk mencari dan memilah-milah typeface yang mengandung glif IPA di dalamnya. Oleh karena itu, saya tulis ini untuk membantu diri saya sendiri di masa depan dan, harapannya, setiap orang yang kebetulan sedang membaca ini.

## Ikhtisar: Detail teknis nerd stuff
Sebagai sistem transkripsi, IPA punya tujuan untuk secara presisi menggambarkan *speech sound* ke dalam bentuk visual tertulis. Masalahnya, organ vokal manusia sedemikian fleksibel dan kompleks sehingga mampu menciptakan banyak bunyi yang berbeda. IPA, mengadopsi sistem alfabetis,[^1] dibebankan tugas yang berat untuk mewakili banyaknya suara manusia.[^2] Oleh karena itu, per pembaruan 2005, terdapat 107 huruf (termasuk huruf-huruf IPA yang sudah tersedia dalam set Aksara Latin dan Aksara Yunani) perlu dipikirkan untuk ditempatkan dalam blok IPA. Banyaknya jumlah huruf yang sepenuhnya baru yang perlu digambar ulang membuat banyak desainer font enggan untuk mengakomodasi IPA karena memang perlu pengetahuan tambahan khusus dan ukuran-ukuran tertentu untuk mendesain dan mengakomodasi fitur-fitur IPA.

<gambar 1>

Huruf yang terdapat pada IPA tidak dimaksudkan untuk dimengerti sebagai simbol teknis. Berbeda dengan, katakan, kebanyakan notasi matematika (mis. + ≥ ⊃) yang memiliki desain yang mandiri, huruf-huruf pada IPA perlu dimengerti sebagai huruf selayaknya desain Aksara Latin. Karena alasan tersebut, rupa huruf IPA perlu diperlakukan dan didesain selayaknya huruf-huruf Latin yang menyertainya. Masalah ini menjadi masalah yang penting pada detail font dengan gaya humanis (i.e. meniru rupa gaya tulisan manusia, berkebalikan dengan gaya abstraksi huruf seperti pada font grotesque). Mengapa?

<pic?>

Ada banyak huruf IPA yang memiliki rupa turunan dari yang sudah ada. Lahir di masa *letterpress*, banyak huruf IPA 
    hanyalah bentuk yang diputar/hasil cerminan dari huruf yang sudah ada. Namun, seperti yang terlihat, beberapa  

[^1]: Pendekatan lain yang menarik untuk mengatasi problem tersebut adalah dengan melihat segmen suara manusia sebagai hal kombinatoris. Banyak alternatif dari IPA seperti misalnya [UPA](https://omniglot.com/conscripts/upa.htm), [Alfabet Musa](https://musa.bet/home.htm), dan [UPFA](https://redd.it/137skmk) berdasar dari pendekatan tersebut dan mengambil sistem *featural* (berciri) sebagai basis visual. (TODO make article about "against featural")
[^2]: Kemewahan yang kita rasakan (dikelilingi dengan perangkat yang mendukung [Unicode](https://en.wikipedia.org/wiki/Unicode)) tidak dialami oleh orang-orang sebelum kita. Oleh karena itu, sistem seperti X-SAMPA](https://en.wikipedia.org/wiki/X-SAMPA) (turunan SAMPA) lahir sebagai *"hack"* dari lingkungan yang kebanyakan hanya mendukung [ASCII](https://en.wikipedia.org/wiki/ASCII). Oleh karena itu, nasib yang dialami X-SAMPA lebih berat karena harus mewakili banyaknya segmen suara hanya dengan 95 karakter (bandingkan dengan Unicode v15 yang mendukung lebih dari 800.000 karakter. Saat artikel ini ditulis, hanya baru 149.186 karakter terisi).

