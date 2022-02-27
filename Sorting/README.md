# [SORTING](https://github.com/monicayoshe/Tugas-Algoritma-dan-Struktur-Data-TC122G/tree/main/Sorting)

  - Tujuan utama dari proses sorting adalah mengurutkan data berdasarkan keinginan, sehingga data yang dihasilkan akan lebih terstruktur, teratur dan sesuai dengan kebutuhan.
  - Sorting dapat dilakukan secara ascending (pengurutan nilai dari yang terkecil sampai terbesar) dan descending (pengurutan nilai dari yang terbesar sampai terkecil).
  - Berikut merupakan beberapa metode sorting :

 [1. Bubble Sort](https://github.com/monicayoshe/Tugas-Algoritma-dan-Struktur-Data-TC122G/blob/main/Sorting/Bubble%20Sort_672021032.c)
    <br> ![TEST CASE Bubble Sort](https://user-images.githubusercontent.com/99154617/155891611-97401349-34ad-4bfc-8f93-2b88a6ff7011.PNG)
    <br>↳ Bubble sort mengurutkan data dengan cara membandingkan elemen sekarang dengan elemen berikutnya.
    <br>↳ Jika pengurutan dilakukan secara ascending, ketika elemen sekarang lebih besar dari elemen berikutnya maka kedua elemen tersebut akan ditukar. 
    <br>↳ Ketika satu proses telah selesai, maka bubble sort akan mengulangi proses, demikian seterusnya.
    <br>↳ Bubble sort akan berhenti jika seluruh array telah diperiksa dan tidak ada pertukaran lagi yang bisa dilakukan.
   
 [2. Insertion Sort](https://github.com/monicayoshe/Tugas-Algoritma-dan-Struktur-Data-TC122G/blob/main/Sorting/Insertion%20Sort_672021032.c)
    <br> ![TEST CASE Insertion Sort](https://user-images.githubusercontent.com/99154617/155891658-42f3cc20-f8d5-49fb-a974-090c5032fab9.PNG)
    <br>↳ Algoritma insertion sort merupakan suatu metode pengurutan data dengan melakukan penempatan setiap elemen data pada posisinya dengan membandingkan dengan data-data yang telah ada. 
    <br>↳ Prinsip dari insertion sort adalah dengan membagi data yang akan diurutkan menjadi dua kelompok, satu kelompok yang belum diurutkan dan yang satunya lagi sudah diurutkan.
    <br>↳ Elemen yang pertama diambil dari kelompok list yang belum diurutkan dan kemudian ditempatkan sesuai posisinya pada bagian lain yang belum diurutkan.
 
 [3. Selection Sort](https://github.com/monicayoshe/Tugas-Algoritma-dan-Struktur-Data-TC122G/blob/main/Sorting/Selection%20Sort_672021032.c)
    <br> ![TEST CASE Selection Sort](https://user-images.githubusercontent.com/99154617/155891708-0e958f97-757d-4b65-8e21-2fc45873b723.PNG)
    <br>↳  Algoritma selection sort merupakan pengurutan dengan konsep memilih elemen dengan nilai paling rendah dan menukar elemen tersebut dengan elemen ke –i.
    <br>↳  Nilai dari i dimulai dari 1 ke n, yang dimana n merupakan jumlah total elemen dikurangi satu.
    
    
- [CHALLENGE NIM GENAP! (672021032)](https://github.com/monicayoshe/Tugas-Algoritma-dan-Struktur-Data-TC122G/blob/main/Sorting/Challenge_672021032.c)
<br> ![TEST CASE Challenge](https://user-images.githubusercontent.com/99154617/155891726-85fffa4d-447d-48d2-904c-59f1671bfdd0.PNG)
 1. Analogi algoritma Selection Sort (ascending) :
    <br>↳  Memulai pengecekan data dari data ke 1 hingga data ke n.
    <br>↳  Menentukan bilangan dengan index terkecil dari data pada bilangan tersebut.
    <br>↳  Menukar bilangan index terkecil dengan bilangan pertama.
    <br>↳  Demikian seterusnya hingga seluruh data berhasil diurutkan dari yang terkecil hingga yang terbesar.

 2. Analogi algoritma Insertion Sort (ascending) :
    <br>↳  Membandingkan data kedua dengan data kesatu.
    <br>↳  Apabila data ke dua lebih kecil maka tukar posisinya.
    <br>↳  Data ketiga dibandingkan dengan data kesatu dan kedua.
    <br>↳  Apabila data ketiga lebih kecil tukar lagi posisinya.
    <br>↳  Data keempat dibandingkan dengan data ketiga hingga kesatu.
    <br>↳  Apabila data keempat lebih kecil dari ketiganya maka letakkan data keempat di posisi paling depan.
    <br>↳  Begitu seterusnya hingga tidak ada lagi data yang dapat dipindahkan.
