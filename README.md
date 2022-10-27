# FIX Laravel The Stream or File Error

### Translate English: 
> This error occurs when you after uploading laravel project on ubuntu server ( nginx ). You will come across this problem, and the only way to solve this problem is in the following way:

The solution is: 
```
$ cd /path/your_laravel_project
$ sudo chown -R $USER:www-data storage
$ sudo chown -R $USER:www-data bootstrap/cache
$ chmod -R 775 storage
$ chmod -R 775 bootstrap/cache
```

### Translate Indonesia:
> Error ini terjadi ketika anda setelah mengupload project laravel di ubuntu server ( nginx ). kamu akan menemukan masalah ini, dan satu satunya cara untuk menyelesaikan masalah ini adalah dengan cara sebagai berikut:

Solusinya adalah:
```
$ cd /tempat_folder/proyek_laravel_kamu
$ sudo chown -R $USER:www-data storage
$ sudo chown -R $USER:www-data bootstrap/cache
$ chmod -R 775 storage
$ chmod -R 775 bootstrap/cache
```
