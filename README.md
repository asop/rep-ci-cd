# 🚀 rep-ci-cd

> Percobaan CI/CD — tanpa Docker, cuma pakai GitHub Actions.

Repo ini bukti kalau buat jalanin CI/CD itu **gak harus ribet** dan **gak harus install Docker** dulu.

Setiap push kode ke `main`, GitHub otomatis nge-test dan nge-deploy.

---

## 🤔 Apa itu CI/CD?

**CI = Continuous Integration**
Setiap ada kode baru yang di-push, langsung di-test otomatis. Kalau ada yang error, langsung ketahuan, bukan nunggu sebulan kemudian.

**CD = Continuous Delivery**
Kalau test-nya lolos, kode baru itu langsung siap di-deploy ke user, tanpa deploy manual.

Gambaran:
`Masak (Code) -> Cicipin (Test) -> Sajiin ke Pelanggan (Deploy)` — semua otomatis.

---

## 📁 Struktur Repo
