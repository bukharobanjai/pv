# 🧮 Kalkulator Sederhana dengan Python (Google Colab)

Proyek ini merupakan implementasi kalkulator sederhana menggunakan bahasa pemrograman Python yang dijalankan di Google Colab. Kalkulator ini dapat melakukan operasi dasar seperti:
- Penjumlahan
- Pengurangan
- Perkalian
- Pembagian

## 🚀 Fitur

- Input dari pengguna secara interaktif
- Validasi pembagian dengan nol
- Menampilkan hasil operasi secara jelas
- Mudah dikembangkan untuk fitur lanjutan

## 📄 Contoh Kode

```python
def tambah(a, b):
    return a + b

def kurang(a, b):
    return a - b

def kali(a, b):
    return a * b

def bagi(a, b):
    if b != 0:
        return a / b
    else:
        return "Error: Pembagian dengan nol!"
