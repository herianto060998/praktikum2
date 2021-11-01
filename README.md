# praktikum2 
## program menghitung luas dan keliling lingkaran

### Rumus Luas & Keliling Lingkaran
Luas     = π × r²<p>
Keliling = 2 x π × r<p>

Nilai Phi yang akan kita gunakan adalah 3.14<p>
r merupakan jari-jari lingkaran<p>

Phi merupakan nilai konstanta di matematika sementara jari-jari merupakan jarak antara titik pusat dengan tepi lingkaran.<p>

### Flowchart Menghitung Luas & Keliling Lingkaran
![gambar1](gmb.ss/ss1.png.png)

### Program Python Menghitung Luas & Keliling Lingkaran 
INPUT <p>
import math<p>
r = float(input("Masukan Jari-jari : "))<p>

luas = math.pi*(r*r)<p>
keliling = 2*math.pi*r<p>

print ("Luas Lingkaran \t\t= ",luas)<p>
print ("Keliling Lingkaran\t= ",keliling)<p>
![gambar2](gmb.ss/ss2.png.png)

OUTPUT<p>
Masukan Jari-jari : 10<p>
Luas Lingkaran          =  314.1592653589793<p>
Keliling Lingkaran      =  62.83185307179586<p>
![gambar3](gmb.ss/ss3.png.png)

Penjelasan:<p>
Program diatas saya mengimport modul (math) yang sudah di sediakan oleh python. Fungsinya supaya saya dapat menyertakan nilai (phi) yang sudah tersedia dalam modul tersebut dengan perintah (math.pi) jika kita coba mencetak fungsi tersebut maka akan menghasilkan nilai 3.14<p>
import math<p>
print (math.pi)<p>

Selanjutnya kita memerlukan nilai jari-jari (r) yang nantinya akan di masukan oleh pengguna pada layar console. Kita menggunakan fungsi input() yang nilainya di konversi ke tipe data float (bilangan riil). Ingat bahwa fungsi input() akan menganggap semua nilai inputan bertipe string, sehingga kita perlu melakukan konversi ke tipe yang diinginkan.<p>

Ketika kita sudah mendapat nilai phi dan jari-jari selanjutnya kita bisa menghitung luas dan keliling sesuai dengan rumus-nya masing-masing (lihat pada baris ke 3 & 4).<p>

Selanjutnya kita tampilkan hasilnya dengan fungsi print(). sintak \t merupakan karakter espace yang berfungsi untuk membuat tab. dalam kasus ini agar sejajar karakter sama dengan (=) nya.<p>

Jika dilihat hasil luas dan keliling lingkaran mempunyai angka pecahan yang cukup banyak, untuk mengambil 2 angka pecahan saja kita pakai fungsi format() seperti berikut:<p>

print ("Luas Lingkaran \t= ",format(luas,'.2f'))<p>
print ("Keliling Lingkaran \t= ",format(keliling,'.2f'))<p>

Luas Lingkaran          =<p>
Keliling Lingkaran      =<p>

Dengan penggunaan fungsi format(luas,’.2f’) akan menghasilkan 2 angka pecahan saja.<p>










