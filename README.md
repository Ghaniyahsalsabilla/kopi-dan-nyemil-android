#  Kopi dan Nyemil

## Deskripsi

**Kopi dan Nyemil** merupakan aplikasi pemesanan kopi dan makanan ringan berbasis Android yang dikembangkan menggunakan Kotlin dan XML Layout.

Aplikasi ini dirancang untuk memudahkan pengguna melihat daftar menu, memilih produk, mengisi informasi penerima, dan melakukan konfirmasi pesanan melalui perangkat Android.

## Fitur Aplikasi

1. **Welcome Page** — Halaman awal aplikasi.
2. **Sign Up** — Pilihan untuk masuk atau membuat akun.
3. **Register** — Pendaftaran akun pengguna.
4. **Login** — Masuk menggunakan username dan password yang telah didaftarkan.
5. **Home** — Menampilkan sapaan pengguna dan daftar produk.
6. **Daftar Produk** — Menampilkan enam pilihan kopi dan makanan ringan beserta gambar dan harga.
7. **Profile** — Menampilkan informasi nama dan username pengguna serta fitur logout.
8. **Delivery Address** — Formulir untuk mengisi nama penerima, nomor telepon, dan alamat pengiriman.
9. **Order Confirmation** — Menampilkan ringkasan produk dan informasi penerima sebelum pesanan dikonfirmasi.
10. **Order Success** — Menampilkan pemberitahuan bahwa pesanan berhasil dikonfirmasi.

## Daftar Menu

| No. | Nama Produk | Harga |
|---|---|---:|
| 1 | Kopi Gula Aren | Rp25.000 |
| 2 | Butterscotch Latte | Rp27.000 |
| 3 | Chocolate | Rp22.000 |
| 4 | Matcha Latte | Rp27.000 |
| 5 | Brownie with Ice Cream | Rp30.000 |
| 6 | Croissants | Rp18.000 |

## Teknologi yang Digunakan

- **Kotlin** — Bahasa pemrograman aplikasi.
- **Android Studio** — Integrated Development Environment (IDE).
- **XML Layout** — Membuat tampilan antarmuka aplikasi.
- **RecyclerView** — Menampilkan daftar produk.
- **SharedPreferences** — Menyimpan informasi akun pengguna secara lokal.
- **Intent** — Menghubungkan perpindahan antarhalaman aplikasi.
- **Android SDK** — Platform pengembangan aplikasi Android.

## Cara Menjalankan Aplikasi

1. Download atau clone repository ini.
2. Buka Android Studio.
3. Pilih **Open** dan arahkan ke folder project `kopi-dan-nyemil`.
4. Tunggu proses Gradle Sync hingga selesai.
5. Hubungkan perangkat Android atau jalankan emulator.
6. Klik tombol **Run** untuk menjalankan aplikasi.

## Alur Penggunaan

1. Pengguna membuka aplikasi melalui halaman Welcome.
2. Pengguna memilih Register untuk membuat akun.
3. Setelah akun berhasil dibuat, pengguna melakukan Login.
4. Pengguna masuk ke halaman Home dan memilih produk.
5. Pengguna mengisi informasi penerima dan alamat pengiriman.
6. Pengguna memeriksa detail pesanan pada halaman Order Confirmation.
7. Pengguna menekan tombol Konfirmasi Pesanan.
8. Aplikasi menampilkan halaman Order Success.

## Screenshot Aplikasi

Screenshot setiap halaman aplikasi akan ditambahkan pada bagian ini.

1. Welcome Page
<img width="282" height="546" alt="Screenshot 2026-11-04 195306" src="https://github.com/user-attachments/assets/3a583692-c88f-4654-ac9e-602da42315c9" />
 <img width="280" height="556" alt="Screenshot 2026-11-04 195327" src="https://github.com/user-attachments/assets/daf86934-6d5b-45d1-9c59-341074ad6dc1" />

2. Register Page
<img width="283" height="558" alt="Screenshot 2026-11-04 195343" src="https://github.com/user-attachments/assets/92855fb5-861d-4bd4-8faf-0a5d39413bf1" />

3. Login Page
<img width="276" height="552" alt="Screenshot 2026-11-04 195353" src="https://github.com/user-attachments/assets/3f33c3a2-8dba-4065-93b3-0b9ce5d9e160" />

4. Home Page
<img width="265" height="555" alt="Screenshot 2026-11-04 195445" src="https://github.com/user-attachments/assets/8c7db1c5-ee1e-4a03-b2b2-b2f429351cdf" />
  <img width="261" height="552" alt="Screenshot 2026-11-04 195454" src="https://github.com/user-attachments/assets/74baf387-cc66-49c8-878e-7ec64e45a79d" />

5. Profile Page
<img width="340" height="727" alt="Screenshot 2026-11-05 215052" src="https://github.com/user-attachments/assets/306dbf3e-18e5-4cdc-9cd5-21d4a8706af5" />

6. Delivery Address Page
<img width="280" height="553" alt="Screenshot 2026-11-04 195506" src="https://github.com/user-attachments/assets/14514510-4352-4dc8-927f-50a935155f3d" />

7. Order Confirmation 
<img width="266" height="542" alt="Screenshot 2026-11-04 195529" src="https://github.com/user-attachments/assets/55bf5725-4b8a-487f-8946-344d98e60266" />

8. Order Success Page
<img width="300" height="606" alt="Screenshot 2026-11-05 201515" src="https://github.com/user-attachments/assets/f910c46f-b8f3-48c5-92ce-e19d0ccb911f" />


## Catatan

Aplikasi ini merupakan proyek UTS mata kuliah Pengembangan Aplikasi Mobile. Proses pemesanan masih berupa simulasi dan belum terhubung dengan database, payment gateway, maupun layanan pengiriman secara nyata.

## Pengembang

**Nama:** Ghaniyah Salsabilla

**NIM:** 1247050109

**Proyek:** Kopi dan Nyemil

**Platform:** Android
