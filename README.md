# Implementasi-Kontrol-Joystick-PS3-pada-Self-Balancing-Robot

Penelitian ini membahas tentang sistem kontrol robot penyeimbang diri dengan menggunakan remote control melalui komunikasi Bluetooth dengan menggunakan metode proportional integral derivative (PID) dan Kalman Filter. Alat yang digunakan pada sistem ini yaitu ESP32, MPU6050, driver motor, stepdown, baterai li-ion, dan motor DC. Sistem ini dapat berjalan berdasarkan inputan sinyal dari sensor MPU6050 yang digunakan untuk mendapatkan nilai setpoint. Jika nilai pembacaan sensor tidak sesuai dengan setpoint, maka robot akan bergerak dan berusaha menyeimbangkan diri. Penambahan Kalman filter digunakan untuk menghilangkan noise pada pembacaan sensor. Hasil pengujian pada robot menunjukkan bahwa jangkauan efektif antara remote control dan robot tanpa adanya obstacle atau rintangan yaitu 8 meter. Sedangkan untuk jangkauan efektif antara remote control dan robot dengan adanya obstacle atau rintangan 7 meter. 

Berikut vidio demo robot dan penjelasannya https://youtu.be/hnWAiaImK-c?si=YOZt5Qgrn8JjibeC
![SELFBAL PS3](https://github.com/user-attachments/assets/39b8acea-a3c8-4d6e-9304-ea03a99a3399)
![Schematic selfbalancing](https://github.com/user-attachments/assets/dc3a5a42-6184-49fd-82c3-10a908029230)
