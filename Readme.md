# -*- coding: utf-8 -*-
"""Markdown (README.md).ipynb

Automatically generated by Colaboratory.

Original file is located at
    https://colab.research.google.com/drive/1OCd-Ts1soo_N9CQhUrOYy1PQBBoCWkKg

Menggunakan google colab sebagai sarana penghubung ke streamlit

Sebelum code program di running, pastikan file:
- dashboard.py
- day.csv
- hour.csv

telah terupload di direktori file google colab,

setelah sudah, running code dibawah
"""

!pip install streamlit

!streamlit run dashboard.py & npx localtunnel --port 8501

"""Setelah kode kedua di running, muncul url, klik url tersebut.

Setelah diklik akan muncul tab baru, masukkan external url dengan menghilangkan http:// dan :8501 seperti contoh:
 http://34.68.93.184:8501 diubah menjadi 34.68.93.184

Klik submit dan hasil dashboard streamlit dapat terlihat
"""