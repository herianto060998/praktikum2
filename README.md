# praktikum2 
## program menghitung luas dan keliling lingkaran

### Rumus Luas & Keliling Lingkaran
Luas     = π(pi) × r²<p>
Keliling = 2 x π(pi) × r<p>

Nilai Phi yang akan kita gunakan adalah 22/7<p>
r merupakan jari-jari lingkaran<p>

Phi merupakan nilai konstanta di matematika sementara jari-jari merupakan jarak antara titik pusat dengan tepi lingkaran.<p>

### Flowchart Menghitung Luas & Keliling Lingkaran
![gambar1](gmb.ss/ss1.png.png)

### Program Python Menghitung Luas & Keliling Lingkaran 
INPUT <p>
r = int(input("Masukan Jari-jari : "))<p>
pi = 22/7

luas = pi*(r*r)<p>
keliling = 2*pi*r<p>

print ("Luas Lingkaran = ",luas,"cm")<p>
print ("Keliling Lingkaran = ",keliling,"cm")<p>
![gambar2](gmb.ss/ss2.png.png)

OUTPUT<p>
Masukan Jari-jari : 10
Luas Lingkaran =  314.2857142857143 cm <p>
Keliling Lingkaran =  62.857142857142854 cm <p>
Luas Lingkaran =  314.29<p>
Keliling Lingkaran =  62.86<p>
![gambar3](gmb.ss/ss3.png.png)

Penjelasan:<p>
Program diatas saya menggunakan phi = 22/7 . Fungsinya supaya saya dapat menyertakan nilai (phi) yang sudah ada .fungsi tersebut maka akan menghasilkan nilai phi = 22/7<p>

Selanjutnya kita memerlukan nilai jari-jari (r) yang nantinya akan di masukan oleh pengguna pada layar console. Kita menggunakan fungsi input() yang nilainya di konversi ke tipe data float (bilangan riil). Ingat bahwa fungsi input() akan menganggap semua nilai inputan bertipe string, sehingga kita perlu melakukan konversi ke tipe yang diinginkan.<p>

Ketika kita sudah mendapat nilai phi dan jari-jari selanjutnya kita bisa menghitung luas dan keliling sesuai dengan rumus-nya masing-masing .<p>

Selanjutnya kita tampilkan hasilnya dengan fungsi print().<p>

Jika dilihat hasil luas dan keliling lingkaran mempunyai angka pecahan yang cukup banyak, untuk mengambil 2 angka pecahan saja kita pakai fungsi format() seperti berikut:<p>

print ("Luas Lingkaran = ",format(luas,'.2f'))<p>
print ("Keliling Lingkaran = ",format(keliling,'.2f'))<p>

Luas Lingkaran          =<p>
Keliling Lingkaran      =<p>

Dengan penggunaan fungsi format(luas,’.2f’) akan menghasilkan 2 angka pecahan saja.<p>

## Penjelasan  dari LAB 1 DAN LAB 2

### Fungsi end
contoh inputan program sebagai berikut <p>
![gambar4](gmb.ss/ss4.png.png)

maka ouput saat run akan seperti berikut<p>
![gambar5](gmb.ss/ss5.png.png)

pengunaan end akan menghasilkan huruf kesamping pada (A,B,C) tetapi jika tidak menggunakan end hasilnya huruf akan berbaris kebawah (X,Y,Z)<p>

### Fungsi penggunaan Separator
contoh inputan program sebagai berikut<p>
![gambar6](gmb.ss/ss6.png.png)

maka output saat run akan seperti berikut<p>
![gambar7](gmb.ss/ss7.png.png)

penggunaan sep=',' akan menghasilkan output dengan pemisah angka yaitu koma<p>
penggunaan sep=" akan menghasilkan output tanpa tanda pemisah antar angka <p>
penggunaan sep=':' akan mengahasilkan output dengan pemisah angka yaitu titik dua<p> 
penggunaan sep='-' akan menghasilkan output dengan pemisah angka yaitu strip<p>

### Pengunaan string format
contoh inputan program sebagai berikut<p>
![gambar8](gmb.ss/ss8.png.png)

maka output saat run akan seperti berikut<p>
![gambar9](gmb.ss/ss9.png.png)

hasil output akan dimulai dari paragraf sebelah kiri dan angka akan terus dikalikan 10 setelah angka sebelumnya<p>

### Penggunaan string format 
contoh inputan program sebagai berikut<p>
![gambar10](gmb.ss/ss10.png.png)

maka output saat run akan seperti berikut<p>
![gambar11](gmb.ss/ss11.png.png)

hasil output akan dimulai dari paragraf sebelah kanan dan angka akan terus dikalikan 10 setelah angka sebelumnya<p>

### Program penjumlahan dan pembagian
contoh inputan program sebagai berikut <p>
![gambar12](gmb.ss/ss12.png.png)

maka output saat run akan seperti berikut <p>
![gambar13](gmb.ss/ss13.png.png)

saat kita memasukkan nilai pada variabel a dan b maka akan menghasilkan output penjumlahan dan pembagian <p>














