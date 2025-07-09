
# 🌐 FJP Official – Company Profile Website (Next.js Version)

Website ini merupakan versi remake dari website HTML statis milik FJP Official, dikembangkan ulang menggunakan **Next.js**, **Tailwind CSS**, dan **shadcn/ui** agar lebih modern, modular, dan SEO-friendly.

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
├─ app/                     # Folder utama untuk routing dan halaman
│  ├─ article/              # Halaman artikel
│  ├─ contact/              # Halaman kontak
│  ├─ home/                 # Halaman beranda
│  ├─ product/              # Halaman produk
│  ├─ service/              # Halaman layanan
│  ├─ favicon.ico           # Ikon website
│  ├─ globals.css           # Global stylesheet
│  ├─ layout.tsx            # Root layout Next.js App Router
│  └─ page.tsx              # Root page (default route)
├─ node_modules/            # Dependency packages
├─ public/                  # Aset publik: gambar, font, icon
├─ .gitignore               # File untuk mengecualikan file dari Git
├─ eslint.config.mjs        # Konfigurasi linting JavaScript/TypeScript
├─ next-env.d.ts            # TypeScript environment declarations
├─ next.config.ts           # Konfigurasi utama Next.js
├─ package-lock.json        # Lockfile dependencies
├─ package.json             # Metadata proyek dan dependencies
├─ postcss.config.mjs       # Konfigurasi PostCSS
├─ README.md                # File dokumentasi proyek
└─ tsconfig.json            # Konfigurasi TypeScript
```

---

## 🛠️ Fitur Mendatang

- [ ] Konten layanan dinamis dari CMS
- [ ] Integrasi form kontak dengan `react-hook-form` atau API route
- [ ] Halaman portofolio projek
- [ ] Struktur blog artikel
- [ ] Mode gelap (dark mode)
- [ ] Navigasi yang lebih terstruktur
- [ ] Integrasi AI untuk generate gambar proyek
- [ ] Menampilkan konten dari Instagram
- [ ] Chat bot otomatis

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
