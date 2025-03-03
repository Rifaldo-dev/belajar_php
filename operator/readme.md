# Operator dalam PHP

## 1. Pengertian Operator
Operator dalam PHP adalah simbol atau kata kunci yang digunakan untuk melakukan operasi terhadap variabel dan nilai. PHP mendukung berbagai jenis operator yang digunakan dalam perhitungan, logika, dan manipulasi data.

## 2. Jenis-Jenis Operator dalam PHP
### a. Operator Aritmatika
Digunakan untuk melakukan operasi matematika.

| Operator | Keterangan | Contoh |
|----------|-----------|--------|
| `+`  | Penjumlahan | `$a + $b` |
| `-`  | Pengurangan | `$a - $b` |
| `*`  | Perkalian | `$a * $b` |
| `/`  | Pembagian | `$a / $b` |
| `%`  | Modulus (sisa bagi) | `$a % $b` |
| `**` | Pangkat | `$a ** $b` |

**Contoh:**
```php
$a = 10;
$b = 5;
echo $a + $b; // Output: 15
```

### b. Operator Perbandingan
Digunakan untuk membandingkan dua nilai.

| Operator | Keterangan | Contoh |
|----------|-----------|--------|
| `==`  | Sama dengan | `$a == $b` |
| `!=` atau `<>` | Tidak sama dengan | `$a != $b` |
| `>`  | Lebih besar | `$a > $b` |
| `<`  | Lebih kecil | `$a < $b` |
| `>=`  | Lebih besar atau sama | `$a >= $b` |
| `<=`  | Lebih kecil atau sama | `$a <= $b` |
| `===`  | Sama dengan dan tipe data sama | `$a === $b` |
| `!==`  | Tidak sama atau tipe berbeda | `$a !== $b` |

**Contoh:**
```php
$a = 10;
$b = "10";
var_dump($a == $b); // Output: true
var_dump($a === $b); // Output: false
```

### c. Operator Logika
Digunakan untuk operasi logika antara nilai boolean.

| Operator | Keterangan | Contoh |
|----------|-----------|--------|
| `&&` atau `and` | Logika AND | `$a && $b` |
| `||` atau `or` | Logika OR | `$a || $b` |
| `!`  | Negasi (NOT) | `!$a` |
| `xor` | XOR (salah satu harus true, tapi tidak keduanya) | `$a xor $b` |

**Contoh:**
```php
$a = true;
$b = false;
echo ($a && $b); // Output: false
```

### d. Operator Penugasan
Digunakan untuk memberikan nilai ke variabel.

| Operator | Keterangan | Contoh |
|----------|-----------|--------|
| `=`  | Penugasan | `$a = 5` |
| `+=` | Penjumlahan | `$a += 3` (sama dengan `$a = $a + 3`) |
| `-=` | Pengurangan | `$a -= 3` |
| `*=` | Perkalian | `$a *= 3` |
| `/=` | Pembagian | `$a /= 3` |
| `%=` | Modulus | `$a %= 3` |

**Contoh:**
```php
$a = 10;
$a += 5;
echo $a; // Output: 15
```

### e. Operator Increment & Decrement
Digunakan untuk menambah atau mengurangi nilai variabel.

| Operator | Keterangan | Contoh |
|----------|-----------|--------|
| `++$a` | Pre-increment | Tambah 1 sebelum digunakan |
| `$a++` | Post-increment | Tambah 1 setelah digunakan |
| `--$a` | Pre-decrement | Kurangi 1 sebelum digunakan |
| `$a--` | Post-decrement | Kurangi 1 setelah digunakan |

**Contoh:**
```php
$a = 5;
echo ++$a; // Output: 6
```

### f. Operator String
Digunakan untuk menggabungkan string.

| Operator | Keterangan | Contoh |
|----------|-----------|--------|
| `.`  | Penggabungan string | `$a . $b` |
| `.= ` | Penugasan string | `$a .= $b` |

**Contoh:**
```php
$a = "Hello";
$b = " World!";
echo $a . $b; // Output: Hello World!
```

### g. Operator Ternary
Digunakan untuk membuat ekspresi bersyarat dalam satu baris.

**Sintaks:**
```php
$hasil = (kondisi) ? nilai_jika_true : nilai_jika_false;
```

**Contoh:**
```php
$nilai = 80;
$status = ($nilai >= 75) ? "Lulus" : "Tidak Lulus";
echo $status; // Output: Lulus
```

## 3. Kesimpulan
PHP menyediakan berbagai operator untuk manipulasi data, perbandingan, logika, dan lainnya. Memahami cara kerja operator sangat penting dalam pengembangan aplikasi berbasis PHP.

