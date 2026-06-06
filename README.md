# Shooter Plane (Phaser 3)

Game tembak pesawat 2D sederhana yang dibangun menggunakan HTML5, JavaScript, dan framework game **Phaser 3**. Proyek ini dibuat sebagai bagian dari pembelajaran/tugas (PJBL Kelas 11 Genap).

---

## 🎮 Fitur Utama

- **Menu Utama**: Tampilan menu interaktif sebelum memulai permainan.
- **Pilih Hero (Pesawat)**: Pilihan karakter pesawat dengan statistik atau tampilan berbeda sebelum bertanding.
- **Gameplay Tembak Pesawat**: Aksi menembak musuh, menghindari rintangan/peluru musuh, dan mengumpulkan poin.
- **Game Over**: Layar akhir game yang menampilkan skor serta tombol untuk mencoba kembali (restart).
- **Audio & Visual**: Menggunakan aset gambar dan suara untuk meningkatkan pengalaman bermain.

---

## 📂 Struktur Folder Proyek

```text
Shooter/
├── Shooter-Plane-Phaser/       # Folder utama game Phaser
│   ├── Assets/                 # Aset gambar, suara, dan visual pendukung
│   ├── index.html              # Entry point utama game
│   ├── sceneMenu.js            # Layar menu utama game
│   ├── scenePilihHero.js       # Layar pemilihan pesawat/hero
│   ├── scenePlay.js            # Logika utama permainan (gameplay)
│   └── sceneGameOver.js        # Layar setelah pemain kalah (game over)
├── package.json                # Konfigurasi dependensi project (Phaser)
└── README.md                   # Dokumentasi proyek (file ini)
```

---

## ⚙️ Persyaratan Sistem

- Browser modern (Google Chrome, Firefox, Edge, Safari, dll.)
- Web Server lokal (misal: **Live Server** di VS Code, Laragon, Python HTTP server, atau Node.js http-server) untuk menghindari isu kebijakan CORS saat memuat aset lokal secara dinamis.

---

## 🚀 Cara Menjalankan Game Secara Lokal

### Langkah 1: Kloning Repositori
Buka terminal Anda dan jalankan perintah berikut:
```bash
git clone https://github.com/LubaidArfaCasillas/Shooter.git
cd Shooter
```

### Langkah 2: Menjalankan Web Server
Karena Phaser memuat aset (gambar/audio) menggunakan AJAX, Anda membutuhkan server lokal:

#### Opsi A: Menggunakan Live Server (VS Code)
1. Buka folder `Shooter-Plane-Phaser` di VS Code.
2. Klik kanan pada file `index.html` dan pilih **Open with Live Server**.

#### Opsi B: Menggunakan Node.js (http-server)
Jika Anda memiliki Node.js terinstal, Anda dapat menjalankan perintah berikut di terminal:
```bash
# Install http-server secara global (jika belum ada)
npm install -g http-server

# Jalankan server di dalam folder game
cd Shooter-Plane-Phaser
http-server
```
Buka URL yang diberikan (biasanya `http://localhost:8080`) di browser Anda.

---

## 🛠️ Kontributor
* **Lubaid Arfa Casillas**
