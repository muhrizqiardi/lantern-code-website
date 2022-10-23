# LanternCode Website

Tugas UTS Pemrograman Web 2020B

dibuat oleh Muhammad Rizqi Ardiansyah (20051204044)

---

## Mengunjungi LanternCode

<https://lantern-code-website.vercel.app/>

---

## Apa itu LanternCode?

- LanternCode adalah sebuah website kursus belajar pemrograman.
- Di website ini terdapat ribuan _content creator_ yang membuat konten pembelajaran.

---

## Struktur Halaman LanternCode

LanternCode terdiri dari:

- [_Home page_](https://lantern-code-website.vercel.app/)
- [Halaman buat akun](https://lantern-code-website.vercel.app/sign-up.html)
- [Halaman masuk akun](https://lantern-code-website.vercel.app/sign-in.html)
- [Halaman informasi LanternCode Premium](https://lantern-code-website.vercel.app/premium.html)
- [Halaman pencarian kursus](https://lantern-code-website.vercel.app/search.html)
- [Halaman kursus](https://lantern-code-website.vercel.app/course-detail.html)
- [Halaman _content creator_](https://lantern-code-website.vercel.app/content-creator.html)

---

## Tentang LanternCode

- LanternCode menggunakan `parcel` sebagai build tools
- Kelebihan dari `parcel`:
  - minim konfigurasi, dan
  - performa sangat cepat

---

## Tentang LanternCode (cont.)

- LanternCode menggunakan `scss`, bahasa _superset_ dari css untuk penulisan _styles_
- Kelebihan dari `scss`:
  - penulisan kode yang efisien, tidak ada lagi pengulangan kode yang boros, dan
  - kemudahan dalam konfigurasi Bootstrap (seperti mengganti warna primary dan lain-lain)

---

## Cara menjalankan LanternCode

- Memastikan Node dan NPM terpasang
- Membuka terminal/_command prompt_
- Mengganti direktori ke direktori projek
- Meng-_install_ semua package dengan perintah:

  ```bash
   npm install
  ```

- Melakukan proses _build_ dengan perintah:

  ```bash
  npm run build
  ```

- Menjalankan server dengan perintah:

  ```bash
  npm run serve
  ```

- Membuka halaman di <http://localhost:3000/>
