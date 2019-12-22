# Tunning Database System
Tunnig merupakan salah satu cara pada database system untuk meningkatkan performa kinerja database
Tunning database system dapat dilakukan dengan pendekatan beberapa level:

1. Hardware
2. Sistem Operasi
3. Database Manajement System
4. Schema basis data
5. Indexing
6. Query

Pada praktik ini hanyaakan melakukan tunning pada level Indexing dan Setting Database Manajement System.

## Indexing :cyclone:

"An index for a file in a database system works in much the same way as the index in this textbook. If we want to learn about a particular topic (specified by a word or a phrase) in this textbook, we can search for the topic in the index at the back of the book, find the pages where it occurs, and then read the pages to find the information for which we are looking. The words in the index are in sorted order, making it easy to find the word we want. Moreover, the index is much smaller than the book, further reducing the effort needed."

### :cat:Tools
- Java Programming
- DBMS Seperti Mysql, Postgress, MariaDB dll.

### :hamster:Praktikum

Tujuan
1. Memahami konsep dan cara melakukan tunning dengan indexing dan setting DBMS
2. Mampu membandingkan `response time` sebelum dan sesudah melakukan indexing pada database

Deskripsi
1. Pastikan DBMS sudah terinstall dan sedang dalam keadaan `run`
2. Download Query DDL. [Download DDL](sql/DDL-MySQL.sql)
3. Buat Schema Database. Contoh `DBMS1`
4. Eksekusi SQL pada bagian (2)
5. Download Code dalam bahasa pemrograman Java. [Download Code](sql/tableGen.zip)
6. Compile dan jalan code tersebut pada komputer anda.

```bash
$javac tableGen.java
```

```bash
$java tableGen
```

### :frog:Tahapan percobaan

1. Generate data dengan menjalankan code
2. Lakukan perubahan pada beberapa nilai
3. Hitung response time dari query yang diberikan
4. Lakukan Tunning. Tunning yang dilakukan yaitu tunnig dengan indexing dan setting DBMS. Untuk lebih jelas bisa lihat pada file Tugas.
3. Hitung response time dari query yang diberikan sesudah tunning

### :monkey:Tugas

[Download Tugas](../tugas/laporan.xlsx)
