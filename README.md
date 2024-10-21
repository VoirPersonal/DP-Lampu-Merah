# DP Lampu Merah #
- Nama: Fikri Abiyyu Rahman
- NIM: 2409116063
- Prodi: Sistem Informasi B

## Penjelasan Baris Kode ##
``` python
from prettytable import PrettyTable
import time
```
Preattytable adalah module yang digunakan agar dapat menampilkan table dalam baris kode
time, digunakan agar baris kode bisa ditampilkan dengan adanya selang waktu

```python
tabel = PrettyTable()
tabel.field_names = ["Nama", "Nim", "Prodi"]
tabel.add_row(["Fikri Abiyyu Rahman", "2409116063", "Sistem Informasi"])
print(tabel)
print("")
print("")
print("")
```
Baris kode diatas berfungsi untuk menampilkan nama, nim, dan prodi

```python
while True:
```
Digunakan untuk membuat pengulangan

```python
    print("-- ini lampu merah --")
    lampu_merah = PrettyTable()
    lampu_merah.field_names = ["Lampu Lalu Lintas"]
    lampu_merah.add_row(["🔴"])
    lampu_merah.add_row(["⚪"])
    lampu_merah.add_row(["⚪"])
    print("")
    print("")
```
Baris kode diatas digunakan untuk menampilkan tabel yang berbentuk seperti rambu lalu lintas. Disini sedang berwarna merah yang berarti berhenti

```python
    print(lampu_merah)
    print("1")
    time.sleep(1)
    print("2")
    time.sleep(1)
    print("3")
    time.sleep(1)
    print("4")
    time.sleep(1)
    print("5")
    time.sleep(1)
    print("6")
    time.sleep(1)
    print("7")
    time.sleep(1)
    print("8")
    time.sleep(1)
    print("9")
    time.sleep(1)
    print("10")
    time.sleep(1)
    print("")
    print("")
```
Baris kode diatas berfungsi untuk membuat hitungan dalam rambu lalu lintas (10 detik), sehingga dapat beralih meenjadi warna berikutnya. Disini dari merah akan beralih menuju lampu kuning

```python
    print("-- Ini Lampu Kuning --")
    lampu_kuning = PrettyTable()
    lampu_kuning.field_names = ["Lampu Lalu Lintas"]
    lampu_kuning.add_row(["⚪"])
    lampu_kuning.add_row(["🟡"])
    lampu_kuning.add_row(["⚪"])
    print("")
    print("")
```
Baris kode diatas digunakan untuk menampilkan tabel yang berbentuk seperti rambu lalu lintas. Disini sedang berwarna kuning yang berarti siap-siap

```python
    print(lampu_kuning)
    print("1")
    time.sleep(1)
    print("2")
    time.sleep(1)
    print("3")
    time.sleep(1)
    print("4")
    time.sleep(1)
    print("5")
    time.sleep(1)
    print("")
    print("")
```
Baris kode diatas berfungsi untuk membuat hitungan dalam rambu lalu lintas (5 detik), sehingga dapat beralih meenjadi warna berikutnya. Disini dari merah akan beralih menuju lampu kuning

```python
    print("-- Ini Lampu Hijau --")
    lampu_Hijau = PrettyTable()
    lampu_Hijau.field_names = ["Lampu Lalu Lintas"]
    lampu_Hijau.add_row(["⚪"])
    lampu_Hijau.add_row(["⚪"])
    lampu_Hijau.add_row(["🟢"])
    print("")
    print("")
```
Baris kode diatas digunakan untuk menampilkan tabel yang berbentuk seperti rambu lalu lintas. Disini sedang berwarna hijau yang berarti jalan

```python
    print(lampu_Hijau)
    print("1")
    time.sleep(1)
    print("2")
    time.sleep(1)
    print("3")
    time.sleep(1)
    print("4")
    time.sleep(1)
    print("5")
    time.sleep(1)
    print("6")
    time.sleep(1)
    print("7")
    time.sleep(1)
    print("8")
    time.sleep(1)
    print("9")
    time.sleep(1)
    print("10")
    time.sleep(1)
    print("")
    print("")
```
Baris kode diatas berfungsi untuk membuat hitungan dalam rambu lalu lintas (10 detik), sehingga dapat beralih meenjadi warna berikutnya. Disini dari hijau akan kembali ke lampu merah
