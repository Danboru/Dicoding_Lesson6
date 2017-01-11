# Dicoding_Lesson6

### Listview dan Gridview

Listview merupakan komponen utama yang dapat menampilkan dan menampung data dalam jumlah yang banyak secara vertical dalam bentuk list yang dapat di-scroll secara vertical. Contoh aplikasi yang menggunakan Listview adalah Whatsapp. Lebih lanjut mengenai Listview dapat dibaca di http://developer.android.com/guide/topics/ui/layout/listview.html

![](https://github.com/Danboru/Dicoding_Lesson6/blob/master/201610191205037505632442d0fae9cd735fb7be165dd5.jpg?raw=true)

Sedangkan gridview merupakan komponen utama yang dapat menampilkan dan menampung data dalam jumlah yang banyak dalam bentuk grid (baris dan kolom). Biasanya implementasinya adalah menampilkan katalog barang pada mobile commerce, gallery Image dsb. Salah satu apps yang memanfaatkan gridview adalah Instagram. Lebih lanjut mengenai Gridview, dapat dibaca pada tautan http://developer.android.com/guide/topics/ui/layout/gridview.html.

![](https://github.com/Danboru/Dicoding_Lesson6/blob/master/20161019120531821701022755be326b45697e2dc2fc84.jpg?raw=true)

Persamaan dua komponen ini adalah untuk menampilkan data kedalam bentuk List dan Grid dibutuhkan Adapter yang berfungsi untuk memproses dan menformat tiap item data dalam GridView atau ListView.

### Adapter

Adapter adalah sebuah mekanisme untuk membinding sekumpulan data, memproses dan memformat tampilan item-item data yang akan ditampilkan melalui listview atau gridview. Lebih lanjut dapat dibaca pada http://developer.android.com/reference/android/widget/Adapter.html.

Android SDK telah menyediakan Adapter bawaan yang secara default dapat digunakan dan dikustomisasi sesuai dengan kebutuhan yang ada. Berikut adalah native adapter yang terdapat didalam Android SDK. 

ArrayAdapter : Adapter yang diperuntukan untuk mem-binding data-data dalam format array.

SimpleCursorAdapter : Adapter yang diperuntukan untuk mem-binding data-data column dalam format objek Cursor (umumnya merupakan hasil nilai balik jika kita melakukan query pada ContentProvider)

Ref : Professional Android 4 Application Development page 156 - 164

Untuk customisasi Adapter dari Stractch bisa menggunakan BaseAdapter : http://developer.android.com/reference/android/widget/BaseAdapter.html
