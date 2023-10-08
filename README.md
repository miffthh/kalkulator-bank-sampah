Kalkulator Bank Sampah

System Requirements
1. PHP Version 8^
2. Laravel 9
3. Template Admin Bootstrap

Fitur apa saja yang tersedia di Kalkulator Bank Sampah

1. Kalkulator Bank Sampah
2. Data User

Instalation
1. git clone https://github.com/miffthh/kalkulator-bank-sampah.git 
2. cd kalkulator-bank-sampah
3. cp .env.example .env
4. Buka .env lalu ubah baris berikut
   DB_PORT=3306
   DB_DATABASE=bank_sampah
   DB_USERNAME=root
   DB_PASSWORD=
5. php artisan key:generate
6. php artisan migrate:fresh --seeder=UserSeeder
7. Jalankan sistem, ketik :
   php artisan serve

catatan :
email : admin@gmail.com
password : admin123
