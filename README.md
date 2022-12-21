<h2> Struktur Data </h2>
<h3> Stack </h3>
Stack adalah suatu struktur data yang terbentuk dari barisan hingga yang terurut dari satuan data. Karakteristik dari stack sendiri
bersifat LIFO (<i>Last In First Out</i>), artinya data yang terakhir merupakan data yang akan keluar terlebih dahulu. Misalnya seperti
tumpukan buku. Buku yang pertama berada dalam tumpukan adalah buku yang akan terakhir dikeluarkan. 
<br>

Terdapat dua operasi dasar dalam Stack, yaitu push dan pop. <br>
- Push, digunakan untuk memasukkan data ke dalam Stack <br>
- Pop, digunakan untuk mengeluarkan data dari Stack 

Penyisipan dan penghapusan data terjadi di satu ujung, yaitu dari atas tumpukan. Apabila ruang memori sudah penuh, namun masih dilakukan
operasi penyisipan elemen, maka akan terjadi <i>stack overflow</i>. Apabila struktur data kosong, namun tetap dilakukan operasi penghapusan, 
maka akan terjadi <i>stack underflow</i>

<h3> Queue </h3>
Queue adalah struktur data yang menerapkan konsep FIFO (<i>first In First Out</i>, artinya data yang diinput di awal akan menjadi data yang 
pertama kali dikeluarkan. Berbeda dengan stack, queue disusun secara horizontal dan terbuka di kedua ujungnya. Ujung pertama (<i>head</i>) 
digunakan untuk menghapus data, sedangkan ujung lainnya (<i>tail</i>) untuk menyisipkan data.
<br>

Ada beberapa operasi dasar dalam queue, di antaranya <br>
- Enqueue, menambahkan elemen ke akhir antrian <br>
- Dequeue, menghapus elemen dari depan antrian <br>
- IsEmpty, memeriksa apakah antrian kosong <br>
- IsFull, memeriksa apakah antrian penuh <br>
- Peek, mendapatkan nilai bagian depan antrian tanpa menghapusnya
