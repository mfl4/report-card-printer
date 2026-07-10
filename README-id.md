# report-card-printer

Sebuah proyek workshop Python kecil dari kursus **Dasar-Dasar Python**. Folder
ini berisi latihan praktis yang memperkenalkan konsep dasar Python: variabel
dan tipe data.

## Isi Folder

| Berkas          | Keterangan                                                       |
| --------------- | ----------------------------------------------------------------- |
| `main.py`       | Program contoh yang mendemonstrasikan variabel dan tipenya.       |
| `LICENSE`       | Dedikasi domain publik CC0 1.0 Universal.                        |
| `.gitignore`    | Aturan abaikan standar Python untuk version control.             |

## Cara Memulai

1. Pastikan Python 3 telah terpasang.
2. Jalankan program dari dalam folder proyek:

   ```bash
   python main.py
   ```

## Apa yang Dilakukan `main.py`

Skrip ini menunjukkan cara menyimpan nilai ke dalam variabel dan memeriksa
tipe datanya menggunakan fungsi bawaan `type()`.

```python
name = 'Alice'
print(name, type(name))

is_student = True
print(is_student, type(is_student))
```

- `name` adalah **string** (`str`) yang menyimpan teks `'Alice'`.
- `is_student` adalah **boolean** (`bool`) yang menyimpan nilai `True`.

Menjalankan program akan mencetak setiap nilai beserta tipenya:

```
Alice <class 'str'>
True <class 'bool'>
```

## Tujuan Pembelajaran

- Mendeklarasikan variabel dan memberikan nilai.
- Mengenali tipe data `str` dan `bool`.
- Menggunakan `print()` dan `type()` untuk mengeksplorasi nilai.

## Lisensi

Dirilis di bawah [CC0 1.0](LICENSE), menempatkan karya ini ke dalam domain
publik.
