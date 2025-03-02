# **Sintaks Dasar PHP**

## DAFTAR ISI
1. [PENGENALAN PHP](/README.md)
2. [SINTAK DASAR PHP](/sintak_dasar)

Berikut ini merupakan sintak dasar dari bahasa pemgoraman php, yaitu:
```php
<?php 
    echo "Hello, World!";
?>
```
---


- ```<?php```  merupakan tag pembuka
-  ```echo "";``` merupakan sintak untuk menampilkan teks
- ```?>``` merupakan tag penutup.
# **Variabel di PHP**

Variabel di PHP, untuk mendekralasikan variabel pada bahasa pemograman php, itu juga memiliki aturan dalam mendeklarasikan variabel, sebagai berikut:

- Harus diawali dengan $ (misal: $nama).
- Nama variabel harus dimulai dengan huruf atau 
- underscore (_), tidak boleh angka.
- Tidak boleh mengandung spasi, gunakan underscore 
- (_) atau camelCase.
- Bersifat case-sensitive ($nama berbeda dengan $Nama).
## **Contoh Implementasi**
```php
//input
<?php
// Deklarasi variabel dengan berbagai tipe data
$nama = "fulan";  // String
$umur = 45;         // Integer
$tinggi = 1.75;     // Float
$isActive = true;   // Boolean
$hobi = ["Ngoding", "Gaming", "Membaca"]; // Array

// Menampilkan isi variabel
echo "Nama: $nama\n";
echo "Umur: $umur tahun\n";
echo "Tinggi: $tinggi meter\n";
echo "Status Aktif: " . ($isActive ? "Ya" : "Tidak") . "\n";
echo "Hobi: " . implode(", ", $hobi) . "\n";
?>
```
```bash
Output:

Nama: Rifaldo
Umur: 25 tahun
Tinggi: 1.75 meter
Status Aktif: Ya
Hobi: Ngoding, Gaming, Membaca

```


# **Tipe Data dalam PHP**

Berikut merupakan tipe data yang terdapat pada bahasa pemograman php

| **Tipe Data** | **Deskripsi** | **Contoh** |
|--------------|--------------|------------|
| **String** | Teks atau kumpulan karakter dalam tanda kutip. | `$teks = "Hello, World!";` |
| **Integer** | Bilangan bulat (tanpa desimal). | `$angka = 2024;` |
| **Float (Double)** | Bilangan desimal atau pecahan. | `$nilai = 3.14;` |
| **Boolean** | Nilai benar (`true`) atau salah (`false`). | `$is_active = true;` |
| **Array** | Kumpulan nilai dalam satu variabel. | `$hobi = array("Membaca", "Ngoding");` |
| **NULL** | Variabel yang tidak memiliki nilai. | `$data = NULL;` |


## **Contoh Implementasi**

// String
```php
<?php
echo "Tipe Data String: ";
$teks = "Hello, PHP!";
echo $teks . "\n";
?>
```

// Integer
```php
<?php
$angka = 2024;
echo "Tipe Data Integer: " . $angka . "\n";
?>
```
// Float
```php
<?php
>
$nilai = 3.14;
echo "Tipe Data Float: " . $nilai . "\n";
?>
```
// Boolean
```php
<?php 
$is_active = true;
echo "Tipe Data Boolean: " . ($is_active ? "true" : "false") . "\n";
?>
```

// Array
```php
<?php
$hobi = array("Membaca", "Ngoding");
echo "Tipe Data Array: " . implode(", ", $hobi) . "\n";
?>
```

