Kelompok B5

Najwan Wi'am Asroshan    (2309106107)  Ketua
Muhammad Annur Akbar     (2309106110)
Nelsi                    (2309106120)
Erza Nadifa              (2309106093)

Judul: Sistem Smart Flood Dan Environment Monitoring Berbasis MQTT Dan Telegram Bot

Deskripsi: Sistem ini merupakan sebuah prototype IoT Pendeteksi Banjir Berbasis ESP32 yang digunakan untuk memantau kondisi hujan dan ketinggian air secara realtime. Sistem memanfaatkan ESP32 DevKit V1 sebagai mikrokontroler utama yang terhubung dengan dua sensor, yaitu Water Rain Sensor Module dan Water Level Sensor.

Rain sensor berfungsi untuk mendeteksi terjadinya hujan sebagai peringatan awal atau early warning system. Ketika sensor mendeteksi adanya air hujan, sistem akan secara otomatis mengirimkan notifikasi melalui Telegram Messenger dengan pesan bahwa hujan sedang terjadi. Fungsi ini bertujuan untuk memberikan informasi awal sebelum kemungkinan terjadinya banjir.

Selain itu, water level sensor digunakan untuk membaca ketinggian permukaan air. Berdasarkan nilai yang dibaca sensor, sistem akan membagi kondisi air menjadi beberapa status yaitu aman, waspada, dan bahaya banjir. Jika kondisi masih aman, sistem hanya menampilkan status pada dashboard. Ketika level air mulai meningkat, sistem akan mengirimkan notifikasi peringatan melalui Telegram. Sedangkan saat level air mencapai kondisi bahaya, sistem akan mengaktifkan buzzer sebagai alarm lokal dan mengirimkan notifikasi bahaya banjir secara otomatis.

Data hasil pembacaan sensor akan ditampilkan secara realtime pada dashboard web Blynk Cloud sehingga pengguna dapat melakukan monitoring melalui browser pada laptop atau komputer tanpa perlu menggunakan aplikasi smartphone. Dashboard menampilkan nilai rain sensor, nilai water level, serta status kondisi banjir secara langsung.

Dengan adanya sistem ini, pengguna dapat memantau kondisi lingkungan secara realtime dan memperoleh informasi lebih cepat terkait potensi banjir. Sistem ini diharapkan dapat membantu dalam memberikan peringatan dini banjir berbasis Internet of Things (IoT) secara sederhana namun efektif.


Pembagian Tugass: Wi'am : Kodingan,Blink  Akbar:Rakit,Boot Telegram,   Nelsi: Merakit, penyusunan dan pengemasan file ZIP untuk kebutuhan tampilan antarmuka sistem.     Erza:Membuat Gambar Skematik, Dan Laporan

Komponen Yang di gunakan:
ESP32
Rain Sensor
Water Level Sensor
Buzzer
Breadboard
Kabel Jumper
Kabel USB
Blynk Web
Telegram Bot
Arduino IDE


