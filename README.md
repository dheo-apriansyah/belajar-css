# catatan belajar-css
Belajar css agar bisa jadi frondEnd


inline
- tidak bisa atur width dan height

block
- bisa atur size
- tapi turun ke baris baru

inline-block
- element tetap sebaris (tidak turun)
- bisa di atur width dan height

display grid
- buat baris kolam otomatis

grid-template-columns
- untuk menentukan jumlah kolom dalam grid

repeat(..)
- ulangi kolom berkali-kali

auto-fit
- buat kolom sebanyak mungkin sesuai lebar layar
- kalau layar besar -> kolomnya banyak
- kalau layar kecil -> kolomnya berkurang otomatis
- kolomg kosong di hilangkan

min-max(150px, 1fr)
- lebar minimun kolom = 150px
- lebar maximum = 1fr

1fr(bagian ruang kosong)
- jika ada kotak 900px maka di bagi 3(1fr)
- ambil 1 bagian dari sisa ruang yang tersedia
- kalau ada 2 atau lebih semua dapat bagian yang sama
- fr otomatis menyusaikan ukuran layar
- responsive secara natural