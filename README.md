# 📚 Buku Interactive Framework

Sebuah sistem dan *workflow* berbasis AI untuk mengubah buku cetak atau PDF statis menjadi lingkungan belajar 3D yang imersif dan interaktif. Proyek ini menggunakan arsitektur prompt universal yang dapat diterapkan untuk semua mata pelajaran (Biologi, Fisika, Sejarah, Geografi, dll) menggunakan web-based 3D rendering (Three.js).

## ⚙️ Cara Kerja (Workflow)

Sistem ini bergantung pada *Canvas workspace* di model AI generasi terbaru untuk men-generate lingkungan 3D dan kode pendukungnya secara bersamaan.

1. **Pilih Model & Tool:** Buka workspace AI (seperti Gemini dengan fitur Canvas/Code Editor).
2. **Siapkan Konteks (Prompting):** Gunakan template dari `PROMPT_FRAMEWORK.md` untuk menginstruksikan pembuatan lingkungan 3D.
3. **Upload Referensi Data:** Unggah file PDF materi buku teks dan gambar referensi agar akurasi keilmuannya terjaga.
4. **Generate & Eksplorasi:** AI akan merender kode HTML/JS/Three.js menjadi *environment* 3D interaktif di mana pengguna bisa memutar objek, membaca info, dan melakukan *zoom*.
5. **Iterasi:** Gunakan instruksi lanjutan (misal: *"Perlambat animasi"* atau *"Ubah warna background menjadi lebih terang"*) untuk menyempurnakan UI/UX.

## 🛠 Teknologi yang Digunakan
- **HTML5/CSS3/JavaScript:** Struktur dasar aplikasi.
- **Three.js:** Library utama untuk rendering grafik 3D di browser tanpa perlu plugin tambahan.
- **AI Code Generation:** Engine utama pembuat *boilerplate* dan logika interaksi 3D.

## 🚀 Penggunaan
Ambil prompt dari `PROMPT_FRAMEWORK.md`, sesuaikan *bracket* `[...]` dengan mata pelajaran yang Anda inginkan, lalu jalankan di AI Code Canvas.