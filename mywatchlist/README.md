Jelaskan perbedaan antara JSON, XML, dan HTML!
- JSON (JavaScript Object Notation) adalah turunan dari JavaScript yang digunakan dalam penyimpanan dan pengiriman data.
JSON didesain menjadi ***self-describing***, sehingga JSON sangat mudah untuk dimengerti.
Format JSON berbentuk text, sehingga kode untuk membaca dan membuat JSON banyak terdapat di berbagai bahasa pemrograman.
- XML (eXtensible Markup Language) adalah bahasa komputer untuk menyederhanakan proses pertukaran dan penyimpanan data.
XML didesain menjadi ***self-descriptive***, sehingga dengan membaca XML tersebut, mudah mengerti informasi yang ingin disampaikan data yang tertulis.
XML hanyalah informasi yang dibungkus di dalam tag, tidak perlu program untuk mengirim, menerima, menyimpan, atau menampilkan informasi tersebut.
- HTML (Hyper Text Markup Language) adalah bahasa markup standar untuk mendefinisikan struktur dari sebuah halaman web.
HTML berisi macam-macam elemen yang akan menyampaikan informasi cara untuk menampilkan konten kepada browser.
HTML umum digunakan untuk menyusun bagian paragraf, heading, maupun ***link*** pada halaman web.

Jelaskan mengapa kita memerlukan data delivery dalam pengimplementasian sebuah platform?
Data delivery penting dalam pengimplementasian sebuah platform karena data perlu dikirim satu ***stack*** ke ***stack*** lainnya. Dalam beberapa kasus, data yang diterima atau dikirim berbeda-beda, sehingga perlu metode data delivery untuk menyesuaikannya. Selain itu, bisa jadi ada berkas yang tidak disimpan di ***server***, tetapi dihasilkan oleh kode program.

Jelaskan bagaimana cara kamu mengimplementasikan checklist di atas.
- Membuat folder baru bernama mywatchlist di dalam folder tugas2
- Mengimplementasikan models,py, views.py, dan urls.py pada folder mywatchlist
- Menambahkan path mywatchlist
- Membuat file initial_mywatchlist_data.json dan memasukkan 10 data
- Membuat folder templates dan file .html di dalamnya
- Melakukan makemigrations dan migrate
- Melakukan runserver
- Melakukan push ke akun GitHub
- Mengecek deployment terhadap aplikasi mywatchlist di Heroku 
- Mengisi file tests.py kemudian test tiga URL untuk memastikan dapat URL mengembalikan respon HTTP 200 OK

Akses URL menggunakan Postman
- JSON
<img width="960" alt="2022-09-22 (5)" src="https://user-images.githubusercontent.com/112617861/191643334-e56ecb33-ea69-4f3a-ab5e-35ae62d8039a.png">
- XML
<img width="960" alt="2022-09-22 (6)" src="https://user-images.githubusercontent.com/112617861/191643071-b9eb2e0b-1599-45ec-b6b5-17fe1075c123.png">
- HTML
<img width="960" alt="2022-09-22 (1)" src="https://user-images.githubusercontent.com/112617861/191643409-3ed0f1ed-f0e0-4045-ab79-c44a2a9f15b8.png">