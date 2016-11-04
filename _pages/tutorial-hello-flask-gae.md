---
title: Tutorial Aplikasi Hello di Google App Engine
permalink: /tutorial-hello-flask-gae
---
Framework yang digunakan adalah Flask di Python 2.7.

Sebelum menjalankan perintah-perintah Python di Command Prompt, pastikan pindah ke Anaconda environment yang menggunakan Python 2.7:

    activate py27

Troubleshooting: Bila Anda mendapatkan error "The input line is too long." maka Anda perlu menyunting `PATH` agar lebih ringkas (hapus beberapa bagian yang dirasa tidak perlu).

Berikut adalah langkah-langkah di https://cloud.google.com/appengine/docs/python/getting-started/python-standard-env .

## Set up libraries

1. Buat folder chatbot, misalnya `C:\Users\ceefour\git\studygroup-bot`
2. Di dalam folder tersebut buat file appengine_config.py sesuai Getting Started
3. Buka Command Prompt, aktifkan Python 2.7:

        activate py27

4. Install Flask:

        pip install -t flask

## Creating the app.yaml file

1. Buat file `app.yaml` versi 1 sesuai panduan
2. Coba jalankan:

    dev_appserver.py .

3. Lalu buka di http://localhost:8080/

## Lanjutan

[GAE Starter Kit](https://github.com/kkinder/GAEStarterKit) memiliki fitur bawaan yang lebih lengkap.
