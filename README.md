# Praktikum 3: CSS Dasar - Pemrograman Web
Repository ini dibuat untuk menyelesaikan tugas Praktikum 3 Pemrograman Web.

## Identitas Mahasiswa

| Keterangan      | Data                 |
| --------------- | ---------------      |
| **Nama**        | Lia Mulyati          |
| **Kelas**       | I251D                |
| **NIM**         | 312510167		         |
| **Mata Kuliah** | Pemrograman Web      |

### Tujuan Praktikum

Mahasiswa mampu memahami konsep dasar CSS.

Mahasiswa mampu memahami aturan penulisan pada CSS (Internal, Eksternal, dan Inline).

Mahasiswa mampu memahami selector sebagai pengontrol CSS (Elemen, ID, dan Class).

Mahasiswa mampu membuat pengaturan CSS pada HTML.

---

## Struktur Folder Proyek

```
Lab3Web/
├── Lab3_css_dasar.html
├── style_eksternal.css
└── README.md

```
## 1. Struktur File

Struktur file pada praktikum ini adalah sebagai berikut:

<img width="106" height="65" alt="Screenshot 2026-10-08 105657" src="https://github.com/user-attachments/assets/a5f7ddf5-07c9-44ac-b405-6a6f0c08983f" />


## Langkah-langkah Praktikum

### 1. Membuat Dokumen HTML Dasar

Langkah pertama adalah membuat dokumen HTML dasar dengan nama lab2_css_dasar.html. Dokumen ini menggunakan struktur HTML5 yang berisi elemen-elemen seperti header, <nav>, dan <div> untuk menyusun kerangka halaman web.
<img width="628" height="436" alt="image" src="https://github.com/user-attachments/assets/fa275d13-a850-45c2-ac06-a91d616aa9c9" />
<img width="562" height="353" alt="image" src="https://github.com/user-attachments/assets/c0a20cb2-8724-44ae-8cda-cd184f32650b" />



Selanjutnya buka pada brwoser untuk melihat hasilnya.

<img width="462" height="124" alt="Screenshot 2026-10-08 120200" src="https://github.com/user-attachments/assets/d34c0f2c-e049-4a48-860a-0dbea8bb9462" />


### 2. Mendeklarasikan CSS Internal

CSS Internal ditulis di dalam tag <style> yang diletakkan pada bagian <head> dokumen HTML. Pada langkah ini, gaya ditambahkan untuk memodifikasi elemen body, header, dan teks h1.
<img width="401" height="307" alt="image" src="https://github.com/user-attachments/assets/c9529ba0-2b57-448b-881a-7d5a41c21126" />


Selanjutnya simpan perubahan yang ada, dan lakukan refresh pada browser untuk melihat hasilnya.

<img width="464" height="140" alt="Screenshot 2026-10-08 122655" src="https://github.com/user-attachments/assets/31999241-0406-4893-9d87-a08318cf5861" />

### 3. Menambahkan Inline CSS

Inline CSS ditulis langsung di dalam baris tag HTML sebagai atribut style. Pada praktikum ini, inline CSS diterapkan pada tag <p> untuk mengubah perataan teks menjadi ke tengah (center) dan mengubah warna tulisan. Gaya ini hanya berdampak pada satu baris elemen tersebut.

<img width="377" height="17" alt="Screenshot 2026-10-08 122537" src="https://github.com/user-attachments/assets/b9170234-1f39-4382-9327-4c5696e5b72f" />



Selanjutnya simpan perubahan yang ada, dan lakukan refresh pada browser untuk melihat hasilnya.



<img width="473" height="152" alt="Screenshot 2026-10-08 123055" src="https://github.com/user-attachments/assets/883f7d81-93a0-4dba-a754-18e2e135cad4" />

### 4. Membuat CSS Eksternal

CSS Eksternal dipisahkan ke dalam file khusus bernama style_eksternal.css. File ini kemudian dihubungkan ke dokumen HTML menggunakan tag <link rel="stylesheet" href="style_eksternal.css">. Metode ini sangat efisien untuk mengatur gaya di banyak halaman sekaligus.


<img width="221" height="190" alt="image" src="https://github.com/user-attachments/assets/eb26bb39-63e1-4616-a17e-022f82bda63f" />


Kemudian tambahkan tag <link> untuk merujuk file css yang sudah dibuat pada bagian
<head>


<img width="439" height="33" alt="image" src="https://github.com/user-attachments/assets/7cd87b26-b06d-400c-936b-3efa0492aaf7" />



Selanjutnya simpan perubahan yang ada, dan lakukan refresh pada browser untuk melihat hasilnya.


<img width="472" height="173" alt="Screenshot 2026-10-08 124416" src="https://github.com/user-attachments/assets/c5b85cc3-9cc9-4524-86c1-057cd050e419" />


### 5. Menambahkan CSS Selector (ID dan Class)

Selector digunakan untuk memilih secara spesifik elemen mana yang akan diubah gayanya:

ID Selector (#): Diterapkan pada elemen spesifik (contoh: #intro). ID bersifat unik dan hanya boleh digunakan satu kali pada satu halaman.

Class Selector (.): Digunakan untuk mengelompokkan beberapa elemen (contoh: .button). Class bisa digunakan berulang kali pada elemen-elemen yang berbeda.


<img width="255" height="349" alt="image" src="https://github.com/user-attachments/assets/b76bdfa6-346d-4350-bc4e-81534063bf9b" />

Selanjutnya simpan perubahan yang ada, dan lakukan refresh pada browser untuk melihat hasilnya.


<img width="470" height="191" alt="Screenshot 2026-10-08 125454" src="https://github.com/user-attachments/assets/055eb6cd-a162-4fe3-9d3a-356ab8b064e0" />



### 6. Validasi Dokumen CSS (W3C Validator)

Melakukan pengujian kode pada style_eksternal.css menggunakan layanan W3C CSS Validator. Hasil pengecekan menunjukkan pesan "Tidak ditemukan kesalahan", yang berarti kode yang ditulis sudah valid dan sesuai dengan standar web internasional.


<img width="949" height="441" alt="Screenshot 2026-10-08 130658" src="https://github.com/user-attachments/assets/d683e09a-9f68-4716-bd2d-628ff2e94d7b" />
