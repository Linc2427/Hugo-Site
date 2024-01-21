---
date: '2024-01-21T04:25:11+07:00'
draft: false
title: 'Instalasi Jupyter Notebook Menggunakan WSL'
tags: [tech, tutorial, jupyter notebook]
description: 'Jupyter Notebook merupakan sebuah program yang biasa digunankan untuk eksplorasi data menggunakan bahasa Julia, Python, dan R. Pada tutorial ini saya akan menunjukkan cara instalasi Jupyter Notebook dengan WSL.'
---
![Scenario 1: Jupyter Notebook](/notebook_windows_wsl.png)

Jupyter Notebook merupakan sebuah program yang biasa digunankan untuk eksplorasi data menggunakan bahasa Julia, Python, dan R. 

Pada kali ini saya akan menunjukkan cara menginstall Jupyter Notebook di Windows menggunakan WSL yang dimana menurut saya lebih mudah dibandingkan dengan cara instalasi secara biasa melalui instalasi python pada windows. Distro yang saya gunakan pada tutorial ini adalah **Ubuntu**.


Instalasi WSL dapat dilihat pada dokumentasi dari [Microsoft](https://learn.microsoft.com/en-us/windows/wsl/install). Setelah WSL terinstall ikuti langkah berikut:
1. Buka WSL Pada Terminal
2. Install pip
```shell
sudo apt install python3-pip
```
3. Install Jupyter Notebook
```shell
pip install notebook
```
4. Jalankan Jupyter Notebook
```shell
jupyter notebook
```
atau
```shell
python3 -m notebook
```
Untuk mengakses folder yang kalian inginkan gunakan perintah seperti biasa pada linux yaitu dengan cd ke direktori yang kalian inginkan.

Nah! cukup mudah bukan dibandingkan cara biasanya 👍😁👍
