# utskecerdasanbuatan

rogram ini dirancang untuk membantu dalam mengidentifikasi jenis hama pada tanaman berdasarkan gejala yang muncul. Dengan menggunakan serangkaian aturan logika, program dapat memberikan diagnosis yang sesuai dengan kondisi tanaman.

Alur Pembuatan Program
Definisi Fungsi

Fungsi identifikasi_hama didefinisikan untuk menerima empat parameter boolean yang mencerminkan gejala yang mungkin ada pada tanaman:
daun_menguning
bercak_hitam
daun_berlubang
tanaman_layu
Aturan Diagnosa

Di dalam fungsi, terdapat beberapa aturan yang digunakan untuk mengidentifikasi hama:
Aturan 1: Jika daun_menguning dan bercak_hitam keduanya benar, maka hama yang terdeteksi adalah "Hama Jamur".
Aturan 2: Jika daun_berlubang dan tanaman_layu keduanya benar, maka hama yang terdeteksi adalah "Ulat".
Aturan 3: Jika daun_menguning dan tanaman_layu keduanya benar, maka hama yang terdeteksi adalah "Hama Kutu".
Aturan 4: Jika bercak_hitam dan daun_berlubang keduanya benar, maka hama yang terdeteksi adalah "Hama Kutu Daun".
Aturan 5: Jika tidak ada gejala yang cocok, program akan mengembalikan "Hama tidak dikenali".
Contoh Penggunaan

Sebuah dictionary gejala dibuat untuk merepresentasikan kondisi gejala tanaman.
Fungsi identifikasi_hama dipanggil dengan nilai dari gejala, dan hasil diagnosis disimpan dalam variabel hasil.
Mencetak Hasil Diagnosa

Hasil diagnosa ditampilkan menggunakan print().
Tabel Hasil Diagnosa

Sebuah tabel dibuat dalam bentuk list of lists yang berisi kombinasi gejala dan hama yang mungkin.
Tabel ini dicetak dengan format yang teratur agar mudah dibaca.
