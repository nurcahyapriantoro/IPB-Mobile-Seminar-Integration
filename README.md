<p align="center">
  <img src="https://raw.githubusercontent.com/nurcahyapriantoro/IPB-Mobile-Seminar-Integration/main/Assets/Logo-IPB-University-Horizontal.png" alt="Logo IPB" width="500"/>
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
- [🛠️ Alat dan Teknologi](#-alat-dan-teknologi)
- [🎨 Desain & Arsitektur Sistem](#-desain--arsitektur-sistem)
  - [Diagram Use Case](#diagram-use-case)
  - [Diagram Aktivitas](#diagram-aktivitas)
  - [Diagram Sequence](#diagram-sequence)
  - [Diagram Class](#diagram-class)
- [📸 Tampilan Aplikasi (Mockup)](#-tampilan-aplikasi-mockup)
- [🔗 Tautan Penting](#-tautan-penting)
- [👥 Tim Pengembang](#-tim-pengembang)
- [🙏 Ucapan Terima Kasih](#-ucapan-terima-kasih)

---

## 📝 Tentang Proyek

[cite_start]Proyek ini bertujuan untuk merancang dan membangun sebuah sistem manajemen seminar yang terpusat dan terintegrasi ke dalam aplikasi **IPB Mobile Student (IPBM)**. [cite_start]Tujuannya adalah untuk meningkatkan relevansi aplikasi bagi mahasiswa tingkat akhir sekaligus menyelesaikan masalah inefisiensi dalam penyebaran informasi seminar di lingkungan Institut Pertanian Bogor.

### Latar Belakang Masalah

[cite_start]Saat ini, proses penyebaran informasi seminar masih sangat konvensional dan tidak terstruktur, seringkali hanya melalui pesan berantai di grup WhatsApp. Hal ini menimbulkan berbagai masalah:

> [cite_start]* **🚫 Informasi Tidak Teratur:** Jadwal dan tautan seminar mudah tenggelam dalam ramainya grup percakapan.
> * **📉 Jangkauan Terbatas:** Informasi hanya tersebar di kalangan tertentu, menyulitkan pemenuhan kuota minimal peserta.
> [cite_start]* **❓ Kurang Transparansi:** Tidak ada platform terpusat untuk mencari seminar berdasarkan minat atau jadwal.
> [cite_start]* **🎓 Risiko Penundaan Kelulusan:** Mahasiswa tingkat akhir berisiko gagal memenuhi syarat seminar, yang dapat menghambat kelulusan.

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
-   ❌ **Pembatalan Seminar:** Fitur untuk membatalkan penyelenggaraan seminar yang telah diajukan atau disetujui.
-   📊 **Lihat Pendaftar:** Memantau jumlah dan daftar mahasiswa yang akan hadir sebagai audiens.
</details>

<details>
<summary><b>👩‍🏫 Untuk Mahasiswa Audiens</b></summary>

-   🔍 **Pencarian & Filter Lanjutan:** Mencari seminar berdasarkan kata kunci, fakultas, atau departemen untuk menemukan topik yang paling relevan.
-   ✍️ **Pendaftaran Partisipasi:** Mendaftar sebagai peserta seminar hanya dengan beberapa kali klik.
-   🔔 **Notifikasi Pengingat:** Sistem notifikasi otomatis untuk mengingatkan seminar yang akan dihadiri.
-   🚫 **Pembatalan Partisipasi:** Membatalkan kehadiran untuk memberikan slot kepada mahasiswa lain.
</details>

<details>
<summary><b>🔒 Untuk Admin / Tenaga Kependidikan</b></summary>
  
-   🛡️ **Verifikasi & Persetujuan:** Meninjau pengajuan seminar dari mahasiswa dan memberikan persetujuan atau penolakan berdasarkan kelengkapan administrasi dan konten.
-   📈 **Dasbor Manajemen:** Memantau semua aktivitas seminar yang terjadi di dalam platform.
</details>

---

## 🛠️ Alat dan Teknologi

Proyek ini dirancang menggunakan alat modern untuk proses analisis dan desain, serta teknologi pengembangan web yang umum digunakan.
* [cite_start]**Desain UI/UX & Prototipe:** Figma 
* [cite_start]**Diagram Alur & Kolaborasi:** Miro 
* [cite_start]**Backend Framework:** Laravel 
* [cite_start]**Frontend Framework:** Bootstrap 
* [cite_start]**Platform Target:** IPB Mobile (Android & iOS) 

---

## 🎨 Desain & Arsitektur Sistem

Analisis dan desain sistem dilakukan secara mendalam untuk memastikan semua kebutuhan fungsional dan non-fungsional terpenuhi.

### Diagram Use Case
[cite_start]Diagram ini menggambarkan interaksi utama antara aktor (Mahasiswa, Dosen, Admin) dengan fitur-fitur sistem.

<p align="center">
  <img src="https://raw.githubusercontent.com/nurcahyapriantoro/IPB-Mobile-Seminar-Integration/main/Assets/Use%20Case%20Diagram.png" alt="Diagram Use Case" width="700"/>
  <br/>
  <small><i>Diagram interaksi Aktor dengan Sistem</i></small>
</p>

### Diagram Aktivitas
[cite_start]Diagram ini memvisualisasikan alur kerja (workflow) dari setiap proses utama dalam sistem.

<details>
<summary><b>Lihat Diagram Aktivitas Selengkapnya</b></summary>

| [cite_start]User Login  | [cite_start]Menambahkan List Seminar  | [cite_start]Mencari & Mendaftar Seminar  |
| :---: | :---: | :---: |
| <img src="https://raw.githubusercontent.com/nurcahyapriantoro/IPB-Mobile-Seminar-Integration/main/Assets/Activity%20Diagram%201.png" alt="Activity Diagram 1" width="300"> | <img src="https://raw.githubusercontent.com/nurcahyapriantoro/IPB-Mobile-Seminar-Integration/main/Assets/Activity%20Diagram%202.png" alt="Activity Diagram 2" width="300"> | <img src="https://raw.githubusercontent.com/nurcahyapriantoro/IPB-Mobile-Seminar-Integration/main/Assets/Activity%20Diagram%203.png" alt="Activity Diagram 3" width="300"> |

</details>

### Diagram Sequence
Diagram ini menunjukkan urutan interaksi antar objek dalam sistem untuk skenario tertentu.
<p align="center">
  <img src="https://raw.githubusercontent.com/nurcahyapriantoro/IPB-Mobile-Seminar-Integration/main/Assets/Sequence%20Diagram.png" alt="Sequence Diagram" width="700"/>
  <br/>
  <small><i>Contoh alur sequence diagram</i></small>
</p>

### Diagram Class
[cite_start]Struktur data dirancang untuk secara efisien menyimpan dan mengelola data terkait pengguna, seminar, dan entitas lainnya.
<p align="center">
  <img src="https://raw.githubusercontent.com/nurcahyapriantoro/IPB-Mobile-Seminar-Integration/main/Assets/Class%20Diagram.png" alt="Class Diagram" width="800"/>
  <br/>
  <small><i>Struktur dan relasi antar entitas dalam sistem</i></small>
</p>

---

## 📸 Tampilan Aplikasi (Mockup)

Berikut adalah beberapa mockup fitur utama yang dirancang di Figma.

| Menambahkan Seminar | Mengikuti Seminar | Cancel Partisipasi |
|:---:|:---:|:---:|
| <img src="https://raw.githubusercontent.com/nurcahyapriantoro/IPB-Mobile-Seminar-Integration/main/Assets/Menambahkan%20List%20Seminar%20(Mahasiswa%20Tingkat%20Akhir).png" alt="Menambahkan List Seminar" width="250"> | <img src="https://raw.githubusercontent.com/nurcahyapriantoro/IPB-Mobile-Seminar-Integration/main/Assets/Mengikuti%20Seminar%20(Mahasiswa%20Audiens).png" alt="Mengikuti Seminar" width="250"> | <img src="https://raw.githubusercontent.com/nurcahyapriantoro/IPB-Mobile-Seminar-Integration/main/Assets/Cancel%20Partisipasi%20Seminar%20(Mahasiswa%20Audiens).png" alt="Cancel Partisipasi" width="250"> |
| **Fitur Filter** | **Fitur Search Bar** | **Cancel Penyelenggaraan** |
| <img src="https://raw.githubusercontent.com/nurcahyapriantoro/IPB-Mobile-Seminar-Integration/main/Assets/Fitur%20Filter%20berdasarkan%20Fakultas%20(%E2%80%9CFEM%E2%80%9D)%20%26%20Jurusan%20(%E2%80%9CManajemen%E2%80%9D).png" alt="Fitur Filter" width="250"> | <img src="https://raw.githubusercontent.com/nurcahyapriantoro/IPB-Mobile-Seminar-Integration/main/Assets/Fitur%20Search%20Bar%20(Studi%20Kasus%20mencari%20Fakultas%20%E2%80%9Cfem%E2%80%9D).png" alt="Fitur Search" width="250"> | <img src="https://raw.githubusercontent.com/nurcahyapriantoro/IPB-Mobile-Seminar-Integration/main/Assets/Cancel%20Penyelenggaraan%20Seminar%20(Mahasiswa%20Tingkat%20Akhir).png" alt="Cancel Penyelenggaraan" width="250"> |

---

## 🔗 Tautan Penting

[cite_start]Akses aset dan dokumentasi pelengkap proyek melalui tautan berikut.

<p align="center">
  <a href="https://www.figma.com/proto/ah9jTxc2B0wr3miOVQiBTT/ADS?node-id=41-225&p=f&t=FTPAtG1OasRMqlgH-1&scaling=min-zoom&content-scaling=fixed&page-id=4%3A40506&starting-point-node-id=41%3A225&show-proto-sidebar=1">
    <img src="https://img.shields.io/badge/Figma-Prototype-F24E1E?style=for-the-badge&logo=figma&logoColor=white" alt="Figma Prototype"/>
  </a>
  <a href="https://www.canva.com/design/DAGqhW1Vipc/rCIG-A35lcvJr9iTnomDJw/edit?utm_content=DAGqhW1Vipc&utm_campaign=designshare&utm_medium=link2&utm_source=sharebutton">
    <img src="https://img.shields.io/badge/Canva-Presentasi-00C4CC?style=for-the-badge&logo=canva&logoColor=white" alt="Canva Presentation"/>
  </a>
  <a href="https://miro.com/app/board/uXjVIcA63gc=/?share_link_id=503088974360">
    <img src="https://img.shields.io/badge/Miro-Board-FFCA28?style=for-the-badge&logo=miro&logoColor=black" alt="Miro Board"/>
  </a>
</p>

---

## 👥 Tim Pengembang

[cite_start]Proyek ini dikembangkan oleh tim mahasiswa dari Program Studi Ilmu Komputer, Institut Pertanian Bogor.

* [cite_start]**Nurcahya Priantoro** - `G6401221049` 
* [cite_start]**Nabil Hamzah Ash Shiddiq** - `G6401221901` 
* [cite_start]**Justin Kristaldi Djafar** - `G6401221102` 

---

## 🙏 Ucapan Terima Kasih

Kami ingin mengucapkan terima kasih kepada:
* Institut Pertanian Bogor (IPB)
* Dosen Pembimbing dan Tenaga Kependidikan
* Semua pihak yang telah memberikan dukungan selama proses analisis dan desain sistem ini.
