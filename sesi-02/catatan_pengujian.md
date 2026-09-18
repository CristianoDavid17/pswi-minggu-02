Pemeriksaan melalui devtools :

1. Bahasa dokumen html mempunyai lang=id "LULUS"
2. Judul halaman title tampil pada tab browser "LULUS"
3. Hierarki heading h1, h2, dan h3 berurutan logis "LULUS"
4. Landmark header, nav, main, aside, footer ditemukan "LULUS"
5. Navigasi Tautan menuju id yang tersedia "LULUS"

Validasi menggunakan https://validator.w3.org/nu/ :
1. Terdapat error dibagai </body> dan <aside> dimana perintah </body> duluan saya buat sebelum perintah <aside> sehingga struktur perintah tidak sesuai dimana </body> seharusnya berada diakhir untuk menutup perintah di dalam halaman website



Haail Eksperimen :
1. GEJALA, Tidak terjadi apa-apa
BUKTI, halaman masig bisa di buka dan normal
PENYEBAP, tagar artikel dihapus
PERBAIKAN, menambahkan kembali tagar penutup artikel
HASIL, halaman masih normal seperti biasa

2. GEJALA, tautan tidak dapat bergerak
BUKTI, web tidak memuat kegiatan
PENYEBAP,karena id section diganti
PERBAIKAN, menambahkan lagi tanda kutip (") di id section yang di uji coba tadi
HASIL, halaman web kembali normal seperti  biasa

3. GEJALA, tidak ada terjadi apa-apa di struktur hierarki DOM(normal seperti biasanya)
BUKTI, masih menampilkan hierarki yang sama sejak awal sebelum dirubah
PENYEBAP, DOM mendeteksi h2 saja
PERBAIKAN, kembali memuat h3 ke program
HASIL, web tetap normal seperti biasa
4. GEJALA, struktur web rusak karena main dimasukkan kedalam header/judul
BUKTI, Ketika di cek di validator terjadi banyak error dalam program
PENYEBAP, main tidak bisa berada di header, main berisi halaman web yang akan di isi sedangkan header merupakan judul yang akan dibuat
PERBAIKAN, kembali meletakkan main ke bawah header
HASIL, error di validasi hilang dan kembali normal