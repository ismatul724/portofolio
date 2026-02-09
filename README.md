Portfolio website profesional yang dibangun dengan HTML, CSS, dan JavaScript murni.

## 📋 Deskripsi

Website portofolio modern dan responsif dengan desain yang clean dan professional. Website ini menampilkan informasi pribadi, keahlian, project yang telah dikerjakan, dan informasi kontak.

## 🚀 Fitur

- **Responsive Design** - Tampilan optimal di semua perangkat (desktop, tablet, mobile)
- **Smooth Scrolling** - Navigasi yang halus antar section
- **Animated Elements** - Animasi fade-in dan hover effects
- **Interactive Navigation** - Mobile hamburger menu
- **Contact Form** - Formulir kontak yang fungsional
- **Professional Layout** - Desain yang clean dan modern

## 📁 Struktur Folder

```
portfolio/
│
├── index.html          # File HTML utama
│
├── css/
│   └── style.css       # File CSS untuk styling
│
├── js/
│   └── script.js       # File JavaScript untuk interaktivity
│
└── README.md           # Dokumentasi project
```

## 🎨 Sections

1. **Header/Hero** - Nama dan deskripsi singkat dengan call-to-action buttons
2. **About Me** - Informasi tentang diri, pengalaman, dan background
3. **Skills** - Keahlian dan teknologi yang dikuasai
4. **Projects** - Portfolio project yang telah dikerjakan
5. **Contact** - Informasi kontak dan formulir untuk menghubungi

## 💻 Teknologi yang Digunakan

- HTML5
- CSS3 (dengan CSS Variables untuk theming)
- JavaScript (Vanilla JS - tanpa framework)

## 🎯 Cara Menggunakan

1. Download atau clone repository ini
2. Buka file `index.html` di browser
3. Atau gunakan Live Server untuk development

```bash
# Jika menggunakan Live Server di VS Code
# Klik kanan pada index.html -> Open with Live Server
```

## ✏️ Customisasi

### Mengubah Informasi Pribadi

Edit file `index.html` dan ganti:
- Nama di bagian `<h1>` dan `<title>`
- Deskripsi di bagian hero dan about
- Skills, projects, dan informasi kontak

### Mengubah Warna

Edit CSS variables di file `css/style.css`:

```css
:root {
    --primary-color: #2563eb;    /* Warna utama */
    --primary-dark: #1e40af;     /* Warna utama gelap */
    --secondary-color: #64748b;  /* Warna sekunder */
    /* ... */
}
```

### Menambah Project

Tambahkan card baru di section projects:

```html
<div class="project-card">
    <div class="project-image">
        <!-- Image atau placeholder -->
    </div>
    <div class="project-content">
        <h3>Nama Project</h3>
        <p>Deskripsi project</p>
        <div class="project-tech">
            <span>Tech 1</span>
            <span>Tech 2</span>
        </div>
        <div class="project-links">
            <a href="#" class="project-link">Live Demo</a>
            <a href="#" class="project-link">GitHub</a>
        </div>
    </div>
</div>
```

## 📱 Responsive Breakpoints

- Desktop: > 768px
- Tablet: 768px
- Mobile: < 480px

## 🔧 Fitur JavaScript

- Mobile menu toggle
- Smooth scrolling navigation
- Active section highlighting
- Scroll animations
- Form validation
- Parallax effects
- Hover interactions

## 📝 License

Project ini bebas digunakan untuk keperluan pribadi dan pembelajaran.
