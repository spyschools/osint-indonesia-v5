# 🇮🇩 Tools OSINT Indonesia

Tools OSINT sederhana untuk melakukan pencarian informasi berdasarkan **NIK** atau **Nomor HP** menggunakan **sumber data OSINT (Open Source Intelligence)** yang tersedia secara publik.

> **Penting:** Tools ini **tidak mengambil data dari database ilegal, hasil kebocoran data (data breach), maupun database pribadi**. Semua informasi yang ditampilkan berasal dari sumber publik yang dapat diakses secara legal.

---

## ✨ Fitur

* 🔍 Pencarian berdasarkan NIK
* 📱 Pencarian berdasarkan Nomor HP
* 📄 Mendukung pencarian satu per satu (Single Input)
* 📂 Mendukung pencarian massal menggunakan file `.txt`
* 🌐 Export hasil ke format HTML
* 🔄 Update otomatis ke versi terbaru

---

## Instalasi

Clone repository:

```bash
git clone https://github.com/spyschools/osint-indonesia-v5.git
```

Masuk ke folder project:

```bash
cd osint-indonesia-v5
```

Berikan izin eksekusi:

```bash
chmod +x *
```

Jalankan tools:

```bash
python3 osint_v5.py
```

---

## Cara Penggunaan

Saat program dijalankan akan muncul pilihan:

```
[*] OSINT v5 siap jalan (NIK/HP → hasil + HTML)

Mode:
(1) Single Input
(2) Load dari file .txt
```

### Mode 1 - Single Input

Pilih:

```
1
```

Kemudian masukkan NIK atau Nomor HP yang ingin dilakukan pencarian.

---

### Mode 2 - Load dari File

Pilih:

```
2
```

Kemudian masukkan nama file, misalnya:

```
targets.txt
```

Contoh isi file:

```
081234567890
081298765432
3201xxxxxxxxxxxx
```

Anda dapat mengubah isi `targets.txt` sesuai kebutuhan.

---

## Update ke Versi Terbaru

Jalankan:

```bash
python3 osint_builder.py
```

Kemudian ekstrak hasil build:

```bash
unzip osint_v5.zip -d osint_v5_pkg
```

Masuk ke folder:

```bash
cd osint_v5_pkg
```

Jalankan tools:

```bash
python3 osint_v5.py
```

---

## Struktur Project

```
.
├── osint_v5.py
├── osint_builder.py
├── targets.txt
├── output/
└── README.md
```

---

## Persyaratan

* Python 3.x
* Koneksi internet

---

## Disclaimer

Tools ini dibuat **hanya untuk tujuan edukasi, penelitian, pengujian keamanan (security testing), dan pengembangan**.

Pengguna bertanggung jawab penuh atas penggunaan tools ini. Penulis tidak bertanggung jawab atas penyalahgunaan yang melanggar hukum, privasi, atau ketentuan yang berlaku.

Gunakan tools ini secara **etis, legal, dan bertanggung jawab**.

---

## Kontribusi

Pull Request, Issue, dan saran pengembangan selalu diterima untuk meningkatkan kualitas tools ini.

---

## Lisensi

Silakan gunakan, modifikasi, dan kembangkan sesuai dengan lisensi yang diterapkan pada repository ini.
