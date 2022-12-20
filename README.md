# Final Struktur Data
Tugas Struktur Data, materi Stack &amp; Queue

## Queue
### Definisi
Queue adalah struktur data linier yang menerapkan prinsip operasi di mana elemen data yang masuk pertama akan keluar lebih dulu. Prinsip ini dikenal dengan istilah **FIFO (First In, First Out)**.

Struktur data Queue disusun secara horizontal dan terbuka di kedua ujungnya. Ujung pertama (*head*) digunakan untuk menghapus data sedangkan ujung lainnya (*tail*) digunakan untuk menyisipkan data.

### Operasi Queue
Queue adalah struktur data abstrak (ADT) yang memungkinkan operasi berikut:

* *Enqueue*: Menambahkan elemen ke akhir antrian.
* *Dequeue*: Menghapus elemen dari depan antrian.
* *IsEmpty*: Memeriksa apakah antrian kosong.
* *IsFull*: Memeriksa apakah antrian sudah penuh.
* *Peek*: Mendapatkan nilai bagian depan antrian tanpa menghapusnya.
* *Initialize*: Membuat antrian baru tanpa elemen data (kosong).
Namun, secara umum antrian memiliki 2 operasi utama, yaitu enqueue dan dequeue.

### Fungsi dan Kegunaan Queue
Berikut ini adalah beberapa fungsi queue yang paling umum dalam struktur data:
* Queue banyak digunakan untuk menangani lalu lintas (*traffic*) situs web.
* Membantu untuk mempertahankan *playlist* yang ada pada aplikasi *media player*
* Queue digunakan dalam sistem operasi untuk menangani interupsi.
* Membantu dalam melayani permintaan pada satu sumber daya bersama, seperti printer, penjadwalan tugas CPU, dll.
* Digunakan dalam transfer data asinkronus misal *pipeline*, *IO file*, dan *socket*.


## Stack
### Definisi
Stack adalah daftar terurut di mana pengambilan dan penambahan item terjadi hanya pada satu ujung.

Ketika prinsip FIFO (First In First Out) digunakan dalam Queue, prinsip LIFO (Last In Fist Out) digunakan dalam Stack, di mana elemen terakhir ditambahkan atau data adalah elemen pertama yang diambil dari Stack itu juga.

Untuk mudahnya, misalkan kita sedang menumpuk sebuah buku, buku terakhir dalam tumpukan (stack) akan menjadi buku pertama yang diambil karena berada di bagian atas tumpukan, sehingga objek akan terdorong dari bagian atas tumpukan.

### Fungsi dalam Stack
* Fungsi *init* : fungsi ini digunakan untuk menginisialisasi atau membuat stack baru yang belum terisi atau masih kosong.
* Fungsi *full* : fungsi untuk mengetahui apakah stack dalam keadaan penuh.
* Fungsi *empty* : digunakan untuk mengetahui apakah stack dalam keadaan kosong atau telah terisi.
* Fungsi *clear* : digunakan untuk mengosongkan stack dimana stack dianggap kosong apabila puncak stack berada pada posisi -1.
* Fungsi *push* : digunakan untuk menambahkan data ke dalam stack yang dalam penambahanya data tidak dapat ditambahkan jika stack dalam keadaan full (penuh).
* Fungsi *pop* : digunakan untuk mengambil data teratas stack dengan syarat bahwa stack dalam keadaan tidak kosong.

### Operasi pada Stack
* *Push* : Untuk menambahkan elemen atau data, dimana data paling akhir akan diletakkan di paling atas.
* *Pop* : untuk mengambil atau mengeluarkan data dimana data yang diambil adalah data terakhir atau paling atas.
* *Clear* : digunakan untuk mengosongkan stack.
* *IsEmpty* : untuk memeriksa apakah stack sudah kosong.
* *IsFull* : untuk memeriksa apakah stack dalam keadaan penuh.
