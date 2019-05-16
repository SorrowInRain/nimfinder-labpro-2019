# NIM Finder

Disini, terdapat spesifikasi singkat dari aplikasi yang Anda harus bangun. Spesifikasi lengkap dapat dibaca pada [dokumen](https://docs.google.com/document/d/1744BZnVDGIzEUiLb9780qJAjQD30bOBQhSamQIX6fRk/edit?usp=sharing) yang telah diberikan.

## Spesifikasi Aplikasi
Pada tugas kali ini, Anda diminta untuk membuat sebuah aplikasi yang dapat berkomunikasi dengan API NIM Finder yang diberikan. Aplikasi dibuat menggunakan __React__. 

Aplikasi dapat melakukan __pencarian mahasiswa__, baik __berdasarkan NIM__ (atau NIM parsial) ataupun __berdasarkan nama__ (atau nama parsial). Adapun operasi pencarian nantinya akan ditangani oleh API yang telah disediakan (lihat di bagian Spesifikasi API dibawah). Namun, sebelum dapat melakukan pencarian, pengguna aplikasi harus melakukan __login__ terlebih dahulu (juga disediakan oleh API).

Anda disarankan menggunakan [create-react-app](https://github.com/facebook/create-react-app). Anda akan perlu melakukan *inheritance* terhadap kelas *Component* milik React. React memiliki konsep OO, sehingga Anda diharapkan dapat memanfaatkan konsep ini juga. Anda juga diharapkan menggunakan *design pattern* yang menurut Anda cocok untuk digunakan, misal:

* Filter Design Pattern
* Decorator Design Pattern
* Strategy Design Pattern
* dan lain-lain

Aplikasi Anda harus mampu diakses lewat *Github Pages*. Pada dasarnya, Anda perlu *push* hasil *build* dari React ke branch "gh-pages" untuk dideteksi oleh *Github Pages*. Jika Anda membutuhkan lebih dari 1 route, Anda bisa melakukan parsing pada url dengan mempelajari [*repository*](https://github.com/rafrex/spa-github-pages) ini.

## Informasi Pengerjaan dan *Deliverables*
* Aplikasi dibuat dengan menggunakan __React__.
* Aplikasi __harus memanfaatkan API__ yang disediakan.
* Untuk mengerjakan tugas ini, Anda diharuskan untuk melakukan *fork* terhadap repository ini. Anda kemudian mengerjakan tugas ini di repository yang baru saja Anda *fork* tersebut. 
* Batas akhir pengerjaan adalah __20 Juni 2019, pukul 23.59__. Pengumpulan dilakukan dengan membuat __*merge request*__ ke repository ini kembali, dengan “TugasSeleksi2_<NIM Anda>” sebagai judul dari merge request. (contoh : TugasSeleksi2_13516000) 
* Deliverables yang harus ada dalam repository Anda adalah :
  * *Source Code*
  * File *Readme* (hapus spesifikasi ini), minimal berisi hal-hal berikut ini :
    * Nama aplikasi, nama Anda, dan NIM Anda
    * Cara memasang/menjalankan aplikasi
    * Cara menggunakan aplikasi (termasuk *screenshot* dari aplikasi Anda)
    * Desain aplikasi (*class* yang dibuat/digunakan, bagaimana aplikasi bekerja, dsb.)
    * *Library*/kakas yang digunakan dalam aplikasi Anda, beserta sumbernya (jika ada)
    * *Review* terhadap desain API yang ada (mana yang kurang baik dan bagaimana yang lebih baik)
  * Susunlah *Readme* semenarik mungkin
