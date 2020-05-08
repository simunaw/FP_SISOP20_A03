# FP_SISOP20_A03

Menggunakan command 

1. sort

Mengurutkan file()

Contoh : output akan diprint di terminal kecuali -o

sort input.txt (mengurutkan file secara asc)

sort -o output.txt input.txt (Memasukkan hasil output kedalam file output.txt)  

sort -r input.txt (mengurutkan file secara desc)

sort -n input.txt (Mengurutkan file numerik)

sort -k2 input.txt (mengurutkan berdasarkan kolom 2)

sort -c (Mengecek apakah file sudah terurut, jika sudah tidak mengeluarkan output)

sort -u (mengurutkan dan menghapus jika ada duplikasi)

sort -M input.txt (mengurutkan berdasarkan bulan) 
.

2. Date


Command date berguna untuk menampilkan date(tanggal, bulan, tahun) atau time (jam, menit, detik)

Contoh: 

date

date + “%d-%m-%y”

date -s “month/day/year HH:MM:SS”

date -r “nama_file” 




