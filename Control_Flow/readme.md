# Control Flow dalam PHP

## 1. Pendahuluan
Control flow adalah cara program mengeksekusi kode berdasarkan kondisi tertentu. PHP menyediakan beberapa struktur kontrol utama:

- **Percabangan (Conditional Statements)**
- **Perulangan (Loops)**
- **Pernyataan Kontrol (Control Statements)**

---

## 2. Percabangan (Conditional Statements)
Percabangan digunakan untuk mengeksekusi kode berdasarkan suatu kondisi.

### 2.1 if Statement
```php
$nilai = 80;
if ($nilai >= 75) {
    echo "Selamat, Anda lulus!";
}
```

### 2.2 if-else Statement
```php
$nilai = 60;
if ($nilai >= 75) {
    echo "Selamat, Anda lulus!";
} else {
    echo "Maaf, Anda tidak lulus.";
}
```

### 2.3 if-elseif-else Statement
```php
$nilai = 85;
if ($nilai >= 90) {
    echo "Nilai Anda A";
} elseif ($nilai >= 75) {
    echo "Nilai Anda B";
} else {
    echo "Nilai Anda C";
}
```

### 2.4 Switch Statement
```php
$hari = "Senin";

switch ($hari) {
    case "Senin":
        echo "Hari ini Senin.";
        break;
    case "Selasa":
        echo "Hari ini Selasa.";
        break;
    default:
        echo "Hari tidak dikenali.";
}
```

---

## 3. Perulangan (Loops)
Loop digunakan untuk menjalankan blok kode berulang kali.

### 3.1 for Loop
```php
for ($i = 1; $i <= 5; $i++) {
    echo "Iterasi ke-$i <br>";
}
```

### 3.2 while Loop
```php
$i = 1;
while ($i <= 5) {
    echo "Iterasi ke-$i <br>";
    $i++;
}
```

### 3.3 do-while Loop
```php
$i = 1;
do {
    echo "Iterasi ke-$i <br>";
    $i++;
} while ($i <= 5);
```

### 3.4 foreach Loop
```php
$buah = ["Apel", "Jeruk", "Mangga"];

foreach ($buah as $item) {
    echo "Buah: $item <br>";
}
```

---

## 4. Pernyataan Kontrol (Control Statements)
### 4.1 break
```php
for ($i = 1; $i <= 5; $i++) {
    if ($i == 3) {
        break;
    }
    echo "Iterasi ke-$i <br>";
}
```

### 4.2 continue
```php
for ($i = 1; $i <= 5; $i++) {
    if ($i == 3) {
        continue;
    }
    echo "Iterasi ke-$i <br>";
}
```

### 4.3 return
```php
function cekUsia($usia) {
    if ($usia < 18) {
        return "Anda belum cukup umur.";
    }
    return "Silakan masuk.";
}

echo cekUsia(16);
```

---

## 5. Kesimpulan
- **Percabangan**: if, if-else, if-elseif-else, switch
- **Perulangan**: for, while, do-while, foreach
- **Pernyataan kontrol**: break, continue, return

Dengan memahami control flow, Anda dapat membuat program yang lebih dinamis dan efisien. 🚀
