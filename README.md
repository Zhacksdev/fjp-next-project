
# 🌐 FJP Official – Company Profile Website (Next.js Version)

Website ini merupakan versi remake dari website HTML statis milik FJP Official, dikembangkan ulang menggunakan **Next.js**, **Tailwind CSS**, dan **shadcn/ui** agar lebih modern, modular, dan SEO-friendly.

---

## 🚀 Live Preview

📍 [https://fjpofficial.com](https://fjpofficial.com)  
📍 (Subdomain dinamis, jika ada): `https://app.fjpofficial.com`

---

## ⚙️ Tech Stack

| Area             | Teknologi                                   |
|------------------|----------------------------------------------|
| Framework        | [Next.js](https://nextjs.org/)               |
| Styling          | [Tailwind CSS](https://tailwindcss.com/)     |
| UI Components    | [shadcn/ui](https://ui.shadcn.com/)          |
| Icons            | [Lucide React](https://lucide.dev/)          |
| Carousel         | [Swiper.js](https://swiperjs.com/)           |
| Gambar           | `next/image` (image optimization)            |
| SEO              | `next/head` + [`next-seo`](https://github.com/garmeeh/next-seo) |
| Deployment       | [Vercel](https://vercel.com/)                |

---

## 📥 Instalasi & Menjalankan Proyek

```bash
# 1. Clone repository
git clone https://github.com/username/fjp-next-project.git
cd fjp-next-project

# 2. Install dependencies
npm install

# 3. Jalankan development server
npm run dev

# 4. Buka di browser
http://localhost:3000
```

---

## 🧱 Struktur Folder

```
fjp-next-project/
├─ app/                  # Halaman utama (Next.js App Router)
│   └─ page.jsx
├─ components/           # Komponen utama: HeroImage, Client, WeDo, Service
├─ public/               # Aset publik: gambar, logo, icon SVG
├─ styles/               # File Tailwind + Global CSS
│   └─ globals.css
├─ .gitignore
├─ tailwind.config.js
├─ next.config.js
├─ README.md             # File dokumentasi ini
```

---

## ✨ Fitur Website

- ✅ Hero section dengan animasi teks dinamis
- ✅ Section "We Do" menampilkan keunggulan jasa
- ✅ Carousel klien dengan Swiper.js
- ✅ Komponen layanan siap dikembangkan dinamis
- ✅ SEO optimization dengan meta tag & open graph
- ✅ Gambar teroptimasi dan responsif

---

## 🛠️ Fitur Mendatang

- [ ] Konten layanan dinamis dari CMS
- [ ] Integrasi form kontak dengan `react-hook-form` atau API route
- [ ] Halaman portofolio projek
- [ ] Struktur blog artikel
- [ ] Mode gelap (dark mode)

---

## 💡 Kontributor

- 👨‍💻 [@Zhacksdev](https://github.com/Zhacksdev) – Fullstack Developer
- 📸 Tim FJP Official – Konten, branding, dan desain

---

## 📜 Lisensi

MIT License.  
Website ini dikembangkan untuk keperluan resmi FJP Official dan boleh digunakan kembali untuk proyek personal/non-komersial dengan menyebutkan atribusi.

---

### 🧠 Catatan Pengembangan

> Website ini sebelumnya dibangun menggunakan HTML statis. Remake dilakukan untuk mempercepat pengembangan, mempermudah kolaborasi tim, dan mendukung peningkatan performa melalui SSR dan optimasi SEO bawaan dari Next.js.
