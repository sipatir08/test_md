# LEMBAR PENGESAHAN

## DOKUMEN PERSYARATAN PENGGUNA (URD) E-LEARNING DARLING

| Label | Nilai |
| :--- | :--- |
| **Kode Formulir** | TOR. 061/PRODID4TI-ULBI/SPm/VIII/2024 <br> TOR. 0022.00/UM.001/BA/00/TI/2024 |
| **Judul Pengembangan** | E-Learning DARLING (Damri Academy For Realiable Learning And Innovation Guidance) <br> untuk meningkatkan kapasitas SDM di Lingkungan Perum DAMRI |
| **Pejabat yang Mengajukan** | Roni Andarsyah, Ketua Maching Fund 2024 |
| **Rencana Implementasi Sistem (Waktu)** | Oktober 2024 |
| **Luaran Kegiatan** | 1. Perancangan Darling (Lampiran I) <br> 2. Spesifikasi Pekerjaan (Lampiran II) |
| **Tanggal Pengajuan** | Bandung, 14 Agustus 2024 |

---

### Persetujuan

**Diajukan Oleh:** &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; **Disetujui Oleh:**
<br>
**Ketua** (Maching Fund 2024) &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; **MITRA** (Perum DAMRI)
<br><br><br><br>
*(Tanda tangan)* &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;*(Tanda tangan)*
<br>
**Dr. Ali Mohamad Rezza, ST., MM** &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; **Noerahman Adi Pratama**

***

# LAMPIRAN II. USER REQUIREMENT
## Lingkup E-Learning DARLING (DAMRI Academy For Realiable Learning And Innovation Guidance)
### untuk meningkatkan kapasitas SDM di Lingkungan Perum DAMRI

| No. | Modul | Lingkup Pekerjaan | Approve by Mitra |
| :---: | :--- | :--- | :---: |
| **1** | **General** | 1. Menggunakan Framework Codelgniter versi 4 | V |
| | | 2. Dominan menggunakan bahasa Indonesia sebagai bahasa untuk tampilan web. | V |
| | | 3. Menggunakan Database MySQL | V |
| | | 4. Seluruh content gambar pada website disupport oleh DAMRI | V |
| | | 5. Customize Template Dashboard (Dari DAMRI) | V |
| **2** | **Login** | 1. Login menggunakan NIK (database dari DAMRI) | V |
| | | 2. Pakai SSO DAMRI (API dari DAMRI) | V |
| **3** | **User Trainee** | 1. Home User menampilkan Navbar (Profil, Notifikasi (warning), Course, Dashboard, Path) (Dinamis) | V |
| | | 2. Home User menampilkan Banner images (content damri) | V |
| | | 3. Home User menampilkan informasi course yang sedang dikerjakan (course in progress) lengkap dengan durasi course. | V |
| | | 4. Pada menu Course dapat melihat course wajib dan opsional (random), course bersifat terbuka siapa saja bisa enroll, melihat hasil course, melihat progress course. | V |
| | | 5. Filter berdasarkan kategori (dinamis) | V |
| | | 6. Mengerjakan course yang tersedia yaitu pre-test, deskripsi materi/text, menonton video, post-test. | V |
| | | 7. Melihat history course pada profil yang pernah diikuti atau yang sedang diikuti. | V |
| | | 8. Kegiatan pembelajaran akan dibatasi waktu sesuai dengan assign dari operator, jika tidak sesuai dengan waktu yang ditentukan, maka akan ada info di dashboard user trainee | V |
| | | 9. Melihat path yang di assign oleh operator dan mengajukan path course yang diinginkan | V |
| | | 10. Mendownload modul dan sertifikat sesuai dengan ketersediaan (standar kelulusan 80, sertifikat bisa di unduh PDF sesuai kode sertifikatnya) | V |
| **4** | **Operator** | 1. Menampilkan menu/navbar dashboard, profil operator | V |
| | | 2. Sidebar terdiri dari (Dashboard, Learning Path, Courses, Berita, Slider, Assignment & Request,) | V |
| | | 3. Terdapat Logo DAMRI, dan Humberger pada Sidebar | V |
| | | 4. Menampilkan halaman dashboard summary jumlah peserta (sedang berlangsung, selesai, waktu sudah melewati batas dan gagal), jumlah course, jumlah learning path, jumlah cabang) | V |
| | | 5. Menampilkan halaman dashboard (Grafik target peserta yang mengambil course berbanding dengan hasil per cabang dan perbulan) tahunan | V |
| | | 6. Menampilkan Assignment & Request pada menu kelola Assignment & Request | V |
| | | 7. Pada menu Assignment mengelola penugasan dan pengajuan (tambah, ubah, hapus, cari, approve, reject) | V |
| | | 8. Kelola penugasan dan pengajuan dimasukan dalam 1 halaman | V |
| | | 9. Pada menu course terdapat action (tambah, edit, delete, sub course, set test, draft/publish, set image, set module) | V |
| | | 10. Mengelola Learning Path terdapat Action (Tambah, Courses, Draft/Publish, set image, Edit, Delete) | V |
| | | 11. Mengelola data Berita terdapat Action (Tambah, Draft/Publish, set image, Edit, Delete) | V |
| | | 12. Mengelola data slideshow pada halaman (utama Landing page dan home user) terdapat Action (Tambah, set image, Edit, Delete) | V |
| **5** | **Halaman Landing Page** | 1. Menampilkan Slideshow (Informasi dinamis) | V |
| | | 2. Menampilkan informasi summary jumlah course, peserta, dan video. | V |
| | | 3. Menampilkan informasi course yang paling diminati dengan jumlah 8 teratas (slider dll) judul terpisah diatas slider. | V |
| | | 4. Menampilkan informasi berita terkini. | V |
| **6** | **Official** | 1. Dashboard (sama dengan operator) | V |
| | | 2. Report (menyesuaikan DAMRI) | V |

***

**Detail Tambahan dari Dokumen TOR:**

* **Estimasi Waktu Pengerjaan:** 60 hari (2 bulan).
* **Kesepakatan:** Dengan menandatangani semua modul ini, berarti pihak *client* setuju dengan lingkup pekerjaan tersebut dan pihak pengembang setuju akan mengerjakan modul pada dokumen ini.
* **Biaya Tambahan:** Jika di kemudian hari terjadi penambahan modul atau lingkup pekerjaan, maka akan ada biaya tambahan yang disesuaikan dengan tingkat kesulitan dan lama pengerjaan.