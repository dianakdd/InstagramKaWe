# InstagramKaWe
![logo](https://github.com/dianakdd/InstagramKaWe/blob/master/ss_ig.png)
## Hal - hal yang harus dilakukan
1. Silahkan clone project dengan perintah `git clone https://github.com/dianakdd/InstagramKaWe.git`
2. Install composer dengan perintah `composer install`
3. Install npm package dengan perintah `npm install`
4. Copy dan edit .env file dari .env.example menjadi ".env"
5. Generate project key dengan perintah `php artisan key:generate`
6. In the .env file, ubah database information `DB_DATABASE=test` serta pastikan di db anda tidak ada database bernama test/isinya kosong
7. Migrate the database dengan perintah `php artisan migrate`
8. Create symbolic link for storage dengan perintah `php artisan storage:link`
9. Run project dengan perintah `php artisan serve`
