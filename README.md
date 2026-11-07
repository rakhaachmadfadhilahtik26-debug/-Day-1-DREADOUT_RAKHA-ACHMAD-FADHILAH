# -Day-1-DREADOUT_RAKHA-ACHMAD-FADHILAH

## Informasi Peserta
* **Nama Lengkap:** Rakha Achmad Fadhilah
* **Program/Instansi:** D4 Rekayasa Keamanan Siber, Politeknik Negeri Jakarta

## Deskripsi Singkat Repository
Repository ini berisi dokumentasi kegiatan, catatan ringkas, serta hasil praktik dari workshop hari pertama yang berfokus pada pemanfaatan kecerdasan buatan (*Artificial Intelligence*) melalui teknik *prompt engineering* serta pengelolaan manajemen versi kode menggunakan Git dan kolaborasi via GitHub

## Tujuan dan Kegunaan Repository
* Memenuhi penugasan dan pengumpulan tugas Day-1 workshop
* Mendokumentasikan materi, rangkuman, serta langkah-langkah praktikum *Building with AI* dan *Managing Change with GitHub*
* Menyediakan catatan referensi terstruktur mengenai perintah dasar Git, konfigurasi lingkungan pengembangan, hingga pembuatan aplikasi web sederhana (*Student Task Planner*)

---

## Dokumentasi Kegiatan Workshop
Workshop ini dibawakan oleh **Nugi Farhan** (Senior Product Designer) dengan topik utama **"Building with AI, Managing Change with GitHub"**

### 1. Materi dan Topik yang Disampaikan
* **Pengantar AI & Prompt Engineering:** Cara merancang instruksi atau *prompt* yang spesifik agar model AI memberikan jawaban yang tepat, relevan, dan terstruktur. Struktur prompt yang baik mencakup komponen **Role, Task, Context, dan Format**
* **Pengenalan Git & GitHub:** Memahami perbedaan mendasar antara sistem *version control* lokal (Git) dan platform penyimpanan online berbasis web untuk kolaborasi tim (GitHub)
* **Git Workflow & Essential Commands:** Memahami alur kerja Git mulai dari *Working Directory*, *Staging Area*, hingga *.git directory (Repository)*, serta perintah esensial seperti `git init`, `git add`, `git commit`, `git push`, dan `git pull`
* **Konfigurasi Lingkungan (Setup):** Panduan instalasi dan konfigurasi Git, VS Code, serta pembuatan dan penambahan kunci SSH (*SSH Key*) untuk autentikasi yang aman ke GitHub
* **Studi Kasus Praktik:** Membangun aplikasi web sederhana berupa **Student Task Planner** dengan bantuan platform AI dan menerapkannya ke dalam *version control* Git dan GitHub

* ### 1.1 Poin-Poin Penting & Pengetahuan Baru
- **Prompt Engineering:** Pentingnya memberikan *context* dan *role* yang tepat agar AI menghasilkan output yang sesuai kebutuhan.
- **Git vs GitHub:** Memahami bahwa Git adalah sistem *version control* lokal, sedangkan GitHub adalah platform berbasis cloud untuk kolaborasi.
- **SSH Key:** Penggunaan SSH Key jauh lebih aman dan efisien untuk autentikasi ke GitHub dibandingkan password biasa.

### 1.2 Pendapat Pribadi tentang Day 1 Proyek Workshop
Sesi Day 1 Proyek Workshop ini sangat interaktif dan memberikan wawasan praktis yang sangat relevan. Kombinasi antara pemanfaatan AI untuk mempercepat pembuatan project (*Student Task Planner*) dan penggunaan Git/GitHub untuk manajemen kode memberikan pemahaman dasar yang kuat untuk kolaborasi pengembangan perangkat lunak ke depannya.

### 2. Catatan dan Rangkuman Materi
* **Prompt Engineering:**
  * *Prompt* adalah instruksi atau masukan yang diberikan kepada model AI untuk mendapatkan hasil tertentu
  * Keuntungan *prompt engineering* meliputi meningkatkan performa model AI, mengurangi bias/respons *offensive*, meningkatkan kontrol dan prediktabilitas, serta memberikan pengalaman pengguna yang lebih baik
  * Struktur prompt yang ideal terdiri atas *Role* (peran AI), *Task* (tugas utama), *Context* (latar belakang/batasan), dan *Format* luaran yang diinginkan
* **Git dan GitHub:**
  * **Git:** Sistem *version control* terdistribusi (DVCS) ciptaan Linus Torvalds tahun 2005 yang melacak siapa, kapan, dan perubahan apa saja pada file
  * **GitHub:** Platform berbasis web untuk menyimpan *repository* Git secara online dan mendukung kolaborasi
  * **Alur Kerja Git (*Git Workflow*):**
    1. *Working Directory*: Salinan proyek yang sedang dikerjakan di komputer
    2. *Staging Area (Index)*: Area penyimpanan sementara untuk mencatat perubahan yang akan dimasukkan ke *commit* berikutnya
    3. *.git Directory (Repository)*: Tempat penyimpanan metadata dan *database* objek proyek
* **Perintah Penting Git:**
  * `git init`: Memulai *repository* baru.
  * `git add .` / `git add -A`: Memindahkan perubahan file ke *staging area*.
  * `git commit -m "message"`: Menyimpan perubahan ke *repository* lokal dengan pesan deskriptif.
  * `git remote add <name> <url>` & `git push origin main`: Menghubungkan dan mengunggah cabang kode ke *remote repository* GitHub.
  * `git pull origin main`: Mengambil dan menggabungkan pembaruan dari *remote* ke cabang lokal.

### 3. Poin-Poin Penting dan Pengetahuan Baru
* Pentingnya memberikan konteks yang kaya (*Context is key*) pada AI agar hasil keluaran jauh lebih spesifik, akurat, dan sesuai kebutuhan pengguna.
* Penerapan keamanan menggunakan kunci kriptografi **Ed25519** untuk koneksi SSH yang aman antara perangkat lokal dan GitHub.
* Pemahaman langkah-langkah praktis mulai dari merancang aplikasi web *Student Task Planner* menggunakan bantuan AI, inisialisasi Git, hingga melakukan *commit* dan *push* secara berkala ke GitHub.

