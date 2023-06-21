# LP12DPBO2023C2
LP MVP MVVM


## Janji
Saya Destira Lestari Saraswati dengan NIM 2100506 mengerjakan LP 12 Praktikum DPBO dalam mata kuliah Desain Pemrograman Berorientasi Objek untuk keberkahan-Nya maka saya tidak melakukan kecurangan seperti yang telah dispesifikasikan. Aamiin.

## Requirements Soal
Ubah LP7 menggunakan MVP atau MVVM

## Alasan
Saya memilih menggunakan menggunakan arsitektur MVP karena File LP7 yang di ubah merupakan project kecil, lalu untuk presenter hanya memngelola satu view. Presenter ini memungkinkan untuk mengubah fitur-fitur tanpa mengganggu tampilan atau model yang ada.Karena filenya sedikit jadi saya pikir lebih mudah menggunakan arsitektur MVP gak usah mikirin ViewModelnya gimana. Satu lagi karena saya ingin mencoba menggunakan struktur MVP.


## Perbedaan struktur LP12 dan TMD
Perbedaan jelas pada pemilihan arsitektur antara LP12 dan TMD yang saya kerjakan. Sebelumnya di LP12 ini saya menggunakan arsitektur MVP karena saya nilai cocok untuk project kecil. Tapi setelah saya mengerjakan TMD saya akhirnya menggunakan arsitektur MVVM. Di TMD saya menggunakan struktur berikut:
- Model:
  - Ball
  - Blocks
  - DB
  - Point
- View:
  - Menu
- ViewModel:
  - Handler
  - Controller
  - GameViewModel
  - Game
  - Sound
    
Sedangkan LP12 menggunakan struktur persis yang tertera pada repository ini dengan menggunakan MVP.

Menurut saya untuk game dengan spesifikasi TMD, MVVM lebih cocok, karena pemakaian model lebih mudah digunakan. Pemisahan logika dan proses game lebih terorganisir dengan adanaya ViewModel ini sebagai tempat terpisah logika proses game. 
