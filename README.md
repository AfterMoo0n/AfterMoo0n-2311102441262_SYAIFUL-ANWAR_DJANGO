# Personal Portfolio

[![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=fff)](#)
[![Django](https://img.shields.io/badge/Django-%23092E20.svg?logo=django&logoColor=white)](#)

Perkenalkan Saya Syaiful Anwar , website ini akan menjadi portofolio saya dalam mendevelop website dengan framework django 

## Ada apa saja di website ini?

1. Halaman Utama - Menampilkan ringkasan dari masing-masing halaman.
2. Halaman About - Menampilkan projek apa saja yang telah saya buat.
3. Halaman Blog - Menampilkan tulisan yang saya tulis.

## Praktikum 2 Cara instalansi django dan  Menjalankan Project

1. Salin projek

```shell
git clone https://github.com/akhmadqasim/portfolio.git
```

2. Buat virtual environment

```shell
# Universal Python
python -m venv .venv
```

atau di kasus tertentu menggunakan

```shell
# Python 3 Specified
python3 -m venv .venv
```

3. Activate .venv

```shell
# Windows
.venv\Scripts\activate

# macOS/Linux
source .venv/bin/activate
```

4. Install dependency

```shell
pip install django
```

5. Jalankan project

```shell
python manage.py runserver
```
# Praktikum 3
Di Praktikum ini saya melakukan
- Membuat directori baru ( media, static, templates)
- membuat file baru pada directory websiteku (nama dari website Utama ) , yaitu (views.py)
- menambahkan file pada folder static ( page.js, picture.png, style.css)
- Menambahkan file about.html
- menambahkan file about.html dan home.html 
- konfigurasi pada websiteku di bagian settings menambahkan import os pada line 12 kemudian mengubah secret key menambahkan * pada bagian allowed_host untuk menyesuaikan alamat dari host mana yang dapat mengakses ( bisa mengganti dengan ip addres 
  atau domain atau hosting yang kita miliki) . kemudian mengubah setting dirs. pada TEMPLATES jika memerlukan html maka kita bisa  untuk menyesuaikan set folder template html yang berfungsi ketika ingin merender template. yang terakhir pada konfigurasi settings.py yaitu mengdownload sqliteclient untuk dabases menggunakan databases sqlite3
- konfigurasi urls.py memetakan jalur url yang benar pada file views.py (isinya ada fungsi untuk jalur dari file home.html dan abaout.html)
- menambahkan path abaout dan path home pada urls.py
- menambahkan static admin , setting.py

# Praktikum 4
- Membuat apps dan Model

1. Membuat App user
```commandline
django-admin startapp user
```
2. Membuat App berita
```commandline
django-admin startapp berita
```

3. Make Migrations
```commandline
python manage.py makemigration
```

4. Migrate
```commandline
python manage.py migrate
```

5. Install Pillow dalam venv
```commandline
pip install pillow
```