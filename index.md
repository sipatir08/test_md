<div align="center">
  <h1>DOKUMEN PERSYARATAN PENGGUNA (URD)</h1>
  <h2>E-LEARNING DARLING (PERUM DAMRI)</h2>
  <hr>
  <i>(DAMRI Academy For Realiable Learning And Innovation Guidance)</i>
</div>

# LEMBAR PENGESAHAN

| Label | Detail |
| :--- | :--- |
| **Kode Formulir** | TOR. 061/PRODID4TI-ULBI/SPm/VIII/2024 <br> TOR. 0022.00/UM.001/BA/00/TI/2024 |
| **Judul Pengembangan** | E-Learning DARLING (Damri Academy For Realiable Learning And Innovation Guidance) <br> untuk meningkatkan kapasitas SDM di Lingkungan Perum DAMRI |
| **Pejabat yang Mengajukan** | Roni Andarsyah, Ketua Maching Fund 2024 |
| **Rencana Implementasi Sistem** | Oktober 2024 (Estimasi Waktu Pengerjaan: 60 hari / 2 bulan) |
| **Luaran Kegiatan** | 1. Perancangan Darling (Lampiran I) <br> 2. Spesifikasi Pekerjaan (Lampiran II) |
| **Tanggal Pengajuan** | Bandung, 14 Agustus 2024 |

---

### Persetujuan Pelaksanaan Proyek

<br>
<div align="left">

**Diajukan Oleh:** &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; **Disetujui Oleh:**
<br>
**Ketua** (Maching Fund 2024) &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; **MITRA** (Perum DAMRI)
<br><br><br><br>
*(Tanda tangan)* &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; *(Tanda tangan)*
<br>
**Dr. Ali Mohamad Rezza, ST., MM** &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; **Noerahman Adi Pratama**
</div>

***

# LAMPIRAN II. USER REQUIREMENT

## Lingkup E-Learning DARLING

| No. | Modul | Lingkup Pekerjaan | Approve by Mitra |
| :---: | :--- | :--- | :---: |
| **1** | **General** | 1. Menggunakan Framework Codelgniter versi 4. <br> 2. Dominan menggunakan bahasa Indonesia sebagai bahasa untuk tampilan web. <br> 3. Menggunakan Database MySQL. <br> 4. Seluruh content gambar pada website disupport oleh DAMRI. <br> 5. Customize Template Dashboard (Dari DAMRI). | V |
| **2** | **Login** | 1. Login menggunakan NIK (database dari DAMRI). <br> 2. Pakai SSO DAMRI (API dari DAMRI). | V |
| **3** | **User Trainee** | 1. Home User menampilkan Navbar (Profil, Notifikasi, Course, Dashboard, Path) (Dinamis). <br> 2. Home User menampilkan Banner images (content damri). <br> 3. Home User menampilkan informasi course yang sedang dikerjakan (course in progress) lengkap dengan durasi course. <br> 4. Pada menu Course dapat melihat course wajib dan opsional (random), course bersifat terbuka siapa saja bisa enroll, melihat hasil course, melihat progress course. <br> 5. Filter berdasarkan kategori (dinamis). <br> 6. Mengerjakan course yang tersedia yaitu pre-test, deskripsi materi/text, menonton video, post-test. <br> 7. Melihat history course pada profil yang pernah diikuti atau yang sedang diikuti. <br> 8. Kegiatan pembelajaran akan dibatasi waktu sesuai dengan assign dari operator. <br> 9. Melihat path yang di assign oleh operator dan mengajukan path course yang diinginkan. <br> 10. Mendownload modul dan sertifikat (standar kelulusan 80, sertifikat bisa di unduh PDF sesuai kode sertifikatnya). | V |
| **4** | **Operator** | 1. Menampilkan menu/navbar dashboard, profil operator. <br> 2. Sidebar terdiri dari (Dashboard, Learning Path, Courses, Berita, Slider, Assignment & Request). <br> 3. Terdapat Logo DAMRI, dan Humberger pada Sidebar. <br> 4. Menampilkan halaman dashboard summary jumlah peserta (sedang berlangsung, selesai, waktu sudah melewati batas dan gagal), jumlah course, jumlah learning path, jumlah cabang. <br> 5. Menampilkan halaman dashboard (Grafik target peserta yang mengambil course berbanding dengan hasil per cabang dan perbulan) tahunan. <br> 6. Menampilkan Assignment & Request pada menu kelola Assignment & Request. <br> 7. Pada menu Assignment mengelola penugasan dan pengajuan (tambah, ubah, hapus, cari, approve, reject). <br> 8. Kelola penugasan dan pengajuan dimasukan dalam 1 halaman. <br> 9. Pada menu course terdapat action (tambah, edit, delete, sub course, set test, draft/publish, set image, set module). <br> 10. Mengelola Learning Path terdapat Action (Tambah, Courses, Draft/Publish, set image, Edit, Delete). <br> 11. Mengelola data Berita terdapat Action (Tambah, Draft/Publish, set image, Edit, Delete). <br> 12. Mengelola data slideshow pada halaman (utama Landing page dan home user) terdapat Action (Tambah, set image, Edit, Delete). | V |
| **5** | **Halaman Landing Page** | 1. Menampilkan Slideshow (Informasi dinamis). <br> 2. Menampilkan informasi summary jumlah course, peserta, dan video. <br> 3. Menampilkan informasi course yang paling diminati (8 teratas, slider dll). <br> 4. Menampilkan informasi berita terkini. | V |
| **6** | **Official** | 1. Dashboard (sama dengan operator). <br> 2. Report (menyesuaikan DAMRI). | V |

***

### Catatan Proyek (Detail Tambahan dari TOR)

* **Estimasi Waktu Pengerjaan:** 60 hari (2 bulan).
* **Kesepakatan:** Dengan ditandatanganinya modul ini, pihak *client* setuju dengan lingkup pekerjaan, dan pengembang setuju mengerjakan modul pada dokumen ini.
* **Biaya Tambahan:** Jika terjadi penambahan modul atau lingkup pekerjaan di kemudian hari, akan ada biaya tambahan yang disesuaikan dengan tingkat kesulitan dan lama pengerjaan.