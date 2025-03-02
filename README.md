# PHP Dasar

> Ini merupakan repository belajar php dasar.
# DAFTAR ISI
1. [PENGENALAN PHP](/README.md)
2. [SINTAK DASAR PHP](/sintak_dasar)

# Apa itu PHP
![php](https://upload.wikimedia.org/wikipedia/commons/thumb/2/27/PHP-logo.svg/500px-PHP-logo.svg.png)

PHP adalah Hypertext Preprocessor yang dimana sebelumnya dikenal sebagai Personal Home Pages, PHP pertama kali dikembangkan oleh Rasmus Lerdorf pada tahun 1994. PHP merupakan bahasa scripting yang berjalan di server-side, yang dapat disisipkan ke dalam HTML. PHP banyak digunakan untuk mengembangkan website yang dinamis, seperti forum, blog, dan e-commerce.

# **Keunggulan Belajar PHP** 
1. Mudah dipahami
2. Kompitibel dengan banyak database
3. Web yang dihasilkan dinamis
4. Sangat banyak digunakan oleh sistem pemerintahan, pendidikan hingga kesehatan yang ada di indonesia ini
5. Hosting murah dan mudah
6. Kompatibel dengan banyak database


# **Cara Kerja dari PHP**
![cara kerja php](https://blogger.googleusercontent.com/img/b/R29vZ2xl/AVvXsEgtMvKf-bfaWftXSE0B21taMz2tIGqO3cnwpGAC1CkVONSpEE_GwfMghFfgXeLBhWKaD3UKuF32L5S9KTfnhUM5HncqRZSm_X8tuaCp732YRX6GSJtGjOwDpOtd3INiy7eqmPyro2STllY/s1600/cara-kerja-php.jpg)

1. User malakukan request di
> user mengakses domain web, lalu browser akan melakukan request HTTP ke web server.
2. web server akan memproses
> Web server akan menerima request HTTP, lalu setelah itu web server akan membaca kode yang ada di file php.
3. PHP akan mengeksekusi kode

 Misal di file index.php terdapat kode senagai berikut:
```php
<HTML>
<?PHP 
  echo "<B>Hello</B>"; 
?>
</HTML>
```
php tidak akan mengirimkan hasil yang sama, tetapi php akan memberikan kode 
```html
<HTML>
<B>Hello</B>
</HTML>
```

5. Browser akan menampilkan hello di halaman user.
---


# Intalasi PHP
## Untuk menginstall php ada beberapa cara:
1. untuk di windows kita dapat menggunakan software seperti xampp, laragon, apache HTTP web server dan masih banyak lainnya.
2. sedangkan di linux seperti ubuntu, debian, dan lain sebagainya itu menggunakan perintah yang diakses di terminal nya.
``` bash
sudo apt install php
```
tetapi jika membutuhkan php-mysql atau php xml, bisa mengunakan perintah berikut ini.
```bash
sudo apt install php-mysql php-xml
```







