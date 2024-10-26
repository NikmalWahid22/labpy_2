# LAPORAN PRATIKUM 2

## PROGRAM PEMESANAN TIKET BIOSKOP
### KODE PEMROGRAMAN 
Pada tahap awal terdapat Variabel tipe_tiket. Kode ini meminta pengguna untuk memasukan tipe tiketnya, apakah "reguler" atau "VIP". Hasil input ini akan disimpan di variabel tipe_tiket. Selain variabel tipe_tiket terdapat variabel status_member, kode ini meminta pengguna mengenai status member mereka, Apakah Anda memiliki status member "YA" Atau "TIDAK". Hasil input ini akan disimpan di variabel status_member <p>
![Gambar 1](sspy/sspy1.png)

### TAHAP KEDUA
Pada tahap ini,menggunakan struktur if-else untuk menentukan harga tiket berdasarkan tipe tiket. Di Tahap ini terdapat tiga kemungkinan yang pertama. Jika tipe_tiket adalah "reguler", maka variabel harga diatur menjadi 50.000 (harga tiket reguler). Kemungkinan yang kedua jika tipe_tiket adalah "vip", maka variabel harga diatur menjadi 100.000 (harga tiket VIP). Dan kemungkinan yang ketiga yaitu jika pengguna memasukkan tipe tiket selain "reguler" atau "vip", harga diatur menjadi 0, dan pesan "Tipe tiket tidak valid." akan ditampilkan. Ini juga berfungsi sebagai validasi tipe tiket yang dimasukkan pengguna. <p>
![Gambar 2](sspy/sspy2.png)

### TAHAP KETIGA
Pada tahap ini memastikan bahwa proses akan berlanjut apabila tipe tiket valid(harga tidak 0). Jika Harga 0 karena tipe tiket tidak valid maka program akan melewati blok ini dan tidak akan menghitung harga akhir dan mencetak hasil. <P>
![Gambar 3](sspy/sspy3.png)

### TAHAP KEEMPAT 
Pada bagian ini operator ternary digunakan untuk menghitung harga akhir berdasarkan status member :
Jika status member "ya" maka pengguna yang memiliki kartu akan mendapat diskon 20%
Namun jika Status member "tidak" maka tidak ada potongan harga.
![Gambar 4](sspy/ss4.png)

### TAHAP KELIMA
Pada bagian ini akan menampilkan hasil akhir 
tipe-tiket = jenis tiket yang dipilih
status_member = Status member pengguna
total_harga = harga yang harus dibayar
![Gambar 5](sspy/sspy5.png)

## CONTOH 
### Kasus 1 : Memilih tiket reguler dan mempunyai kartu member
![Gambar 6](sspy/sspy7.png)

### Kasus 2 : Memilih tiket reguler dan tidak mempunyai kartu member
![Gambar 7](sspy/sspy8.png)

### Kasus 3 : Memilih tiket VIP dan mempunyai kartu member 
![Gambar 8](sspy/ss9.png)

### Kasus 4 : Memilih tiket VIP dan tidak mempunyai kartu member 
![Gambar 9](sspy/ss10.png)

### Kasus 5 : Pengguna memasukkan tipe tiket yang tidak valid
![Gambar 10](sspy/sspy11.png)


## FLOWCHART 
### TAHAP AWAL 
Untuk memulai Flowchart gunakan terminator sebagai penanda awal flowchart. Setelah itu masuk ke tahap input program menggunakan bentuk paralelogram. Input yang pertama yang di gunakan untuk tipe_tiket sedangkan input yang kedua digunakan untuk mengetahui status member pengunjung.
![Gambar 11](sspy/sspy12.png)

### TAHAP KEDUA
Pada tahap ini pengambilan keputusan pertama dilakukan yaitu mengenai tipe tiket di flowchart tersebut ditulis "Tipe Tiket == reguler?", disini terdapat dua keputusan yaitu ya dan tidak. Jika ya maka tiket tersebut adalah reguler dan jika tidak maka tiket tersebut adalah VIP. Setelah keputusan pertama selesai maka akan lanjut keputusan ke-2 yaitu mengenai status member, jika status member tersebut adalah "ya" maka akan mendapat potongan harga. Jika "Tidak" maka tidak akan mendapat potongan harga. <p>
![Gambar 12](sspy/ss14.png)

### TAHAP AKHIR 
Output akan menampilkan program yang harus dibayar dan progam akan berakhir 
![Gambar 13](sspy/ss13.png)
