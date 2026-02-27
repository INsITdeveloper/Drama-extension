Drama Extension 🎬
Drama Extension adalah sebuah alat/ekstensi yang dirancang untuk mengelola, mengorganisir, dan memutar konten drama atau video pendek secara efisien menggunakan struktur data JSON. Ekstensi ini memungkinkan pengguna untuk mengakses metadata lengkap drama beserta daftar episode dengan tautan video langsung.
✨ Fitur Utama
 * Metadata Lengkap: Menampilkan judul, deskripsi, genre, dan cover drama.
 * Daftar Episode Terstruktur: Mendukung navigasi episode dari awal hingga akhir (misal: Episode 1 - 73+).
 * Streaming Langsung: Memutar video langsung melalui URL yang disediakan dalam data.
 * Format Data Fleksibel: Menggunakan skema JSON yang mudah dimodifikasi dan diintegrasikan.
🛠️ Struktur Data JSON
Ekstensi ini menggunakan format data berikut untuk menampilkan konten:
[
  {
    "book_id": "7596621470965435445",
    "title": "Judul Drama",
    "genres": ["Genre 1", "Genre 2"],
    "description": "Deskripsi singkat alur cerita...",
    "cover_url": "https://link-gambar-cover.jpg",
    "episodes": [
      {
        "index": 1,
        "video_url": "https://link-video-episode-1.mp4"
      }
    ]
  }
]

🚀 Penggunaan (Usage)
1. Persiapan Data
Pastikan Anda memiliki file JSON dengan struktur yang sesuai seperti contoh di atas. Anda dapat menambahkan lebih banyak drama atau episode ke dalam array tersebut.
2. Instalasi (Jika berupa Ekstensi Chrome/Browser)
 * Unduh atau clone repositori ini: git clone https://github.com/INsITdeveloper/Drama-extension.git.
 * Buka browser (Chrome/Edge/Brave).
 * Masuk ke halaman Extensions (chrome://extensions/).
 * Aktifkan Developer Mode di pojok kanan atas.
 * Klik Load unpacked dan pilih folder hasil clone tadi.
3. Cara Menonton
 * Buka ekstensi dari bar browser.
 * Pilih judul drama yang tersedia di daftar.
 * Pilih nomor episode yang ingin ditonton.
 * Video akan otomatis dimuat dari CDN/URL yang tertera.
👨‍💻 Developer
Proyek ini dikembangkan dan dipelihara oleh:
 * GitHub: @INsITdeveloper
 * Project Name: Drama Extension
📝 Lisensi
Proyek ini dilisensikan di bawah MIT License. Anda bebas menggunakannya untuk keperluan pribadi maupun pengembangan lebih lanjut.
Contoh Konten yang Didukung:
| Judul | Jumlah Episode | Genre Utama |
|---|---|---|
| Pacar Virtual Sang CEO | 73+ | Pemeran Utama Pria, CEO, Superpower |
Dibuat dengan ❤️ oleh INsITdeveloper.

