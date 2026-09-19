# ACPEDIA®

[![Hugo](https://img.shields.io/badge/Hugo-v0.165.0--extended-blue.svg)](https://gohugo.io/)
[![Theme](https://img.shields.io/badge/Theme-hugo--bearblog-yellow.svg)](https://github.com/janraasch/hugo-bearblog)
[![License](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)
[![Deploy](https://img.shields.io/badge/Deploy-Cloudflare%20Pages-orange.svg)](https://acpedia.pages.dev/)

**ACPEDIA®** adalah platform repositori dan ensiklopedia teknis independen berbahasa Indonesia yang membahas teknologi pendingin udara (*Air Conditioner*) secara komprehensif dari A sampai Z.

---

## 🌐 Live Preview
* **Production URL:** [https://acpedia.pages.dev/](https://acpedia.pages.dev/)

---

## 💚 Struktur Konten Utama
* **[Mulai dari Sini](/mulai/)**: Alur belajar bertahap 4 level.
* **[Semua Tulisan](/blog/)**: Arsip artikel teknis dan kalkulasi beban termal.
* **[Glosarium](/glosarium/)**: Kamus istilah teknis AC (A–Z) pendingin udara.
* **[Tentang](/tentang/)**: Profil repositori dan transparansi kurasi konten.

---

## 🤩 Spesifikasi Teknologi & Desain
* **Static Site Generator:** Hugo Extended
* **Basis Tema:** Hugo Bear Blog
* **Tipografi:** Inter via rsms.me
* **Styling Kustom:** Terpusat pada `files layouts/partials/style.html`
* **Komponen Terkunci:** Navigasi kurung siku `[menu]` nav.html dan Footer dengan pemisah cycle back-to-top.

---

## 💥 Panduan Pengembangan Lokal

```bash
git clone --recurse-submodules https://github.com/stagnansi/acpedia.git
cd acpedia
hugo server -D
```

---

## 🚀 Alur Deployment (CI/CD)
Setiap commit pada branch `main` akan memicu auto-build di Cloudflare Pages.

---

## 📦 Transparansi & Lisensi
Konten disusun bersama AI dan lolos verifikasi manual oleh ACPEDIA®. Dilisensikan di bawah MIT License.
