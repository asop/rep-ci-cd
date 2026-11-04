# 🚀 rep-ci-cd

![CI/CD Testing](https://github.com/asop/rep-ci-cd/actions/workflows/main.yml/badge.svg)

> Percobaan CI/CD — tanpa Docker, cuma pakai GitHub Actions.

Repo ini untuk menjalankan CI/CD **tidak install Docker** dulu.

Setiap push kode ke `main`, GitHub otomatis nge-test dan nge-deploy.

---

## 🤔 Apa itu CI/CD?

**CI = Continuous Integration**
Setiap ada kode baru yang di-push, langsung di-test otomatis. 

**CD = Continuous Delivery**
Kalau test-nya lolos, kode baru itu langsung siap di-deploy ke user, tanpa deploy manual.

---

## ⚙️ Cara Kerjanya?

File `main.yml` ini yang ngatur semuanya:

1.  **Trigger:** Jalan otomatis tiap ada `push` ke branch `main`
2.  **Checkout:** GitHub ngambil kode terbaru
3.  **Test:** Ngecek apakah `index.html` ada dan gak error
4.  **Deploy:** Kalau lolos, keluar pesan `BERHASIL!`

Mau liat buktinya? Klik tab **Actions** di atas repo ini 👆

---

## 🛠️ Cara Coba Sendiri

1.  Clone repo ini
    ```bash
    git clone https://github.com/asop/rep-ci-cd.git


---
