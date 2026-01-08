# Moodiary - Mood Tracker App

**Moodiary** adalah aplikasi pelacak suasana hati (Mood Tracker) berbasis mobile yang dirancang untuk membantu pengguna memantau kondisi emosional mereka secara berkala. Aplikasi ini berfungsi sebagai alat dokumentasi digital (journaling) untuk mengenali pola perubahan suasana hati melalui fitur pengumpulan data (*collection*) dan visualisasi riwayat (*reflection*).

## 🚀 Fitur Utama & Storyboard

Alur kerja aplikasi ini dirancang secara sistematis untuk memberikan pengalaman pengguna yang intuitif:

1. **Identitas Visual (Logo)**
* Menampilkan identitas utama aplikasi sebagai sistem pelacak mood yang ramah dan interaktif.


2. **Splash Screen**
* Saat aplikasi dibuka, sistem melakukan inisialisasi data dan menampilkan *splash screen* yang memuat logo aplikasi.

* **Fitur Lanjutan:** Pada tahap ini, aplikasi mendeteksi lokasi pengguna secara otomatis untuk menyesuaikan bahasa (lokalisasi).

3. **Halaman Sapaan (Greeting Page)**
* Setelah pemuatan selesai, pengguna disambut dengan halaman sapaan personal (misalnya: "Halo, User!") untuk membangun interaksi positif.

4. **Tambah Mood (Input Data)**
* Pengguna dapat memilih emoji yang mewakili perasaan mereka saat itu, seperti **Senang, Sedih, Marah, atau Netral**.

* Tersedia logika konfirmasi: pengguna dapat memilih untuk **Simpan** (data masuk ke database) atau **Tidak** (kembali ke menu utama tanpa menyimpan).


5. **Dashboard & History**
* Menampilkan ringkasan mood terakhir yang disimpan dan riwayat mingguan dalam bentuk kalender kecil.

* Dilengkapi dengan fitur manajemen data CRUD (*Create, Read, Update, Delete*).

---

## 🛠️ Detail Teknis

* **Platform:** Android Studio (Mobile)

**Bahasa Pemrograman:** Java/Kotlin (Mobile) & PHP Native (Web Version) 

**Database:** MySQL (Versi Web) & Migrasi ke Firebase/SQLite (Versi Mobile) 


* **Notifikasi:** Firebase Cloud Messaging (FCM)


**Metodologi Pengembangan:** *Agile Unified Process* (AUP) yang terdiri dari fase *Inception, Elaboration, Construction,* dan *Transition*.



---

## 📊 Diagram Pemodelan Sistem

Pengembangan aplikasi ini didasarkan pada perancangan perangkat lunak yang matang:
 
**Flowchart:** Menggambarkan logika prosedural dari *start* hingga *end*.

**Use Case Diagram:** Memetakan interaksi aktor (User) dengan fungsionalitas sistem.

**Activity Diagram:** Menjelaskan urutan aktivitas dalam dua *swimlanes* (User & System).

**Class Diagram:** Mendefinisikan struktur kelas seperti `User`, `Mood_Record`, `System_Controller`, dan `Dashboard`.



---
