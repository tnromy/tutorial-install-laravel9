### Tutorial on how to solve errors when installing laravel 9


# step 1
# make sure the server is ready to run the previous version of laravel without problems

# step 2
# clone frash laravel 9

composer create-project --prefer-dist laravel/laravel

# step 3
# install supporting dependencies for laravel9

sudo apt update
sudo apt install php8.1-xml php8.1-mbstring php8.1-curl

wget -O phpunit https://phar.phpunit.de/phpunit-9.phar

# step 4
# grant execution rights to the phpunit file

chmod +x phpunit

# step 5
# move the phpunit file to /usr/local/bin/ so that it can be run from any directory in the program

mv phpunit /usr/local/bin/

# step 6
# continue the installation as usual laravel

laravel cd/
composer update
php artisan key:generate

# step 7
# please try access to localhost in the browser. You will see the default welcome laravel 9.


### Tutorial cara mengatasi error saat install laravel 9


# step 1
# pastikan server sudah siap untuk menjalankan laravel versi sebelumnya tanpa masalah

# step 2
# clone frash laravel 9

composer create-project --prefer-dist laravel/laravel

# step 3
# install dependensi pendukung untuk laravel9

sudo apt update
sudo apt install php8.1-xml php8.1-mbstring php8.1-curl

wget -O phpunit https://phar.phpunit.de/phpunit-9.phar

# step 4
# berikan hak eksekusi pada file phpunit

chmod +x phpunit

# step 5
# pindahkan file phpunit ke /usr/local/bin/ agar bisa dijalankan dari directory manapun di program

mv phpunit /usr/local/bin/

# step 6
# lanjutkan instalasi seperti laravel biasanya

cd laravel/
composer update
php artisan key:generate

# step 7
# silakan dicoba akses ke localhost di browser. Anda akan melihat tampilan default welcome laravel 9.



###

