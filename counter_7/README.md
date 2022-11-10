> Jelaskan apa yang dimaksud dengan *stateless widget* dan *stateful widget* dan jelaskan perbedaan dari keduanya.
*Stateless widget* adalah widget yang state-nya tetap dan tidak dapat diubah setelah dibangun oleh Flutter seperti widget Text dan Icon. *Stateful widget* adalah widget yang state-nya dapat diubah setelah dibangun oleh Flutter, seperti widget Form dan TextField.

> Sebutkan widget apa saja yang kamu pakai di proyek ini dan jelaskan fungsinya.
* Scaffold
Framework yang mengimplementasikan struktur dasar layout visual *Material Design*. 
* AppBar
Sebuah app bar *Material Design*. terdiri dari sebuah toolbar dan kemungkinan beberapa widget lain seperti TabBar dan FlexibleSpaceBar. 
* Center
Sebuah widget yang membuat posisi child di dalamnya berada di tengah.
* Column
Sebuah widget yang menampilkan children di dalamnya dalam susunan vertikal
* Padding
Sebuat widget yang memberikan sisipan pada child-nya dengan padding tertentu.
* Row
Sebuah widget yang menampilkan children di dalamnya dalam susunan horizontal
* Text
Sebuah widget yang menampilkan teks.
* Icon
Sebuah widget yang menampilkan ikon-ikon grafis.
* Expand
Sebuah widget yang melebarkan sebuah child dari Row, Column, atau Flex supaya child tersebut dapat mengisi ruang yang tersedia.
* FloatingActionButton
Sebuah *Material Design* floating action button. Floating action button adalah sebuah tombol ikon berbentuk lingkaran yang melayang di atas konten untuk mempromosikan sebuah aksi utama dalam aplikasi.

> Apa fungsi dari setState()? Jelaskan variabel apa saja yang dapat terdampak dengan fungsi tersebut.
SetState() akan menjalankan metode build kembali sehingga dapat merefleksikan nilai yang sudah diperbarui pada layar.

> Jelaskan perbeedaan antara const dengan final.
const merupakan variabel tetap yang tidak dapat diubah pada saat compile-time. final merupakan variabel tetap yang tidakdapat diubah pada saat runtime.

> Jelaskan bagaimana cara kamu mengimplementasikan checklist di atas.
Membuat variabel string \_oddoreven pada class \_MyHomePageState() dan membuat fungsi \_incrementCounter() untuk menambah \_counter pada class \_MyHomePageState() dan membuat fungsi \_reduceCounter() untuk mengurangi \_counter. Setelah itu membuat fungsi \_oddorevencheck() untuk mengecek apakah \_counter ganjil atau genap lalu memanggil SetState() untuk mengubah \_oddoreven menjadi string "Ganjil" atau "Genap" berdasarkan ganjil atau genapnya \_counter. Setelah itu membuat Floating Action Button "Increment" dan "Reduce", dimana ketika button "Increment" ditekan akan menjalankan fungsi \_incrementCounter() sementara ketika "Reduce" ditekan akan menjalankan fungsi \_reduceCounter().
