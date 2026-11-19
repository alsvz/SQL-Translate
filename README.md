# SQL-Translate
project iseng aja
===========================
# SQL ke Aljabar Relasional

Aplikasi web sederhana untuk mengubah query SQL menjadi ekspresi aljabar relasional dan pohon operator secara langsung di browser.

## Fitur

- Memproses query saat ditulis dan menampilkan ekspresi aljabar relasional beserta pohon operatornya.
- Menyediakan contoh query: dasar, `JOIN`, `GROUP BY`, `UNION`, dan subquery.
- Menyalin hasil ekspresi aljabar ke clipboard.
- Mendukung tampilan terang/gelap mengikuti preferensi sistem.

## Bahasa dan Teknologi

- **HTML5** untuk struktur halaman.
- **CSS3** untuk tampilan dan layout responsif.
- **JavaScript** untuk membaca query, memproses sintaks SQL, dan menampilkan hasil.
- **SQL** adalah bahasa query yang dimasukkan pengguna, bukan bahasa implementasi aplikasinya.

Aplikasi terdiri dari satu file HTML dan tidak memerlukan server, database, atau dependensi tambahan.

## Cara Menjalankan

1. Unduh atau clone repository.
2. Buka `SQL ke Aljabar Relasional.html` langsung di browser modern.
3. Ketik query `SELECT` pada kotak input atau pilih salah satu contoh.

## Sintaks SQL yang Didukung

`SELECT`, `DISTINCT`, `JOIN` (inner, left, right, full, natural, dan cross), `WHERE`, `GROUP BY`, `HAVING`, `ORDER BY`, `LIMIT/OFFSET`, `UNION`, `INTERSECT`, `EXCEPT`, `WITH` (CTE), `CASE`, `CAST`, serta `IN`, `NOT IN`, dan `EXISTS` di `WHERE`.

CTE dan subquery skalar ditampilkan sebagai definisi terpisah. Aplikasi menggunakan bag semantics pada SQL (duplikat dapat muncul), sementara aljabar relasional murni menggunakan set.
>>>>>>> 328fe97 (Initial commit)
