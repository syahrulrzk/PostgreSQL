# What are Relational Databases?
Basis data relasional adalah jenis sistem manajemen basis data (DBMS) yang menyimpan dan mengatur data dalam format terstruktur yang disebut tabel. Tabel ini terdiri dari baris, juga dikenal sebagai catatan atau tupel, dan kolom, yang juga disebut atribut atau bidang. Istilah “relasional” berasal dari fakta bahwa tabel-tabel ini dapat dihubungkan satu sama lain melalui kunci dan hubungan.

## Konsep Utama
| Konsep | Description |
| --- | :--- |
| Table | Tabel adalah kumpulan data yang disusun dalam baris dan kolom. Setiap tabel memiliki nama unik dan mewakili objek atau aktivitas tertentu dalam database. |
| Row |  Row adalah entri tunggal dalam tabel, yang berisi contoh data tertentu. Setiap baris dalam tabel memiliki kolom yang sama dan mewakili satu record. |
| Colum | Kolom adalah bidang data dalam tabel, yang mewakili atribut tertentu dari data. Kolom memiliki nama unik dan tipe data tertentu. |
| Primary Key | Kunci utama adalah kolom (atau sekumpulan kolom) dalam tabel yang secara unik mengidentifikasi setiap baris. Tidak ada dua baris yang memiliki nilai kunci utama yang sama. |
| Foreign Key | Kunci asing adalah kolom (atau sekumpulan kolom) dalam tabel yang mengacu pada kunci utama tabel lain. Ini digunakan untuk membangun hubungan antar tabel.

## Relationships
Salah satu keuntungan utama dari database relasional adalah kemampuannya untuk merepresentasikan hubungan antar tabel. Hubungan ini bisa berupa hubungan satu-ke-satu, satu-ke-banyak, atau banyak-ke-banyak. Mereka memungkinkan kueri dan manipulasi data terkait secara efisien di beberapa tabel.

| Relationships | Description |
| --- | :--- |
| One-to-One | Ini adalah hubungan di mana sebuah baris dalam satu tabel memiliki satu baris yang bersesuaian di tabel lain. Misalnya, seseorang dapat memiliki satu paspor, dan satu paspor hanya dapat dimiliki oleh satu orang. |
| One-to-Many | Ini adalah hubungan di mana satu baris dalam satu tabel dapat memiliki beberapa baris yang bersesuaian di tabel lain. Misalnya, seorang pelanggan dapat memiliki beberapa pesanan, namun satu pesanan hanya dapat dimiliki oleh satu pelanggan. |
| Many-to-Many | Ini adalah hubungan di mana beberapa baris dalam satu tabel dapat memiliki beberapa baris yang bersesuaian di tabel lain. Untuk merepresentasikan hubungan banyak ke banyak, diperlukan tabel ketiga yang disebut tabel persimpangan atau tabel asosiatif. Misalnya, seorang siswa dapat mendaftar di beberapa kursus, dan suatu kursus dapat memiliki banyak siswa yang terdaftar. |

