# 🌍 INNOVATE OS— Environmental Intelligence System

**INNOVATE OS** adalah platform intelijen lingkungan berbasis web statis yang menggabungkan visualisasi **Satelit LEO**, simulasi **AI Vision**, dan pengelolaan **Big Data** krisis lingkungan di Indonesia. 

Proyek ini dibangun menggunakan **HTML5**, **Tailwind CSS**, dan berbagai library animasi modern untuk menciptakan pengalaman pengguna yang interaktif dan futuristik tanpa memerlukan instalasi backend yang rumit.

---

## 🚀 Fitur Utama

### 1. **Neural Intelligence Dashboard (Home)**
* **AI Vision Scanner:** Simulasi pemindaian citra satelit real-time untuk mendeteksi anomali vegetasi dan deforestasi.
* **Real-time Event Toasts:** Sistem notifikasi dinamis yang memunculkan peringatan bencana terbaru secara otomatis.
* **Danger Marquee Strip:** Baris peringatan bahaya (Siaga 1, Waspada) yang bergerak untuk informasi cepat.

### 2. **3D Global Monitoring (About)**
* **Interactive 3D Earth:** Visualisasi Bumi berputar dengan atmosfer dinamis menggunakan CSS murni.
* **Mission Overview:** Penjelasan filosofi dan jembatan antara teknologi luar angkasa dengan kelestarian alam.

### 3. **Advanced Simulation Lab (Simulasi)**
* **8 Skenario Bencana:** Simulasi detail untuk Banjir, Longsor, Gempa, Kebakaran, Limbah, Badai, Erupsi, dan Polusi.
* **Impact Engine:** Kalkulasi estimasi korban jiwa, kerugian infrastruktur (Triliun Rupiah), dan radius kerusakan dalam KM².
* **Interactive Projections:** Grafik garis eskalasi bencana berbasis waktu menggunakan Chart.js.

### 4. **Crisis Archive & Data (Data)**
* **Big Data Management:** Arsip kejadian krisis nasional yang dilengkapi dengan sistem **Pagination** (6 kartu per halaman).
* **Live Filtering:** Fitur pencarian wilayah dan kategori bencana yang bekerja secara instan.
* **Intelligence Modal:** Pop-up detail yang menampilkan koordinat GPS, status mitigasi, dan tren statistik 7 hari terakhir.

### 5. **Public Reporting Center (Contact)**
* **Multi-Image Upload Preview:** Warga dapat mengunggah bukti foto kejadian dengan preview instan sebelum dikirim ke sistem.
* **Grey-Scale Map Integration:** Peta lokasi markas besar yang disesuaikan dengan estetika dashboard.

---

## 🛠️ Teknologi & Library

* **Framework:** HTML5 / Vanilla JavaScript.
* **Styling:** [Tailwind CSS CDN](https://tailwindcss.com/) (JIT Engine).
* **Animations:** [GSAP](https://greensock.com/gsap/) (ScrollTrigger & Staggered Motion).
* **Data Visualization:** [Chart.js](https://www.chartjs.org/).
* **Slider/Carousel:** [Flickity](https://flickity.metafizzy.co/).
* **Icons:** FontAwesome 6.4.0.
* **Fonts:** Plus Jakarta Sans & Space Grotesk (Google Fonts).

---

## 💻 Cara Menjalankan Proyek

Karena proyek ini menggunakan teknologi statis, tidak diperlukan instalasi server atau `npm install`.

1. **Download/Clone** semua file proyek.
2. Pastikan Anda memiliki koneksi internet (untuk memuat library dari CDN).
3. **Buka File:**
   * Klik kanan pada `index.html` -> Open with Browser (Chrome/Edge/Firefox).
   * **Rekomendasi:** Gunakan ekstensi **Live Server** di VS Code untuk pengalaman navigasi antar halaman yang lebih mulus.

---

## 📂 Struktur File

```text
innovate-os/
├── index.html       # Halaman Utama (Hero & AI Vision)
├── about.html       # Halaman Visi & 3D Earth
├── simulator.html    # Laboratorium Simulasi 8 Bencana
├── data.html        # Database Arsip & Pagination
├── contact.html     # Pusat Laporan & Kontak
└── README.md        # Dokumentasi Proyek