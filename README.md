# 🚀 N8N Workflow Collection

Repo ini berisi kumpulan workflow **n8n** yang gw buat untuk berbagai kebutuhan automation (AI, Telegram bot, finance, dll).

---

## 📦 Isi Repo

### 1️⃣ `1.json` — *Automation Finance News Analyzer*

**Deskripsi singkat:**

> Workflow ini bertujuan untuk mencari berita finansial global yang beredar dan menganalisanya dengan format yang lebih user friendly, Dan akan terintegrasikan ke telegram bot

**Fitur utama:**

* ✅ Pengambilan data dari newsapi.org
* ✅ Analisa AI sentiment & impact
* ✅ Integrasi pada telegram bot

**Preview Workflow:**
![Workflow](./docs/1-workflow.png)

**Contoh Output:**
![Output](./docs/1-output.png)

---

## ⚙️ Cara Pakai

1. Import file `.json` ke n8n:

   * Buka n8n
   * Klik **Import Workflow**
   * Upload file

2. Setup credentials:

   * API Key (jika ada)
   * Telegram Bot Token (jika pakai Telegram)
   * dll

3. Jalankan workflow 🚀

---

## 💡 Notes

* Semua workflow bisa dimodifikasi sesuai kebutuhan
* Pastikan semua credential sudah di-setup sebelum run
* Kalau error, cek node yang butuh API / auth

---

## 🧠 Tujuan Repo

* Dokumentasi workflow pribadi
* Portfolio automation & AI
* Sharing ke orang lain biar bisa langsung pakai

---

🔥 *Feel free buat fork, modif, atau improve workflow ini!*
