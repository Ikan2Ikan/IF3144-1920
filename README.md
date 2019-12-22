# Praktikum Database Manajement System :custard:
Review konsep Database manajement system dengan Praktik

- Praktikum 1: [Tunning](tunning/README.md)

Dino Febriyanto 14117124

================Tunning Index================

Untuk Tunning Index saya menambahkan kolom "tot_cred" pada
table "student" kedalam index. Hasilnya tidak terlalu signifikan
dikarenakan memang kondisi database yang dihasilkan oleh
file "tableGen.java" sudah diindexing.



================Tunning DBMS================

Untuk Tunning DBMS saya menggunakan Buffer Pool dan Query Cache.
Buffer Poolnya saya besarkan ukurannya menjadi 3 GigaByte. Lalu
saya menambahkan query cache sebesesar 268435456. Fungsi
Query Cache sendiri adalah membuat query yang sudah pernah
dipanggil disimpan dalam memory cache, jadi ketika query dipanggil
lagi, maka dbms akan mencari di cache apakah query sudah pernah diexecute
Jika pernah maka dbms tidak akan melakukan pencarian dalam database
melainkan hanya menampilkan hasil yang ada di cache. Dan Tunning ini
terbukti ampuh dengan perolehan waktu execute yang berbeda sangat jauh.
