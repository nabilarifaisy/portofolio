# Portofolio Nabil Arif A’isy

Website statis (HTML + CSS dalam satu file), siap di-host di GitHub Pages.

## Deploy ke GitHub Pages

1. Buat repository baru di GitHub. Untuk alamat `https://USERNAME.github.io`, beri nama repo persis `USERNAME.github.io`. Nama lain juga boleh, alamatnya jadi `https://USERNAME.github.io/NAMA-REPO/`.
2. Unggah semua file di folder ini (`index.html`, `.nojekyll`, `README.md`) ke branch `main`. Bisa lewat tombol **Add file → Upload files**, atau lewat terminal:

```bash
git init
git add .
git commit -m "Portofolio pertama"
git branch -M main
git remote add origin https://github.com/USERNAME/NAMA-REPO.git
git push -u origin main
```

3. Buka **Settings → Pages**. Pada **Build and deployment**, pilih **Deploy from a branch**, branch `main`, folder `/ (root)`, lalu **Save**.
4. Tunggu 1–2 menit, lalu buka alamat yang muncul di halaman Pages.

## Catatan

- Font dimuat dari Google Fonts, jadi perlu koneksi internet. Tanpa itu, font bawaan sistem dipakai.
- Untuk mengubah isi, edit `index.html` lalu commit ulang. Situs akan diperbarui otomatis.
