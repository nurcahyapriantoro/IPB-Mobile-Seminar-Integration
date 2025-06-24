<p align="center">
  <img src="https://upload.wikimedia.org/wikipedia/id/thumb/e/e3/Logo_IPB.png/1200px-Logo_IPB.png" alt="Logo IPB" width="150"/>
</p>

<h1 align="center">Sistem Manajemen Seminar Terpusat - IPB Mobile</h1>

<p align="center">
  Sebuah solusi inovatif untuk mengatasi tantangan dalam penyebaran informasi dan manajemen seminar akademik di Institut Pertanian Bogor, terintegrasi langsung dengan platform IPB Mobile Student.
  <br/><br/>
  <img src="https://img.shields.io/badge/status-Completed-brightgreen?style=for-the-badge" alt="Status Proyek"/>
  <img src="https://img.shields.io/badge/platform-Mobile-blue?style=for-the-badge" alt="Platform"/>
  <img src="https://img.shields.io/badge/license-MIT-lightgrey?style=for-the-badge" alt="Lisensi"/>
</p>

---

##  Daftar Isi
- [Daftar Isi](#-daftar-isi)
- [📝 Tentang Proyek](#-tentang-proyek)
  - [Latar Belakang Masalah](#latar-belakang-masalah)
  - [Solusi yang Ditawarkan](#solusi-yang-ditawarkan)
- [✨ Fitur Utama](#-fitur-utama)
- [🛠️ Teknologi yang Digunakan](#-teknologi-yang-digunakan)
- [🎨 Desain & Arsitektur Sistem](#-desain--arsitektur-sistem)
  - [Diagram Use Case](#diagram-use-case)
  - [Diagram Aktivitas](#diagram-aktivitas)
  - [Model Domain (Class Diagram)](#model-domain-class-diagram)
- [📸 Tampilan Aplikasi](#-tampilan-aplikasi)
- [🚀 Memulai](#-memulai)
- [👥 Tim Pengembang](#-tim-pengembang)
- [🙏 Ucapan Terima Kasih](#-ucapan-terima-kasih)

---

## 📝 Tentang Proyek

Proyek ini bertujuan untuk merancang dan membangun sebuah sistem manajemen seminar yang terpusat dan terintegrasi ke dalam aplikasi **IPB Mobile Student (IPBM)**. Tujuannya adalah untuk meningkatkan relevansi aplikasi bagi mahasiswa tingkat akhir sekaligus menyelesaikan masalah inefisiensi dalam penyebaran informasi seminar di lingkungan Institut Pertanian Bogor.

### Latar Belakang Masalah

Saat ini, proses penyebaran informasi seminar masih sangat konvensional dan tidak terstruktur, seringkali hanya melalui pesan berantai di grup WhatsApp. Hal ini menimbulkan berbagai masalah:

> * **🚫 Informasi Tidak Teratur:** Jadwal dan tautan seminar mudah tenggelam dalam ramainya grup percakapan.
> * **📉 Jangkauan Terbatas:** Informasi hanya tersebar di kalangan tertentu, menyulitkan pemenuhan kuota minimal peserta.
> * **❓ Kurang Transparansi:** Tidak ada platform terpusat untuk mencari seminar berdasarkan minat atau jadwal.
> * **🎓 Risiko Penundaan Kelulusan:** Mahasiswa tingkat akhir berisiko gagal memenuhi syarat seminar, yang dapat menghambat kelulusan.

### Solusi yang Ditawarkan

Dengan mengintegrasikan portal seminar ke dalam IPB Mobile, kami menyediakan sebuah platform tunggal yang efisien dan mudah diakses oleh seluruh mahasiswa.

- **Bagi Mahasiswa Tingkat Akhir:** Memudahkan publikasi seminar untuk menjangkau audiens yang lebih luas dan memastikan kuota peserta terpenuhi.
- **Bagi Mahasiswa Umum:** Menyediakan akses mudah untuk mencari, mendaftar, dan mendapatkan notifikasi seminar yang relevan untuk memenuhi syarat SKPI dan menambah wawasan.
- **Bagi Institusi:** Meningkatkan efisiensi proses akademik, menstandarisasi pelaksanaan seminar, dan memperkuat ekosistem digital IPB.

---

## ✨ Fitur Utama

Sistem ini dirancang dengan fitur-fitur yang melayani kebutuhan setiap aktor (pengguna).

<details>
<summary><b>👨‍🎓 Untuk Mahasiswa Penyelenggara Seminar</b></summary>
  
-   ✅ **Pendaftaran Seminar:** Mengajukan jadwal seminar baru dengan mengisi formulir detail (judul, deskripsi, dosen pembimbing, jadwal) dan mengunggah berkas proposal.
-   ✏️ **Manajemen Seminar:** Melihat status dan daftar seminar yang telah diajukan (Menunggu, Disetujui, Ditolak).
-   ❌ **Pembatalan Seminar:** Fitur untuk membatalkan penyelenggaraan seminar yang telah disetujui jika diperlukan.
-   📊 **Lihat Pendaftar:** Memantau jumlah dan daftar mahasiswa yang akan hadir sebagai audiens.
</details>

<details>
<summary><b>👩‍🏫 Untuk Mahasiswa Audiens</b></summary>

-   🔍 **Pencarian & Filter Lanjutan:** Mencari seminar berdasarkan kata kunci, fakultas, atau departemen untuk menemukan topik yang paling relevan.
-   📅 **Kalender Seminar:** Melihat semua jadwal seminar yang akan datang dalam tampilan kalender yang intuitif.
-   ✍️ **Pendaftaran Partisipasi:** Mendaftar sebagai peserta seminar hanya dengan beberapa kali klik.
-   🔔 **Notifikasi Pengingat:** Sistem notifikasi otomatis untuk mengingatkan seminar yang akan dihadiri.
-   🚫 **Pembatalan Partisipasi:** Membatalkan kehadiran untuk memberikan slot kepada mahasiswa lain.
</details>

<details>
<summary><b>🔒 Untuk Admin / Tenaga Kependidikan</b></summary>
  
-   🛡️ **Verifikasi & Persetujuan:** Meninjau pengajuan seminar dari mahasiswa dan memberikan persetujuan atau penolakan berdasarkan kelengkapan administrasi dan konten.
-   📈 **Dasbor Manajemen:** Memantau semua aktivitas seminar yang terjadi di dalam platform.
-   ⚙️ **Manajemen Data:** Mengelola data master seperti ruangan, jadwal, dan data pendukung lainnya.
</details>

---

## 🛠️ Teknologi yang Digunakan

Proyek ini dirancang menggunakan tumpukan teknologi modern untuk memastikan skalabilitas dan kemudahan pemeliharaan.

* **UI & UX:** Figma
* **Activity Diagram:** Miro
* **Platform:** IPB Mobile (Android & iOS)

---

## 🎨 Desain & Arsitektur Sistem

Analisis dan desain sistem dilakukan secara mendalam untuk memastikan semua kebutuhan fungsional dan non-fungsional terpenuhi.

### Diagram Use Case
Diagram ini menggambarkan interaksi utama antara aktor (Mahasiswa, Dosen, Admin) dengan fitur-fitur sistem seperti Login, Menambahkan Seminar, Menghadiri Seminar, dan Verifikasi.

<p align="center">
  <img src="https://placehold.co/600x400/333/FFFFFF?text=Diagram+Use+Case" alt="Diagram Use Case"/>
  <br/>
  <small><i>Diagram interaksi Aktor dengan Sistem</i></small>
</p>

### Diagram Aktivitas
Diagram ini memvisualisasikan alur kerja (workflow) dari setiap proses utama dalam sistem, mulai dari pendaftaran seminar oleh mahasiswa hingga proses verifikasi oleh admin.

<p align="center">
  <img src="https://placehold.co/600x400/555/FFFFFF?text=Diagram+Aktivitas" alt="Diagram Aktivitas"/>
  <br/>
  <small><i>Contoh alur aktivitas Pendaftaran Seminar</i></small>
</p>

### Model Domain (Class Diagram)
Struktur database dirancang untuk secara efisien menyimpan dan mengelola data terkait User, Dosen, Admin, Seminar, Proposal, dan Ruangan.

<p align="center">
  <img src="https://placehold.co/600x400/444/FFFFFF?text=Class+Diagram" alt="Class Diagram"/>
  <br/>
  <small><i>Struktur dan relasi antar tabel dalam database</i></small>
</p>

---

## 📸 Tampilan Aplikasi

Berikut adalah beberapa contoh tampilan (mockup) dari aplikasi yang dirancang dengan antarmuka yang modern, bersih, dan ramah pengguna.

| Halaman Utama | Detail Seminar | Formulir Pendaftaran |
| :---: | :---: | :---: |
| <img src="https://placehold.co/300x600/f0f8ff/333333?text=Halaman+Utama%0A(Daftar+Seminar)" alt="Halaman Utama"> | <img src="https://placehold.co/300x600/e6e6fa/333333?text=Halaman+Detail%0A(Info+Lengkap+Seminar)" alt="Detail Seminar"> | <img src="https://placehold.co/300x600/fff0f5/333333?text=Formulir+Pendaftaran%0A(Ajukan+Seminar+Baru)" alt="Formulir Pendaftaran"> |

---

## 👥 Tim Pengembang

Proyek ini dikembangkan oleh tim mahasiswa dari Program Studi Ilmu Komputer, Institut Pertanian Bogor.

* **Nabil Hamzah Ash Shiddiq** - `G6401221901`
* **Nurcahya Priantoro** - `G6401221049`
* **Justin Kristaldi Djafar** - `G6401221102`

---

## 🙏 Ucapan Terima Kasih

Kami ingin mengucapkan terima kasih kepada:
* Institut Pertanian Bogor (IPB)
* Dosen Pembimbing dan Tenaga Kependidikan
* Semua pihak yang telah memberikan dukungan selama proses analisis dan desain sistem ini.

