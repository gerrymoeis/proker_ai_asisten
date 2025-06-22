# Workspace Dokumentasi dan Perencanaan Acara Himafortic

Selamat datang di Workspace Dokumentasi dan Perencanaan Acara Himafortic. Repositori ini dirancang sebagai **toolkit komprehensif** untuk membantu panitia dan AI Assistant dalam mengelola seluruh siklus hidup acara, mulai dari ide hingga laporan pertanggungjawaban.

## 🎯 Tujuan Utama

Tujuan dari workspace ini adalah:
1.  **Standardisasi:** Memastikan semua dokumen yang dihasilkan sesuai dengan standar formal dan struktur yang ditetapkan oleh Himafortic.
2.  **Efisiensi:** Mempercepat proses perencanaan dan pembuatan dokumen melalui panduan terstruktur dan diskusi terfokus.
3.  **Manajemen Pengetahuan:** Menyimpan seluruh konteks, data, dan histori kerja secara terpusat agar mudah diakses dan dilanjutkan oleh siapa pun di masa depan.
4.  **Kolaborasi AI:** Menyediakan struktur yang jelas agar AI Assistant dapat memahami konteks secara mandiri dan memberikan bantuan yang relevan dan akurat.

## 🚀 Memulai (Getting Started)

### 1. Clone Repositori

Untuk menggunakan workspace ini secara lokal, clone repositori ini menggunakan perintah berikut:

```bash
git clone https://github.com/gerrymoeis/proker_ai_asisten.git
```

### 2. Memulai Sesi dengan AI Assistant

Untuk memulai sesi kerja yang paling efisien dengan AI Assistant, gunakan prompt awal berikut. Prompt ini akan mengarahkan AI untuk langsung memahami seluruh konteks proyek yang telah kita bangun.

**Prompt Awal Optimal:**
> "Halo, saya ingin melanjutkan pekerjaan pada proyek dokumentasi Himafortic. Tolong mulai dengan membaca dan memahami sepenuhnya file-file yang berada dalam workspace ini, baca semua dan keseluruhan isi file-file tersebut, jangan lewatkan satu file pun untuk mendapatkan seluruh konteks, tujuan, aturan kerja, dan aset yang tersedia dalam workspace ini. Setelah itu, konfirmasi pemahaman Anda dan mulai sesi kerja Anda sesuai panduan workflow yang ada. Jangan lewatkan langkah-langkah penting dalam workflow ini. Dan pastikan anda selalu mencatat histori chat dan memperbarui rangkuman pemahaman setelah setiap interaksi signifikan."

## 📖 Panduan Penggunaan (Workflow)

Untuk melanjutkan pekerjaan di workspace ini, baik untuk panitia maupun AI Assistant, ikuti langkah-langkah berikut:

1.  **Pahami Konteks (Wajib untuk AI):** Jika sesi baru dimulai, selalu rujuk ke `rangkuman_pemahaman/ringkasan_konteks_awal.md`. Dokumen ini berisi seluruh pemahaman inti mengenai tujuan proyek, program kerja, standar dokumen, dan aset yang tersedia.
2.  **Gunakan Toolkit yang Ada:** Manfaatkan semua panduan dan template yang tersedia di dalam direktori `kerangka_kerja`.
    - Untuk **dokumen administratif** (proposal, LPJ, ToR), gunakan panduan di `kerangka_kerja/dokumen_spesifik/` untuk memandu diskusi dan menyusun draf.
    - Untuk **perencanaan strategis** (branding, kemitraan), gunakan panduan dan database di `kerangka_kerja/strategi_dan_kreatif/`.
3.  **Dokumentasikan Progres:** Setelah menyelesaikan tugas yang signifikan, selalu perbarui file `histori/chat_history_*.md` dan, jika perlu, perbarui juga `rangkuman_pemahaman/ringkasan_konteks_awal.md` untuk mencerminkan perubahan atau penambahan konteks baru.

## 📂 Struktur Direktori

Berikut adalah penjelasan singkat mengenai struktur direktori utama:

-   **/kerangka_kerja**:
    -   **Deskripsi:** Jantung dari workspace ini. Berisi semua alat bantu (panduan dan template) untuk eksekusi tugas.
    -   `dokumen_spesifik/`: Kumpulan panduan pertanyaan untuk setiap jenis dokumen resmi (proposal, ToR, LPJ, dll.).
    -   `strategi_dan_kreatif/`: Berisi panduan untuk brainstorming, strategi kemitraan, serta database sponsor dan media partner.

-   **/dokumen_contoh_referensi**:
    -   **Deskripsi:** Arsip dokumen-dokumen asli yang digunakan oleh AI Assistant pada tahap awal untuk mempelajari konteks dan standar Himafortic.

-   **/histori**:
    -   **Deskripsi:** Catatan atau log terperinci dari setiap sesi kerja. Berguna untuk melacak keputusan dan perubahan dari waktu ke waktu.

-   **/rangkuman_pemahaman**:
    -   **Deskripsi:** Dokumen tunggal yang merangkum seluruh pemahaman AI terhadap proyek. **Ini adalah titik awal bagi setiap AI agent baru.**

-   **/data**:
    -   **Deskripsi:** Tempat untuk menyimpan output atau data mentah yang dihasilkan selama proyek, seperti hasil riset atau draf awal.

---
Dibuat dan dikelola dengan bantuan AI Assistant.
