---
title: "Data terbuka di bidang geologi"
author: "Dasapta Erwin Irawan"
affiliation: "Institut Teknologi Bandung / INArxiv"
---

# Data terbuka di bidang geologi

Oleh: Dasapta Erwin Irawan (ITB / RINarxiv)

# Pendahuluan

- Tujuan: 
  - mempelajari karakteristik data terbuka di bidang geologi
  - mempelajari ketersediaan data terbuka di bidang geologi
  - menyiapkan draft panduan publikasi data terbuka di bidang geologi dan ilmu kebumian pada umumnya
- Metode:
  - Telaah literatur menggunakan basis data: Scopus, WoS, dan Lens
  - Mengambil contoh kasus data terbuka, masing-masing satu untuk setiap bidang yang diampu oleh dosen-dosen Teknik Geologi ITB
  - Bidang-bidang yang akan dipelajari: 
    1. geologi struktur/geodinamika, 
    2. petrologi/petrografi/mineralogi,
    3. paleontologi/mikropaleontologi, 
    4. geologi teknik, 
    5. hidrogeologi.
- Contoh kasus:
  1. Bidang petrologi/petrografi/mineralogi ([https://www.aapg.org/publications/blogs/wwwupdate/article/articleid/57056/free-access-to-aapgs-discovery-series-10-and-15-full-data-set-tutorials](https://www.aapg.org/publications/blogs/wwwupdate/article/articleid/57056/free-access-to-aapgs-discovery-series-10-and-15-full-data-set-tutorials))
  2. Bidang paleontologi/mikropaleontologi
  3. Bidang geologi teknik
  4. Bidang hidrogeologi
  5. Bidang geologi struktur/geodinamika

# Bidang petrologi/petrografi/mineralogi

## Contoh 1

Saya menerima contoh data petrologi dan petrografi ini dari kolega saya, [Reynaldy Fifaris](https://scholar.google.co.id/citations?hl=en&user=20KtMUQAAAAJ&view_op=list_works&sortby=pubdate). Data tersebut berasal dari AAPG Datapages yang dibagikan kepada publik ([Tautan pengunduhan](http://www.datapages.com/files/ds10)). Ukuran berkas (dalam format `zip`) adalah 200 MB. Data tersebut merupakan data telaah ptrografi berupa foto-foto sayatan tipis yang telah diolah dan disajikan sebagai tutorial labotarorium. Tutorial tersebut disusun oleh [Kitty Miliken](https://scholar.google.com/citations?user=RNFK9SEAAAAJ&hl=en). 

> *Kitty Milliken* is a Senior Research Scientist at the Bureau of  Economic Geology at UT Austin. She received a B.A. in geology at  Vanderbilt University and completed her graduate work (M.A. and Ph.D) at UT Austin. Her research focuses on the integration of imaging and  chemical analysis to decipher the chemical and mechanical histories of  sedimentary rocks. Kitty served as Co-Editor of the Journal of  Sedimentary Research (2004-2008).

**Catatan**:

- Informasi cara merujuk tutorial tidak disajikan dengan jelas. Mestinya ada bagian `Bagaimana cara merujuk` dalam halaman utama.
- Jadi akan ada dua tingkat rujukan:
  - rujukan kepada tutorial
  - rujukan kepada data
- Sayangnya saya belum menemukan keduanya.
- Berkas `zip` berisi: perangkat lunak pemutar tutorial dan dataset. Seluruh dataset berupa foto sayatan tipis, tanpa indikasi lokasi dan koordinat, minimum dalam bentuk tabel dataset. 
- Pada dasarnya kalaupun dokumen tutorial dan dataset adalah berasal dari KM, maka tutorial tetap harus merujuk kepada dataset, bisa dalam bentuk tautan ke dataset.  
- Struktur dokumen akan terlihat seperti ini.

![gbr-struktur-tutorial](/Users/erwin/Downloads/IN-PROCESS/open-data-geologi/gbr-struktur-tutorial.png)





## Contoh 2

Contoh lain akan ditambahkan.



# Bidang Paleontologi/mikropaleontologi

## Contoh 1

- Berikut ini adalah makalah tentang fosil buaya purba yang ditulis oleh [Tennant dan Mannion (2014)](https://peerj.com/articles/599/) yang terbit di Jurnal [PEERJ](peerj.com). 
- Pada dasarnya, makalah ini membahas [deskripsi temuan fosil spesies baru](https://peerj.com/articles/599/#supp-2) oleh penulis yang sama.  Di dalam makalah tersebut penulis menyampaikan [data mentah berupa hasil pengukuran morfometri fosil](https://dfzljdn9uc3pi.cloudfront.net/2014/599/1/S1_morphometric_data.xlsx) (dalam format `xlsx`). 
- Jadi deskripsi fosil dipisahkan dari makalah utama, begitu pula data pengukuran morfometrinya. 
- Tidak hanya itu, foto-foto fosilnya pun diunggah sebagai file terpisah ([https://dfzljdn9uc3pi.cloudfront.net/2014/599/1/fig-3-full.png](https://dfzljdn9uc3pi.cloudfront.net/2014/599/1/fig-3-full.png)). Saat saya google nama spesies, maka foto dari makalah ini muncul dalam hasil pencarian. Artinya foto fosil dapat ditemukan secara terpisah, sehingga dapat menambah peluang makalah utama ditemukan oleh calon pembaca. Penemuan fosil ini beserta lokasinya telah didaftarkan di basis data [Zoobank](http://zoobank.org/References/B7CC4367-4203-4AED-8C30-2D7E4E71665D).  
- Jadi kalau kita petakan posisi makalahnya akan terlihat seperti ini.

 ![gbr-struktur-makalah-peerj](/Users/erwin/Downloads/IN-PROCESS/open-data-geologi/gbr-struktur-makalah-peerj.png)

## Contoh 2

- Contoh ini saya ambil dari repositori data [Pangea](Pangea.de) yang merupakan repositori data kebumian dan lingkungan. Repositori ini dikelola oleh Alfred Wegener Institute, Helmholtz Center for Polar and Marine Research (AWI) dan the Center for Marine Environmental Sciences, University of Bremen (MARUM). 

- Keunikan repositori ini adalah hanya menerima data yang memiliki koordinat geospasial yang jelas. Sebelum terbit, data ditelaah oleh tim terutama untuk aspek apakah data dapat diplot dengan benar. Penulis pun diminta membuat abstrak tentang mengapa data diambil, bagaimana caranya, dan apa target luarannya.

- Mengunggah data ke repositori ini gratis untuk siapapun ([Contoh data dari saya dkk](https://doi.pangaea.de/10.1594/PANGAEA.862987)). Seluruh data yang diunggah berlisensi CC-BY (Creative Commons Attribution), yang berarti **pembaca dapat menggunakan ulang material secara bebas dengan kewajiban menyitirnya**.

- Data yang saya contohkan berjudul **[Hessler, Ines](https://doi.pangaea.de/10.1594/PANGAEA.816694#); Young, Martin; [Holzwarth, Ulrike](https://doi.pangaea.de/10.1594/PANGAEA.816694#); [Mohtadi, Mahyar](https://doi.pangaea.de/10.1594/PANGAEA.816694#); [Lückge, Andreas](https://doi.pangaea.de/10.1594/PANGAEA.816694#); [Behling, Hermann](https://doi.pangaea.de/10.1594/PANGAEA.816694#) (2013):**  Organic-walled dinoflagellate cysts analysis and statistical analysis of 116 surface sediment samples from the eastern Indian Ocean. *PANGAEA*, https://doi.org/10.1594/PANGAEA.816694.

- Data di atas terhubung dengan makalah utama ini: Hessler, I et al. (2013): Imprint of  eastern Indian Ocean surface oceanography on modern organic-walled  dinoflagellate cyst assemblages. *Marine Micropaleontology*, **101**, 89-105, https://doi.org/10.1016/j.marmicro.2013.02.005. 

- Kebetulan makalah utamanya sendiri terbit di jurnal non-OA. Artinya, pembaca tetap bisa mengakses dataset, walaupun makalah utamanya tidak dapat diakses. Bila [halaman utama makalahnya dibuka](https://doi.org/10.1016/j.marmicro.2013.02.005), maka pembaca dapat membaca bagian di bawah ini. Jangan lupa membaca tulisan paling bawah `Copyright 2013 Elsevier B.V. All rights reserved`, yang artinya pembaca harus minta izin ke pemegang Hak Cipta (bukan penulis, tetapi Elsevier) kalau ingin menggunakan ulang bagian (bahkan menyitirnya). Untung penulisnya mengunggah datanya ke tempat di luar otoritas penerbit.

   ![gbr-section-dataavailability](/Users/erwin/Downloads/IN-PROCESS/open-data-geologi/gbr-section-dataavailability.png)