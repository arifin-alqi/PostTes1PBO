# PostTest PBO 1

# **Manajemen penyewaan/pembelian apartemen**
## 1. Konsep Program
  Disini saya membawa tema "manajemen penyewaan/pembelian apartemen", yang menggunakan sistem CRUD yaitu:
  a. Create digunakan untuk menambah data kamar.
  b. Read digunakan untuk menampilkan menu kamar apa saja yang tersedia.
  c. Update digunakan untuk mengubah status kamarnya yang dimana di ubah ke tersedia, disewa dan terjual
  d. Delete digunakan untuk menghapus data kamar kalo kamar itu sudah di beli, sehingga data kamar tidak pernah lagi kosong kecuali dijual kembali.

## 2. Tujuan Program
  Tujuan Program ini digunakan untuk mempermudah pendataan dan juga melihat ketersedian kamar apakah kamar tersebut sudah dibeli/disewa sehingga para pelanggan bisa tau.

## 3. Alur Program
  <img width="576" height="103" alt="image" src="https://github.com/user-attachments/assets/c4d740f7-e74c-4968-b1ee-9afd396ad914" />
  
  Package berguna untuk mengelompokkan kelas, antarmuka, dan sub-paket yang terkait secara logis, sehingga memudahkan pengorganisasian, pengelolaan basis kode yang besar, dan menghindari konflik nama antar kelas yang memiliki nama sama. Import digunakan untuk menambah fitur agar bisa digunakan contoh seperti AraayList dan Scanner.

  <img width="959" height="376" alt="image" src="https://github.com/user-attachments/assets/d73181de-33b5-4807-9051-7ecc9b2ef026" />

  Class digunakan untuk mengelompokkan properti seberapa banyak pun, terus tipe properti juga bisa kita masukkan untuk memberi jelas bahwa tipe atribut yang digunakan. Terus ada construktor yang dimana digunakan untuk menganilisasikan objek yang baru dibuat, terus this digunakan untuk membedekan atribut class dengan parameter.

  <img width="780" height="247" alt="image" src="https://github.com/user-attachments/assets/c19b5132-595b-4750-b0eb-085e6b4a08c3" />

  Menthod tampilkaninfo digunakan untuk menampilkan semua detail unit pada apartemen Ketika di run sehingga bisa tersusun lebih rapi dan terstruktur.

  <img width="778" height="334" alt="image" src="https://github.com/user-attachments/assets/f06ad2a4-0419-4fed-bd8e-2da693736d86" />

  Arraylist yang digunakan untuk menyimpan banyak objek dan juga ada method tampilkandaftar unit jadi disini nanti dia hanya tinggal mengambil method ini agar bisa menampilkan daftar unit.

  <img width="934" height="371" alt="image" src="https://github.com/user-attachments/assets/a9b75890-33c3-41a9-ae51-92e0d1c5c18a" />

  disini ada method update status unit yangberguna untuk  mengubah status unit dari tersedia/terjual/disewa, juga ada menthod tekan enter yang berguna untuk menjeda sebelum kembali kemenu pada tampilakan daftar unit.

  <img width="767" height="157" alt="image" src="https://github.com/user-attachments/assets/4a487d66-a27d-4c52-a901-61dfd60cf4c6" />

  diatas itu dimana kita memasukkan objek-objek untuk setiap atibut yang diawal sesuai tipe datanya jadi dia akan membaca semua buku yang sudah kita masukkan.

  <img width="725" height="403" alt="image" src="https://github.com/user-attachments/assets/b97c0d09-4914-4dc8-be66-bdc764b55d19" />

  Selanjutnya disini ada int pilihan yang berfungsi untuk kita memilih menu sesuai yang diinginkan, jadi nanti akan di menampilkan pilihan terus kita tinggal memasukkan angka yang sesuai dengan yang kita mau.

  <img width="894" height="365" alt="image" src="https://github.com/user-attachments/assets/58aa6e14-ae4a-468e-84cf-2a498a381165" />

  Terus ada switch yang bisa menentukan case pilihan kita dan ada case 1 satu jadi kalo memilih angka 1 maka dia akan masuk ke program ini dan begitu angka lainnya, nah di case 1 ini kita bisa menambahkan unit  yang mungkin unit itu sudah dijual pemiliknya kembali sehingga menjadi tersedia lagi, terus dia akan menampilkan pada unit berhasil di tambahkan terus dia akan Kembali ke menu pilihan lagi karena sudah di berikan break pada case.

  <img width="645" height="100" alt="image" src="https://github.com/user-attachments/assets/dbf0a7bc-9d4f-4b37-a3be-c0fc71ccea50" />

  Nah di case 2 dia akan menampilkan unit yang sudah kita tambahkan dan juga disini ada fitur tekan enter jadi kita harus menekan enter dulu agar bisa kembali ke menu kembali.

  <img width="774" height="201" alt="image" src="https://github.com/user-attachments/assets/ca4de9a3-0b37-40bd-8f48-e5509bffbe3b" />

  Selanjutnya di case 3, pertam dia akan menampilkan unit unit agar kita bisa tau unit mana yang mau diubah, terus kita disini bisa mengubah status ketersediaan dengan memasukkan id kamar tersebut.

  <img width="778" height="460" alt="image" src="https://github.com/user-attachments/assets/0cb7c83f-9799-4c16-835f-edbc0f709fab" />

  Case 4 sama seprti case 3 jadi pertama dia akan menampilkan unit unit agar kita bisa milih unit mana yang mau di hapus dikarena kamar itu sudah di beli, jadi kenapa dihapus agar pelanggan tidak mencari unit yang sudah di beli jadi dia hanya akan membaca unit tersedia saja, jadi disini kita bisa menghapus unitnya hanya dengan memasukkan id unit tersebut.

  <img width="752" height="240" alt="image" src="https://github.com/user-attachments/assets/0b1c5232-5fc0-4532-a1ce-61f217d5e463" />

  Terus terakhir di case 5 jadi saat kita memilih ke case 5 maka program akan selesai, terus kenapa ada while pilihan 5 jadi itu berguna agar saat kita memasukkan angka yang lebih dari 5 dia akan menampilkan bahwa pilihan tidak valid.

## 4. Hasil Output

  <img width="832" height="764" alt="image" src="https://github.com/user-attachments/assets/54708220-3e9b-4df9-990c-de98a8ee2e80" />

  <img width="835" height="763" alt="image" src="https://github.com/user-attachments/assets/40f80fe8-1d5f-494d-acc3-a8c55d1e2444" />

  <img width="834" height="763" alt="image" src="https://github.com/user-attachments/assets/fc4fe4a3-bb77-470b-a715-c4730df6ea7b" />

  <img width="832" height="766" alt="image" src="https://github.com/user-attachments/assets/628dcfb3-93ee-494a-9380-d28a4262f76a" />

  <img width="834" height="760" alt="image" src="https://github.com/user-attachments/assets/53368ed4-e275-4dcc-ab50-11992914bee4" />

  <img width="832" height="759" alt="image" src="https://github.com/user-attachments/assets/5ffe3832-1a55-40d1-9fc7-91fe6cb3eaf6" />

  <img width="825" height="545" alt="image" src="https://github.com/user-attachments/assets/b33104b5-c637-41f5-b473-4013adf89af4" />

