Tools OSINT Indonesia, untuk cek NIK & No HP. Script ini tidak akan ambil data dari database ilegal, tapi hanya dari sumber OSINT publik.

*versi : osint-indonesia-v5

$ git clone https://github.com/spyschools/osint-indonesia-v5.git

$ chmod +x *

$ cd osint-indonesia-v5

$ python3 osint_v5.py

[*] OSINT v3 siap jalan (NIK/HP → hasil + HTML)
Mode: (1) Single input, (2) Load dari file .txt ? 

*pilih 1 untuk single input
*pilih 2 ketik : targets.txt
*pastikan file targets.txt terisi list dan bisa kamu rubah isinya

*UPDATE
$ python3 osint_builder.py

$ unzip osint_v5.zip -d osint_v5_pkg

$ cd osint_v5_pkg

$ python3 osint_v5.py 3275124308050003 +6281234567890

gunakan tools ini dengan bijak, tools ini hanya untuk pengetesan dan pengembangan
