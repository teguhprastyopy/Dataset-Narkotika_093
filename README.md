Selamat datang di repositori "Dataset-Narkotika" yang telah saya susun. Saya adalah Muhammad Teguh Prastyo, seorang mahasiswa dari Universitas Muhammadiyah Malang dengan nomor induk mahasiswa (NIM) 202010370311093. Repositori ini merupakan bagian dari tugas yang diberikan oleh Pak Galih, yang dikenal sebagai "Tugas Dataset Putusan Pidana Khusus," yang terkait dengan pengadilan negeri Palangka Raya.

Dalam repositori ini, terdapat dua folder utama, yaitu "/Dataset" dan "Overview," yang berisi informasi penting terkait dengan putusan-putusan khusus dalam kasus Narkotika di pengadilan negeri tersebut.

# Folder "/Dataset":
Di dalam folder "/Dataset," terdapat sekitar 44 file PDF yang berisi putusan-putusan khusus dari pengadilan negeri Palangka Raya dalam kasus Narkotika. Namun, perlu diperhatikan bahwa tidak semua tautan yang digunakan untuk mengumpulkan data dapat diunduh secara lengkap, karena beberapa tautan tersebut tidak menyediakan opsi unduhan.

# Folder "/Overview":
Di dalam folder "/Overview," terdapat sebuah file Excel yang berisi 44 data terkait dengan putusan-putusan pengadilan tersebut. Data-data ini mencakup informasi umum dari setiap putusan, yang terdiri dari empat kolom:

- No Putusan: Nomor identifikasi unik untuk setiap putusan.
- Lembaga Peradilan: Nama pengadilan yang menangani kasus tersebut.
- Barang Bukti: Jenis barang bukti yang terkait dengan kasus Narkotika.
- Amar Putusan: Ringkasan isi putusan pengadilan.

Penting untuk diingat bahwa proses penginputan data ke dalam file Excel dilakukan secara manual. Hal ini disebabkan oleh kompleksitas struktur PDF yang ditemukan, yang membuat tidak semua PDF dapat diekstraksi teksnya secara otomatis. Namun, informasi tersebut telah disusun dengan cermat untuk memastikan keakuratan dan kebergunaannya dalam tugas "Tugas Dataset Putusan Pidana Khusus" ini.

Selain folder, dalam repositori ini terdapat dua file penting, yaitu "SCRAPPING_PN_PALANGKARAYA_093.ipynb" dan "pn_palangkaraya.csv."

# File "SCRAPPING_PN_PALANGKARAYA_093.ipynb":
File ini digunakan untuk melakukan proses pengambilan data putusan pengadilan terkait dan menyimpannya dalam bentuk DataFrame (tabel) dengan menggunakan modul-modul seperti requests, BeautifulSoup, dan pandas. Berikut adalah penjelasan langkah-langkah dari kode yang terdapat dalam file ini:

1. Import Modul: Dalam bagian ini, modul-modul yang diperlukan, seperti requests, BeautifulSoup, dan pandas, diimpor agar dapat digunakan dalam pengambilan dan pengolahan data.
2. Mendefinisikan URL: URL dari halaman web yang berisi data putusan pengadilan ditentukan di sini.
3. Mengambil Halaman Web: Dengan menggunakan modul requests, halaman web diambil untuk proses selanjutnya.
4. Parsing Halaman Web: Halaman web yang telah diunduh diproses dan diurai menggunakan modul BeautifulSoup.
5. Mencari Tabel HTML: Dalam bagian ini, kode mencari elemen-elemen tabel dalam halaman web yang akan digunakan untuk ekstraksi data.
6. Mendapatkan Data Kolom Tabel: Data judul kolom tabel ditemukan dan disimpan.
7. Membuat DataFrame: Sebuah DataFrame kosong dibuat dengan menggunakan judul kolom yang telah ditemukan sebelumnya.
8. Mengambil Data Baris Tabel: Data dari baris-baris tabel diambil dan dimasukkan ke dalam DataFrame sesuai dengan kolom yang sesuai.
9. Memproses dan Menyimpan Data: Kolom-kolom yang kosong dihapus, dan data akhir disimpan dalam bentuk file CSV dengan nama "pn_palangkaraya.csv."

Semua langkah tersebut dirancang untuk mengambil data dari sejumlah URL yang telah ditentukan, menggabungkannya menjadi satu DataFrame, dan menyimpannya dalam format file CSV dengan nama "pn_palangkaraya.csv."

Semoga penjelasan ini membantu Anda memahami lebih baik tentang repositori "Dataset-Narkotika" dan proses pengambilan dan penyimpanan datanya. Jika ada pertanyaan lebih lanjut atau permintaan informasi tambahan, jangan ragu untuk menghubungi saya.
