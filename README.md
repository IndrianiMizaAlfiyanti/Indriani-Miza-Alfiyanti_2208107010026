Cara menjalankan program:
- Pastikan sudah memiliki compiler C seperti GCC yang terpasang di sistem.
- Salin code program dalam file dengan ekstensi "c", misalnya "sorting_program".
- Buka terminal atau command prompt, lalu arahkan ke direktori tempat anda menyimpan file "c" tersebut.
- Compile kode program dengan perintah " gcc -o sorting_program sorting_program.c"
- Setelah berhasil dikompilasi, jalankan program dengan perintah "./sorting_program"

Setelah dijalankan, program akan menampilkan hasil pengukuran waktu eksekusi untuk masing-masing algoritma pengurutan (bubble sort, selection sort, dan insertion sort) dengan jumlah bilangan acak yang berbeda-beda. Hasilnya akan ditampilkan dalam format yang terstruktur dengan tiga kolom: jenis algoritma, jumlah bilangan, dan waktu eksekusi dalam milidetik (ms).

Fungsi-sungsi yang digunakan dalam code program:
- generateNumbers: Menghasilkan bilangan acak dalam array.
- bubbleSort: Melakukan pengurutan array menggunakan algoritma bubble sort.
- selectionSort: Melakukan pengurutan array menggunakan algoritma selection sort.
- insertionSort: Melakukan pengurutan array menggunakan algoritma insertion sort.
- writeUnsortedToFile: Menulis array bilangan acak ke dalam file sebelum diurutkan.
- writeSortedToFile: Menulis array bilangan yang sudah diurutkan ke dalam file.
- main: Fungsi utama yang mengatur proses pengukuran waktu eksekusi untuk ketiga algoritma pengurutan dan menulis hasilnya ke dalam file.
- 
Semua operasi I/O file menggunakan standar C dan menggunakan fungsi FILE dari pustaka standar C.
