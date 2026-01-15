# 💝 GIF Cinta - Interactive Love Proposal Web App

[![HTML](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![CSS](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)](https://tailwindcss.com/)

Aplikasi web interaktif untuk mengekspresikan perasaan cinta dengan cara yang unik dan menyenangkan. Dilengkapi dengan animasi GIF, efek suara, dan interaksi yang menarik.

---

## 📋 Daftar Isi

- [Tentang Proyek](#-tentang-proyek)
- [Fitur](#-fitur)
- [Demo](#-demo)
- [Teknologi](#-teknologi)
- [Struktur File](#-struktur-file)
- [Cara Menggunakan](#-cara-menggunakan)
- [Halaman](#-halaman)
- [Customisasi](#-customisasi)
- [Audio Files](#-audio-files)
- [Lisensi](#-lisensi)
- [Pembuat](#-pembuat)

---

## 🎯 Tentang Proyek

**GIF Cinta** adalah aplikasi web sederhana yang dirancang untuk membantu seseorang mengungkapkan perasaan cinta dengan cara yang interaktif dan menyenangkan. Aplikasi ini menggunakan GIF animasi, SweetAlert untuk dialog interaktif, dan efek suara untuk menciptakan pengalaman yang berkesan.

### Konsep:
1. **Halaman Awal** (`index.html`) - Menanyakan kabar
2. **Halaman Proposal** (`baik.html`) - Halaman utama untuk melamar/menyatakan perasaan
3. **Halaman Demo** (`app.html`) - Halaman testing/demo

---

## ✨ Fitur

### 🎨 Halaman Awal (`index.html`)
- ✅ Tampilan GIF animasi yang menarik
- ✅ Dua pilihan interaktif: "Baik" dan "Tidak"
- ✅ SweetAlert dialog untuk feedback
- ✅ Redirect otomatis ke halaman berikutnya
- ✅ Desain responsif dengan Tailwind CSS

### 💕 Halaman Proposal (`baik.html`)
- ✅ Background animasi GIF romantis
- ✅ Tombol "Terima" dan "Tidak"
- ✅ **Tombol "Tidak" yang kabur** - Bergerak acak saat di-hover (tidak bisa diklik!)
- ✅ Perubahan GIF dinamis saat diterima
- ✅ **Triple audio playback** - 3 efek suara dimainkan bersamaan
- ✅ Animasi teks yang berubah setelah menerima
- ✅ Watermark pembuat dengan animasi bounce

### 🧪 Halaman Demo (`app.html`)
- ✅ Halaman sederhana untuk testing
- ✅ Menggunakan CSS custom

---

## 🎬 Demo

### Alur Penggunaan:

1. **Buka `index.html`**
   - User ditanya "Apa kabar?"
   - Jika pilih "Baik" → Lanjut ke halaman proposal
   - Jika pilih "Tidak" → Dialog tidak bisa melanjutkan

2. **Di halaman `baik.html`**
   - User ditanya "Apakah kamu mau jadi pacar aku?"
   - Tombol "Tidak" akan kabur saat di-hover
   - Jika pilih "Terima":
     - GIF berubah menjadi romantis
     - 3 audio dimainkan: `hore.mp3`, `text.mp3`, `bgsond.mp3`
     - Teks berubah: "Terima kasih sudah menerima cintaku"
     - GIF berganti setiap 3 detik

---

## 🛠 Teknologi

### Frontend
- **HTML5** - Struktur halaman
- **CSS3** - Styling custom
- **JavaScript (ES6+)** - Logika interaktif
- **Tailwind CSS (CDN)** - Framework CSS untuk styling cepat
- **SweetAlert** - Dialog interaktif yang cantik

### Assets
- **GIF Animasi** - Dari Pinterest
- **Audio Files** - Format MP3 untuk efek suara

### Keuntungan Menggunakan CDN:
- ✅ Tidak perlu instalasi Node.js
- ✅ Tidak perlu `npm install`
- ✅ Tidak perlu build process
- ✅ Langsung bisa dibuka di browser
- ✅ Ukuran proyek lebih kecil

---

## 📁 Struktur File

```
gif_cinta/
├── 📄 index.html           # Halaman awal - menanyakan kabar
├── 📄 baik.html            # Halaman proposal - pertanyaan utama
├── 📄 app.html             # Halaman demo/testing
│
├── 🎨 style.css            # CSS untuk index.html
├── 🎨 baik.css             # CSS untuk baik.html
├── 🎨 stylentn.css         # CSS untuk app.html
│
├── 📜 app.js               # JavaScript untuk app.html
│
├── 🔊 hore.mp3             # Audio efek "hore" (70.7 KB)
├── 🔊 text.mp3             # Audio efek teks (45.3 KB)
├── 🔊 bgsond.mp3           # Audio background sound (213 KB)
│
├── 📖 README.md            # Dokumentasi ini
└── 📖 CLEANUP.md           # Dokumentasi pembersihan file
```

### Total File: 13 files
### Total Audio Size: ~329 KB

---

## 🚀 Cara Menggunakan

### Metode 1: Langsung Buka di Browser

1. **Clone atau download repository ini**
   ```bash
   git clone <repository-url>
   cd gif_cinta
   ```

2. **Double-click file HTML**
   - Klik 2x pada `index.html` untuk membuka di browser default

### Metode 2: Menggunakan Live Server (Recommended)

1. **Install VS Code Extension: Live Server**
   - Buka VS Code
   - Pergi ke Extensions (Ctrl+Shift+X)
   - Cari "Live Server"
   - Install

2. **Jalankan Live Server**
   - Buka folder `gif_cinta` di VS Code
   - Klik kanan pada `index.html`
   - Pilih "Open with Live Server"
   - Browser akan otomatis terbuka di `http://localhost:5500`

### Metode 3: Python HTTP Server

```bash
# Python 3
python -m http.server 8000

# Python 2
python -m SimpleHTTPServer 8000
```

Buka browser: `http://localhost:8000`

---

## 📄 Halaman

### 1. `index.html` - Halaman Awal

**Tujuan**: Menanyakan kabar user sebelum lanjut ke halaman utama

**Fitur**:
- GIF sapaan dari Pinterest
- Tombol "Baik" dan "Tidak"
- SweetAlert untuk konfirmasi
- Redirect ke `baik.html` jika pilih "Baik"

**Code Highlights**:
```javascript
const handleClickBaik = () => {
    swal({
        title: "Baik!",
        text: "Kabar baik, terima kasih.",
        buttons: {
            next: { text: "Next", value: "next" }
        }
    }).then((value) => {
        if (value === "next") {
            window.location.href = "baik.html";
        }
    });
};
```

---

### 2. `baik.html` - Halaman Proposal Utama

**Tujuan**: Halaman utama untuk menyatakan perasaan

**Fitur Utama**:

#### 🎯 Tombol "Tidak" yang Kabur
```javascript
const b = document.querySelector('button.no')
b.addEventListener('mouseover', moveHover);

function moveHover() {
    const i = Math.floor(Math.random() * 100) + 1;
    const j = Math.floor(Math.random() * 100) + 1;
    b.style.left = i + 'px';
    b.style.top = j + 'px';
}
```
Tombol akan bergerak secara acak saat mouse mendekat!

#### 🎵 Triple Audio Playback
```javascript
const audio1 = new Audio('/hore.mp3');
audio1.play();

const audio2 = new Audio('/text.mp3');
audio2.play();

const audio3 = new Audio('/bgsond.mp3');
audio3.play();
```
3 audio dimainkan bersamaan untuk efek dramatis!

#### 🖼 Dynamic GIF Changing
```javascript
setTimeout(() => {
    document.getElementById('dynamicImage').src = 
        'https://i.pinimg.com/originals/97/7e/27/...gif';
}, 3000);

setTimeout(() => {
    document.getElementById('dynamicImage').src = 
        'https://i.pinimg.com/originals/6c/69/d2/...gif';
}, 6000);
```
GIF berganti setiap 3 detik!

---

### 3. `app.html` - Halaman Demo

**Tujuan**: Halaman sederhana untuk testing konsep

**Catatan**: Halaman ini masih dalam development dan bisa digunakan untuk eksperimen

---

## 🎨 Customisasi

### Mengganti GIF

#### Di `index.html`:
```html
<!-- Line 16 -->
<img src="https://i.pinimg.com/originals/1c/f5/a1/1cf5a15991830ba91dc23392a2560ae2.gif"
     class="rounded-xl mb-2" alt="Hai">
```
Ganti URL dengan GIF pilihanmu!

#### Di `baik.html`:
```html
<!-- Line 14 - GIF Awal -->
<img id="dynamicImage"
     src="https://i.pinimg.com/originals/27/9a/37/279a3784afd830bbdc8c01659a6e7d2d.gif"
     class="rounded-xl mb-2" alt="Hai">
```

```javascript
// Line 41 - GIF saat diterima
document.getElementById('dynamicImage').src =
    'https://i.pinimg.com/originals/e7/b0/26/e7b0269da7c8635849a9a6b15a5c2fb3.gif';
```

### Mengganti Teks

#### Di `index.html`:
```html
<!-- Line 18 -->
<h1 class="w-full text-center font-medium">Halo Apa kabar?</h1>
```

#### Di `baik.html`:
```html
<!-- Line 19 -->
<h1 id="dynamicText" class="font-medium text-md text-white">Hai cantik</h1>

<!-- Line 21 -->
<h4 id="dynamicDes" class="font-normal text-md text-white text-center">
    Apakah kamu mau jadi pacar aku?
</h4>
```

### Mengganti Warna

Menggunakan Tailwind CSS classes:

```html
<!-- Background -->
<div class="h-screen bg-sky-200">  <!-- Ganti bg-sky-200 -->

<!-- Tombol -->
<button class="px-5 py-1 bg-blue-400">  <!-- Ganti bg-blue-400 -->
```

**Warna Tailwind yang tersedia**:
- `bg-red-400`, `bg-pink-400`, `bg-purple-400`
- `bg-blue-400`, `bg-green-400`, `bg-yellow-400`
- `bg-indigo-400`, `bg-violet-400`, `bg-fuchsia-400`

### Mengganti Audio

Untuk mengganti file audio, pastikan:
1. Format file: **MP3** (recommended)
2. Letakkan di root folder
3. Update path di JavaScript:

```javascript
const audio1 = new Audio('/hore.mp3');  // Ganti nama file
```

---

## 🔊 Audio Files

### 📊 Detail Audio

| File | Ukuran | Durasi (est.) | Fungsi |
|------|--------|---------------|--------|
| `hore.mp3` | 70.7 KB | ~3-5 detik | Efek celebrasi |
| `text.mp3` | 45.3 KB | ~2-3 detik | Efek teks/notifikasi |
| `bgsond.mp3` | 213 KB | ~10-15 detik | Background music |

### 🎵 Kapan Audio Dimainkan?

Audio dimainkan **HANYA** ketika user klik tombol **"Terima"** di `baik.html`.

Ketiga audio dimainkan **bersamaan** untuk efek dramatis:
```javascript
const audio1 = new Audio('/hore.mp3');
audio1.play();  // Play immediately

const audio2 = new Audio('/text.mp3');
audio2.play();  // Play immediately

const audio3 = new Audio('/bgsond.mp3');
audio3.play();  // Play immediately
```

### 💡 Tips Audio
- Pastikan volume speaker tidak terlalu keras
- Audio akan auto-play (tidak perlu user interaction)
- Format MP3 didukung semua browser modern

---

## 🎨 Tailwind CSS Classes yang Digunakan

### Layout & Sizing
```css
h-screen          /* height: 100vh */
w-full            /* width: 100% */
flex              /* display: flex */
flex-col          /* flex-direction: column */
justify-center    /* justify-content: center */
items-center      /* align-items: center */
```

### Spacing
```css
p-2, p-5          /* padding */
mt-2, mt-3, mt-5  /* margin-top */
mb-2              /* margin-bottom */
gap-3             /* gap between flex items */
```

### Colors & Backgrounds
```css
bg-sky-200        /* background-color: sky 200 */
bg-blue-400       /* background-color: blue 400 */
bg-zinc-400       /* background-color: zinc 400 */
text-white        /* color: white */
```

### Borders & Effects
```css
rounded-xl        /* border-radius: 0.75rem */
rounded-md        /* border-radius: 0.375rem */
shadow-xl         /* box-shadow extra large */
bg-opacity-20     /* background opacity 20% */
```

### Animations
```css
animate-bounce    /* bounce animation */
transition        /* transition all */
duration-300      /* transition duration 300ms */
hover:bg-yellow-400  /* hover state */
```

### Positioning
```css
relative          /* position: relative */
absolute          /* position: absolute */
left-0, right-0   /* left/right: 0 */
bottom-2, right-2 /* positioning */
```

### Typography
```css
font-medium       /* font-weight: 500 */
font-bold         /* font-weight: 700 */
text-md           /* font-size: medium */
text-xs           /* font-size: extra small */
text-center       /* text-align: center */
```

---

## 🌐 Browser Support

Aplikasi ini kompatibel dengan:
- ✅ Google Chrome (Recommended)
- ✅ Mozilla Firefox
- ✅ Microsoft Edge
- ✅ Safari
- ✅ Opera

**Versi Minimum**: Browser modern yang mendukung ES6+ JavaScript

---

## 📝 Catatan Penting

### ⚠️ File yang TIDAK DIPERLUKAN

File-file berikut **SUDAH DIHAPUS** karena tidak digunakan:
- ❌ `node_modules/` - Tidak diperlukan (menggunakan CDN)
- ❌ `package.json` - Tidak diperlukan
- ❌ `package-lock.json` - Tidak diperlukan
- ❌ `tailwind.config.js` - Tidak diperlukan (menggunakan CDN)
- ❌ `postcss.config.js` - Tidak diperlukan

📖 **Baca [CLEANUP.md](./CLEANUP.md)** untuk penjelasan lengkap tentang pembersihan file.

### ✅ Keuntungan Setelah Pembersihan
- 🚀 Ukuran proyek lebih kecil (~50-100 MB lebih ringan)
- ⚡ Tidak perlu instalasi dependencies
- 🔥 Langsung bisa dijalankan di browser
- 📦 Mudah di-share atau deploy

---

## 🚀 Deployment

### Hosting Gratis yang Bisa Digunakan:

#### 1. **GitHub Pages**
```bash
# Push ke GitHub
git add .
git commit -m "Initial commit"
git push origin main

# Enable GitHub Pages di Settings > Pages
```

#### 2. **Netlify**
- Drag & drop folder ke [netlify.com](https://netlify.com)
- Atau connect ke GitHub repository

#### 3. **Vercel**
```bash
# Install Vercel CLI
npm install -g vercel

# Deploy
vercel
```

#### 4. **Surge.sh**
```bash
# Install Surge
npm install -g surge

# Deploy
surge
```

---

## 🔐 Privacy & Security

- ✅ Tidak ada tracking
- ✅ Tidak ada database
- ✅ Tidak ada pengumpulan data user
- ✅ 100% client-side (berjalan di browser)
- ✅ Tidak ada server backend

---

## 🐛 Troubleshooting

### Audio Tidak Dimainkan
**Penyebab**: Browser modern memblokir auto-play audio
**Solusi**: Pastikan user sudah melakukan interaksi (klik tombol)

### GIF Tidak Muncul
**Penyebab**: Koneksi internet lambat atau URL GIF invalid
**Solusi**: 
- Cek koneksi internet
- Coba ganti dengan GIF lokal

### Tailwind Classes Tidak Bekerja
**Penyebab**: CDN Tailwind tidak terload
**Solusi**: 
- Cek koneksi internet
- Pastikan ada baris ini di `<head>`:
  ```html
  <script src="https://cdn.tailwindcss.com"></script>
  ```

---

## 🤝 Kontribusi

Kontribusi selalu diterima! Silakan:
1. Fork repository ini
2. Buat branch baru (`git checkout -b feature/AmazingFeature`)
3. Commit perubahan (`git commit -m 'Add some AmazingFeature'`)
4. Push ke branch (`git push origin feature/AmazingFeature`)
5. Buat Pull Request

---

## 📜 Lisensi

Proyek ini bersifat **open source** dan bebas digunakan untuk keperluan pribadi.

**Catatan**:
- GIF yang digunakan berasal dari Pinterest - pastikan memeriksa lisensi jika digunakan secara komersial
- Audio files harus memiliki lisensi yang sesuai jika digunakan secara komersial

---

## 👨‍💻 Pembuat

**@AndriDev**

> *"Cinta itu seperti kode - butuh debugging, refactoring, dan komitmen untuk membuatnya sempurna."* 💝

---

## 📞 Kontak & Support

Jika ada pertanyaan atau butuh bantuan:
- 💬 Buat Issue di repository ini
- 📧 Contact: [email anda]
- 🌐 Website: [website anda]

---

## 🎯 Future Improvements

### Fitur yang Bisa Ditambahkan:
- [ ] Mode dark/light theme toggle
- [ ] Pilihan bahasa (Indonesia/English)
- [ ] Custom GIF picker
- [ ] Share ke social media
- [ ] Countdown timer
- [ ] Animasi confetti saat diterima
- [ ] Music player controls (play/pause)
- [ ] Responsive design untuk mobile
- [ ] PWA (Progressive Web App) support
- [ ] Custom nama user (personalisasi)

---

## 📚 Resources

### GIF Sources
- [Pinterest](https://pinterest.com) - Sumber GIF animasi

### Libraries Used
- [Tailwind CSS](https://tailwindcss.com) - Utility-first CSS framework
- [SweetAlert](https://sweetalert.js.org) - Beautiful alert dialogs

### Learning Resources
- [MDN Web Docs](https://developer.mozilla.org) - HTML, CSS, JavaScript
- [Tailwind CSS Docs](https://tailwindcss.com/docs) - Tailwind documentation

---

## ⭐ Star History

Jika proyek ini berguna untukmu, jangan lupa kasih ⭐ ya!

---

<div align="center">

### 💝 Dibuat dengan ❤️ oleh @AndriDev

**Happy Coding & Good Luck with Your Love! 🎉**

</div>
