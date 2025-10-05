## 🚀 Alur CI/CD

1. Setiap commit ke branch `main` memicu workflow GitHub Actions.  
2. Workflow melakukan checkout kode, konfigurasi Pages, dan proses deploy.  
3. Website otomatis diperbarui di GitHub Pages setelah workflow selesai.

---

## ✅ Fitur

- Deploy otomatis ke GitHub Pages.  
- Workflow YAML menggunakan `actions/configure-pages@v5` dan `actions/deploy-pages@v4`.  
- Permissions disesuaikan untuk akses `pages: write` dan `id-token: write`.

---

## 🔗 Link

- Website Live: [https://joselumbanraja.github.io/CI-CD/](https://joselumbanraja.github.io/CI-CD/)  
- Repository GitHub: [github.com/joselumbanraja/CI-CD](https://github.com/joselumbanraja/CI-CD)

---

## 🧩 Rencana Pengembangan

- Menambahkan tahap testing otomatis.  
- Integrasi linting dan build tools.  
- Menyertakan notifikasi hasil build.

---

## 📄 Lisensi

Proyek ini dibuat untuk tujuan pembelajaran CI/CD.
