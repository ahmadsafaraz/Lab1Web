# Lab1Web
# 1. Melakukan perubahan pada kode adakah eror kesalahan pebulisan tag

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/9680b31e-357f-4f32-99a4-98c65d71ab55" />

# 2. perbedaan P dengan br dan penjelasannya
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/dfa326fa-cf7c-4e74-aaa0-99a429d9a9a0" />

berikut adalah contoh dari penggunaan tag p yaitu
membuat sebuah paragraf yang memberikan jarak atas dan bawah (margin) pada tag p juga berfungsi untuk membungkus teks sebagai satu kesatuan teks ditampilkan dengan jarak antar paragraf




<img width="1900" height="1060" alt="image" src="https://github.com/user-attachments/assets/986fef30-9f71-42e4-91b5-db36e9999a67" />


berikut adalah contoh dari penggunaan br yaitu
memberi garis baru (enter) dalam teks tanpa membuat paragraf baru tidak menambahkan jarak atas bawah seperti tag p
br juga bersifat self-closing tag (tidak butuh penutup) teks dipisah tapi jaraknya lebih rapat di banding paragraf



Jadi perbedaan yang mencolok dari kedua tag ini adalah pada jarak yang terbentuk.
Kesimpulannya jika hanya ingin membuat baris baru tanpa jarak gunakan tag br, tapi jika ingin membuat baris baru namun memiliki jarak dengan paragraf diatasnya maka bungkuslah paragraf baru tersebut dengan sepasang tag p dan /p


# 3.  berikut adalah perbedaan atribut alt dan title pada tag img
<img width="1920" height="1080" alt="Screenshot (41)" src="https://github.com/user-attachments/assets/a516263d-0726-4a02-b126-8db796b4aca0" />



berikut adalah contoh dari atribut alt digunakan untuk memberikan teks alternatif jika gambar tidak muncul,
jika gambar tidak muncul akan menampilkan teks logo upb



<img width="1919" height="1079" alt="image" src="https://github.com/user-attachments/assets/c50879fb-ee32-4686-8d4a-87ea1c0843a7" />




berikut adalah contoh dari penggunaan atribut title digunakan untuk Memberikan informasi tambahan dalam bentuk tooltip saat kursor diarahkan ke gambar. Jika mouse diarahkan ke gambar, akan muncul tooltip: “Foto ini diambil di google”.

# 4. fungsi penggunaan atribut widht dan height height Agar tampilan gambar proposional 



<img width="650"  alt="image" src="https://github.com/user-attachments/assets/08123779-8218-466d-a804-c865b6783a3a" />



Supaya gambar tetap proporsional (tidak gepeng atau melebar aneh), sebaiknya cukup isi salah satu atribut saja (width atau height), jangan keduanya sekaligus dengan nilai sembarangan.

seperti pada gambar berikut yang menggunakan salah satu atribut widht saja 
Jika mengisi kedua atribut (width & height):

Browser akan memaksa gambar mengikuti ukuran tersebut.

Jika nilai tidak sesuai aspect ratio asli, gambar akan terlihat terdistorsi (misalnya wajah jadi lonjong atau kotak jadi gepeng).

Jika hanya mengisi salah satu atribut (misalnya width saja):

Browser akan otomatis menyesuaikan atribut lainnya sesuai perbandingan asli gambar.

Hasilnya gambar tetap proporsional.

# Atribut Width
Atribut width pada tabel digunakan untuk menentukan lebar tabel

# Atribut Height
Atribut height pada tabel digunakan untuk menentukan tinggi tabel

<img width="1920" height="1080" alt="Screenshot (46)" src="https://github.com/user-attachments/assets/99369224-ca17-483c-b001-af0749af4c7d" />


Atribut target digunakan untuk menentukan di mana link akan dibuka ketika diklik.

"_blank" → Membuka link di tab/jendela baru.

"_self" → Membuka link di halaman/tab yang sama (ini adalah default).

"_top" → Membuka link di jendela paling atas, biasanya untuk keluar dari iframe.

"_parent" → Membuka link di halaman induk (parent frame), jika tidak ada parent frame maka sama seperti _self.

Jadi, pemilihan nilai target tergantung kebutuhan:

kalau ingin tetap di tab yang sama → pakai _self,

kalau ingin ke tab baru → pakai _blank,

kalau sedang bekerja dengan iframe → gunakan _top atau _parent.






