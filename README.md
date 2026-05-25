# UTS Jaringan Nirkabel

## Informasi Individu
- Nama : ........................................
- NIM : ........................................

## Mata Kuliah
UTS Jaringan Nirkabel

## Ketentuan Pengerjaan
- Jenis Pengerjaan : Individu
- Tenggat Waktu : 27 Mei 2026 Pukul 23:59 WIB
- Pengumpulan via E-Mail rizky_ekamaulana@udb.ac.id

--------------------------------------------------

# Konfigurasi Point to Point Wireless

## 1. Topologi Jaringan
Koneksi dilakukan menggunakan metode Point to Point antara:
- 1 Access Point
- 1 Station

Topologi:
[Access Point] ))) ~~~ ((( [Station]

Nilai:
- Berhasil : 30 Point
- Gagal : 0 Point

--------------------------------------------------

# Konfigurasi Wireless

## 2. SSID
Format:
remediasi[NIM]_UTS

Contoh:
remediasi20101010_UTS

Ketentuan Penilaian:
- Sesuai ketentuan : 10 Point
- Salah nama / tidak sesuai format : Potong 50%
  (Nilai menjadi 5 Point)

--------------------------------------------------

## 3. Password SSID
Password:
RemediasiUTS2026!#

Ketentuan Penilaian:
- Sesuai ketentuan : 10 Point
- Salah password / tidak sesuai : Potong 50%
  (Nilai menjadi 5 Point)

--------------------------------------------------

## 4. Tipe Enkripsi
- Security Mode : WPA2-PSK
- Encryption :
  - AES
  - TKIP

Ketentuan Penilaian:
- Sesuai ketentuan : 10 Point
- Salah tipe enkripsi : Potong 50%
  (Nilai menjadi 5 Point)

--------------------------------------------------

## 5. Broadcast SSID
Status:
OFF / Disable

SSID tidak boleh ditampilkan secara publik.

Ketentuan Penilaian:
- Broadcast OFF : 10 Point
- Broadcast ON / salah mode : Potong 50%
  (Nilai menjadi 5 Point)

--------------------------------------------------

## 6. Konfigurasi IP Address

Network:
192.168.251.0/24

Contoh konfigurasi:
- Access Point : 192.168.251.1
- Station      : 192.168.251.2

Subnet Mask:
255.255.255.0

Ketentuan Penilaian:
- IP sesuai ketentuan : 10 Point
- Salah IP : 0 Point

--------------------------------------------------

# Langkah Pengerjaan

## Konfigurasi Access Point
1. Login ke perangkat Access Point
2. Masuk ke menu Wireless
3. Set mode menjadi Access Point
4. Buat SSID sesuai ketentuan
5. Nonaktifkan Broadcast SSID
6. Set keamanan WPA2-PSK
7. Masukkan password sesuai ketentuan
8. Set IP Address
9. Simpan konfigurasi

--------------------------------------------------

## Konfigurasi Station
1. Login ke perangkat Station
2. Scan atau tambahkan SSID secara manual
3. Masukkan password
4. Hubungkan ke Access Point
5. Set IP Address sesuai network
6. Lakukan pengujian koneksi

--------------------------------------------------

# Pengujian Koneksi

## Ping Test
Contoh:
ping 192.168.251.1

atau

ping 192.168.251.2

Jika reply berhasil diterima maka koneksi Point to Point berhasil.

--------------------------------------------------

# Dokumentasi

## Screenshot Konfigurasi
Tambahkan screenshot berikut:
- Konfigurasi Access Point
- Konfigurasi Station
- Hasil koneksi wireless
- Hasil ping test

Ketentuan Penilaian:
- Membuat laporan : 10 Point
- Tidak membuat laporan : 0 Point
- Laporan jelek tetap mendapat nilai

--------------------------------------------------

# Video Presentasi

Buat video presentasi yang menjelaskan:
1. Topologi jaringan
2. Konfigurasi perangkat
3. Pengaturan wireless
4. Pengujian koneksi
5. Kesimpulan hasil praktikum
6. Durasi video maksimal 3 menit
7. File video maksimal 1GB

Ketentuan Penilaian:
- Membuat video presentasi : 10 Point
- Tidak membuat video : 0 Point

--------------------------------------------------

# Rekap Penilaian

| No | Kriteria | Nilai Maksimal | Potongan |
|----|-----------|----------------|-----------|
| 1 | Koneksi Point to Point berhasil | 30 | Gagal = 0 |
| 2 | Nama SSID sesuai ketentuan | 10 | Salah format = -50% |
| 3 | Password sesuai ketentuan | 10 | Salah password = -50% |
| 4 | Tipe enkripsi sesuai | 10 | Salah tipe = -50% |
| 5 | Broadcast SSID OFF | 10 | Salah mode = -50% |
| 6 | Konfigurasi IP sesuai | 10 | Salah IP = 0 |
| 7 | Membuat laporan | 10 | Tidak membuat = 0 |
| 8 | Membuat video presentasi | 10 | Tidak membuat = 0 |

--------------------------------------------------

# Catatan
- Pastikan semua konfigurasi sesuai ketentuan.
- Kesalahan kecil pada konfigurasi wireless tetap mempengaruhi nilai.
- Pastikan koneksi Point to Point dapat berjalan dengan baik sebelum presentasi.
- Upload laporan dan dokumentasi ke E-Mail rizky_ekamaulana@udb.ac.id .

--------------------------------------------------
