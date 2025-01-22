---
title: DOUBLE LINKED LIST
summary: Mata Kuliah Algoritma dan Struktur Dasar
date: 2023-10-27
# Featured image
# Place an image named `featured.jpg/png` in this page's folder and customize its options here.
image:
  caption: "Image credit: [**Unsplash**](https://unsplash.com)"

authors:
  - admin
---

Double Linked List adalah jenis linked dimana kita bisa melintasinya secara dua arah . Tidak seperti singly linked list yang berisi satu pointer di double linked list berisi satu pointer tambahan yang di sebut previous pointer yang menunjuk ke linked sebelumnya jadi ada 3 bagian yaitu prev , *pointer , dan *next pointer. berikut gambar double linked list :

Operasi Double linked list:

1. Penyisipan: Menambahkan elemen di awal, akhir, atau setelah node tertentu dalam daftar.

2. Penghapusan: Menghapus elemen dari daftar, baik dari awal, akhir, atau berdasarkan kunci yang diberikan.

3. Traversal: Menampilkan elemen daftar dalam arah maju dan mundur.

Penyisipan Double linked list :

Penyisipan di awal: Untuk menyisipkan linked baru di awal .Daftar : Buat node baru dengan data yang diberikan. Arahkan penunjuk berikutnya ke simpul pertama saat ini. Perbarui penunjuk sebelumnya dari simpul pertama saat ini untuk menunjuk ke simpul baru. Perbarui penunjuk kepala untuk menunjuk ke simpul baru. Operasi ini memastikan bahwa node baru menjadi node pertama dalam daftar sambil mempertahankan hubungan yang tepat dengan node yang berdekatan.

{{< toc mobile_only=true is_open=true >}}

_Referensi tambahan:_ [Blogspot](https://annisanch.blogspot.com)
