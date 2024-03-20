## Konfigurasi Clone Github Laravel
- Klik tombol "Code" (berwarna hijau) untuk mendapatkan URL repository. Jika menggunakan HTTPS, salin URL tersebut. Jika menggunakan SSH, klik ikon SSH dan salin URL SSH.
- Buka terminal, command prompt atau Git Bash(rekomendasi) di komputer Anda.
- #### Ketikan perintah
      git clone [URL yang dicopy tadi]

  
## Setelah selesai melakukan Cloning lanjutkan perintah
    composer install
### lalu

    npm install
### lalu
    cp .env.example .env

### lalu
    php artisan key:generate


## Cara Menjalankan
### Buka Terminal Baru
    php artisan serve
### Buka Terminal Baru Lagi
     npm run dev
