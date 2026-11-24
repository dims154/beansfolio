# ☕ Beansfolio

**Personal Portfolio Website** milik **Muhammad Ilham Dimas Meidi**  
Dibangun dengan **Astro** — cepat, modern, dan fully responsive.

[![Astro](https://img.shields.io/badge/Astro-7-BC52EE?logo=astro&logoColor=white)](https://astro.build)
[![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?logo=typescript&logoColor=white)](https://www.typescriptlang.org/)
[![License](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)

---

## ✨ Fitur

- 🎯 **Hero Section** modern dengan status ketersediaan
- 👨‍💻 **About Me** + tech stack
- 🛠️ **Skills** dikelompokkan (Backend / Frontend / Tools) + icon
- 🚀 **Featured Projects** dengan preview & link GitHub
- 🏆 **Certificates** (Python, Generative AI, Data Science)
- 📬 **Contact Section**
- 📱 Fully responsive + desain glassmorphism
- ⚡ Performa tinggi berkat Astro

---

## 🛠️ Tech Stack

| Kategori     | Teknologi                          |
|--------------|------------------------------------|
| Framework    | Astro 7                            |
| Language     | TypeScript                         |
| Icons        | astro-icon + Iconify               |
| Styling      | Custom CSS (Glassmorphism)         |
| Package Manager | npm                             |

---

## 🚀 Getting Started

### Prerequisites
- Node.js **≥ 22.12.0**

### Instalasi

```bash
# Clone repository
git clone https://github.com/dims154/beansfolio.git
cd beansfolio

# Install dependencies
npm install

# Jalankan development server
npm run dev
```

Buka di browser: [http://localhost:4321](http://localhost:4321)

### Build untuk Production

```bash
npm run build
npm run preview
```

---

## 📁 Struktur Project

```text
beansfolio/
├── public/
│   ├── certificates/     # Gambar & PDF sertifikat
│   ├── projects/         # Screenshot project
│   └── favicon.*
├── src/
│   ├── assets/
│   │   └── images/       # Foto profil
│   ├── components/       # Komponen halaman
│   │   ├── About.astro
│   │   ├── Certificates.astro
│   │   ├── Contact.astro
│   │   ├── Hero.astro
│   │   ├── Navbar.astro
│   │   ├── Projects.astro
│   │   └── Skills.astro
│   ├── layouts/
│   │   └── Layout.astro
│   ├── pages/
│   │   └── index.astro
│   └── styles/
│       └── global.css
├── astro.config.mjs
└── package.json
```

---

## 🎨 Customization

Ingin pakai sebagai template portfolio sendiri?

1. Ganti data di masing-masing komponen (`Hero.astro`, `About.astro`, `Projects.astro`, `Certificates.astro`, dll)
2. Ganti foto profil di `src/assets/images/profile.jpg`
3. Update screenshot project di `public/projects/`
4. Update sertifikat di `public/certificates/`
5. Ubah meta title & description di `src/layouts/Layout.astro`

---

## 🤝 Contributing

Kontribusi sangat diterima!

1. Fork repository ini
2. Buat branch baru (`git checkout -b feature/nama-fitur`)
3. Commit perubahan (`git commit -m 'Add some feature'`)
4. Push ke branch (`git push origin feature/nama-fitur`)
5. Buat Pull Request

---

## 📄 License

Proyek ini dilisensikan di bawah **MIT License**.  
Silakan gunakan, modifikasi, dan bagikan secara bebas.

> **Catatan**: Saat ini file `LICENSE` belum ada di repo. Disarankan menambahkan file LICENSE (MIT) agar status open source lebih jelas.

---

## 👤 Author

**Muhammad Ilham Dimas Meidi**  
Mahasiswa Sistem Informasi • Full Stack Developer

- GitHub: [@dims154](https://github.com/dims154)
- Portfolio: [beansfolio](https://github.com/dims154/beansfolio)

---

⭐ Jika project ini bermanfaat, jangan lupa kasih **star** ya!
