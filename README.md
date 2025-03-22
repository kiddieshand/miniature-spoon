---
layout: default
title: Miniature Spoon
---

# 🥄 Miniature Spoon

Selamat datang di **Miniature Spoon**! 🎉  
Website sederhana untuk pecinta miniatur.

---

## 🚀 Tentang Miniature Spoon
**Miniature Spoon** adalah website yang menampilkan berbagai informasi menarik tentang miniatur, termasuk koleksi unik dan tips merawatnya.

---

## 📷 Tampilan Website
![Miniature Spoon](assets/img/background.jpg)

---

## 📌 Cara Mengakses  
Buka halaman ini secara langsung melalui GitHub Pages setelah mengunggahnya ke repository.  
Jika menggunakan **GitHub Pages**, URL akan berbentuk:  
miniature-spoon/
│── _layouts/
│   └── default.html
│── index.md
│── assets/
│   └── img/
│       └── background.jpg
└── _config.yml
<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>{{ page.title }}</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <nav>
        <h1>Miniature Spoon</h1>
        <ul>
            <li><a href="/">Home</a></li>
            <li><a href="/tentang">Tentang</a></li>
            <li><a href="/kontak">Kontak</a></li>
        </ul>
    </nav>

    <main>
        {{ content }}
    </main>

    <footer>
        <p>&copy; 2025 Miniature Spoon. Semua Hak Dilindungi.</p>
    </footer>
</body>
</html>
theme: minima
title: Miniature Spoon
description: Website sederhana untuk pecinta miniatur

