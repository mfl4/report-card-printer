# report-card-printer

Utilitas Python ringan yang mendemonstrasikan cara data kartu laporan (rapor) siswa disimpan dan divalidasi. Proyek ini menampilkan tipe data inti Python yang digunakan untuk merepresentasikan catatan seorang siswa, antara lain, nama, status keterdaftaran, usia, dan nilai. Serta cara memeriksa dan memverifikasi tipe dari setiap nilai saat program berjalan.

## Isi Folder

| Berkas          | Keterangan                                                       |
| --------------- | ----------------------------------------------------------------- |
| `main.py`       | Program yang mendefinisikan field rapor dan mencetak tipenya.     |
| `LICENSE`       | Dedikasi domain publik CC0 1.0 Universal.                        |
| `.gitignore`    | Aturan abaikan standar Python untuk version control.             |

## Cara Memulai

1. Pastikan Python 3 telah terpasang.
2. Jalankan program dari dalam folder proyek:

   ```bash
   python main.py
   ```

## Cara Kerja

Skrip ini mendefinisikan field-field pada kartu rapor, lalu mencetak setiap nilai
beserta tipe datanya menggunakan fungsi bawaan `type()`. Program juga menggunakan
`isinstance()` untuk memverifikasi bahwa sebuah nilai termasuk tipe yang
diharapkan.

```python
name = 'Alice'
print(name, type(name))

is_student = True
print(is_student, type(is_student))

age = 20
print(age, type(age))

score = 80.5
print(isinstance(score, float))
print(score, type(score))
```

- `name` adalah **string** (`str`) yang menyimpan nama siswa `'Alice'`.
- `is_student` adalah **boolean** (`bool`) yang menandai status keterdaftaran (`True`).
- `age` adalah **integer** (`int`) yang menyimpan nilai `20`.
- `score` adalah **float** (`float`) yang menyimpan nilai `80.5`; `isinstance(score, float)`
  memastikan bahwa `score` termasuk tipe `float`.

## Output yang Diharapkan

```
Alice <class 'str'>
True <class 'bool'>
20 <class 'int'>
True
80.5 <class 'float'>
```

## Konsep Utama

- Menyimpan field rapor ke dalam variabel dan memberikan nilai yang sesuai.
- Merepresentasikan data dengan tipe `str`, `bool`, `int`, dan `float`.
- Menggunakan `print()` dan `type()` untuk memeriksa nilai.
- Menggunakan `isinstance()` untuk memeriksa apakah suatu nilai termasuk tipe tertentu.

## Lisensi

Dirilis di bawah [CC0 1.0](LICENSE), menempatkan karya ini ke dalam domain
publik.
