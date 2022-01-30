# assignment 03
Terdapat kode Python berikut ini yang akan digunakan.
```python
import html
char1 = html.unescape('&#x25FB;')
char2 = html.unescape('&#x25FC;')

NIM = '10298345'
for x in NIM:
  n = int(x, 10)
  s = ''
  for i in range(n):
    s += char
  print(n, ':', s, sep='')
```

## question 1
Ganti nilai variabel NIM dengan data Anda, jalankan kode yang diberikan, dan tampilkan hasilnya.

### anwser 1
Traceback (most recent call last):
  File "HelloWorld.py", line 10, in <module>
    s += char
NameError: name 'char' is not defined

![image](https://user-images.githubusercontent.com/98453803/151682438-145117ec-3966-4d4a-b2b3-64315beb7306.png)

  
## question 2
Ganti nilai variabel NIM dengan data Anda, modifikasi kode yang diberikan di atas dengan `s += char1`, jalankan dan tampilkan hasilnya.

### anwser 2
1:10219069◻
0:10219069
2:10219069◻◻
1:10219069◻
9:10219069◻◻◻◻◻◻◻◻◻
0:10219069
6:10219069◻◻◻◻◻◻
9:10219069◻◻◻◻◻◻◻◻◻
  
![image](https://user-images.githubusercontent.com/98453803/151682489-83b02e81-dea9-4c23-8508-888e65c6aad3.png)

## question 3
Ganti nilai variabel NIM dengan data Anda, modifikasi kode yang diberikan di atas dengan `s += char2`, jalankan dan tampilkan hasilnya.

### anwser 3
1:10219069◼
0:10219069
2:10219069◼◼
1:10219069◼
9:10219069◼◼◼◼◼◼◼◼◼
0:10219069
6:10219069◼◼◼◼◼◼
9:10219069◼◼◼◼◼◼◼◼◼
  
![image](https://user-images.githubusercontent.com/98453803/151682539-3d734b14-6972-464f-bc43-4ce2f1e5b76c.png)
  
## question 4
Jelaskan dengan singkat hal yang dihasillkan oleh kode yang diberikan.

### answer 4
Kode html.unescape() berfungsi untuk mengubah string ascii menjadi skrip html dengan mengganti karakter ascii dengan karakter khusus menggunakan metode html.escape().
Kode html.unescape() untuk char1 memberikan kotak kosong.
Kode html.unescape() untuk char2 memberikan kotak penuh.
Kode for in berfungsi untuk perulangan for digunakan untuk mengulangi urutan.
Kode range berfungsi untuk fungsi yang digunakan untuk menghasilkan urutan angka.
Kode int() berfungsi untuk mengubah nilai yang ditentukan menjadi bilangan bulat.
Kode print() berfungsi untuk menampilkan hasil kalkulasi.
