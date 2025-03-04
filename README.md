# PHP Dasar

> Ini merupakan repository belajar php dasar.
# DAFTAR ISI
1. [PENGENALAN PHP](/README.md)
2. [SINTAK DASAR PHP](/sintak_dasar)
3. [OPERATOR PHP](/operator/)

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


# Instalasi PHP
## Untuk menginstall php ada beberapa cara:
1. untuk di windows kita dapat menggunakan software seperti xampp, laragon, apache HTTP web server dan masih banyak lainnya.

<p align="center">
  <img src="https://cdn.simpleicons.org/xampp/FB7A24" height="50" alt="XAMPP">
  <img src="https://cdn.simpleicons.org/laragon/0E83CD" height="50" alt="Laragon">
  <img src="https://cdn.simpleicons.org/apache/CA312D" height="50" alt="Apache">
  <img src="https://cdn.simpleicons.org/nginx/009639" height="50" alt="NGINX">
  <img src="https://cdn.simpleicons.org/docker/2496ED" height="50" alt="Docker">
  <img src="https://cdn.simpleicons.org/kubernetes/326CE5" height="50" alt="Kubernetes">
  <img src="https://cdn.simpleicons.org/caddy/2F9134" height="50" alt="Caddy">
</p>


2. sedangkan di linux seperti ubuntu, debian, dan lain sebagainya itu menggunakan perintah yang diakses di terminal nya.
``` bash
sudo apt install php
```
tetapi jika membutuhkan php-mysql atau php xml, bisa mengunakan perintah berikut ini.
```bash
sudo apt install php-mysql php-xml
```
<p align="center">

<img src="https://cdn.simpleicons.org/debian/debian" height="50" alt="debian">
<img src="https://cdn.simpleicons.org/ubuntu/ubuntu" height="50" alt="ubuntu">
<img src="https://cdn.simpleicons.org/linux/FCC624" height="50" alt="linux">
</p>

# Editor PHP
Berikut software yang dapat digunakan untuk malakukan editasi kode php.

<p align="center">
  <img src="https://cdn.simpleicons.org/visualstudiocode/007ACC" height="50" alt="VS Code">
  <img src="https://cdn.simpleicons.org/vim/019733" height="50" alt="Vim">
  <img src="https://cdn.simpleicons.org/gnu/545454" height="50" alt="GNU Nano">
  <img src="https://cdn.simpleicons.org/sublimetext/FF9800" height="50" alt="Sublime Text">
  <img src="https://cdn.simpleicons.org/phpstorm/000000" height="50" alt="PHPStorm">
  <img src="https://cdn.simpleicons.org/notepadplusplus/90E59A" height="50" alt="Notepad++">
  <img src="https://cdn.simpleicons.org/jetbrains/000000" height="50" alt="JetBrains">
</p>

<hr>