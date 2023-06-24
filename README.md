# Learn the Basics of Javascirpt Data Type

## Objectives
- ▢ Tipe data ataupun struktur data adalah konsep penting dalam mengkategorisasikan beberapa hal/jenis berbeda pada unit, pengukuran, juga memungkinkan kita untuk beroperasi pada variabel.


## Learnings
### Menampilkan String
```javascript
> var greeting = "Hello, world!";
> console.log(greeting);
```
#### Output: 
```javascript
> Hello, world!
```
### Menampilkan Angka
```javascript
> var num1 = 42;
> var num2 = 3.14;
> console.log(num1);
> console.log(num2);
```
#### Output: 
```javascript
> 42
> 3.14
```

### Menampilkan type boolean
```javascript
> var isTrue = true;
> var isFalse = false;
> console.log(isTrue);
> console.log(isFalse);
```
#### Output: 
```javascript
> true
> false
```

### Menampilkan type boolean
```javascript
> var undefinedVariable;
> var nullVariable = null;
> console.log(undefinedVariable);
> console.log(nullVariable);
```
#### Output: 
```javascript
> undefined
> null
```

### Menampilkan Objek
```javascript
> var person = {
  name: "John",
  age: 25
};
> console.log(person);
```
#### Output: 
```javascript
> { name: 'John', age: 25 }
```


### Menampilkan Array
```javascript
> var numbers = [1, 2, 3, 4];
> console.log(numbers);
```
#### Output: 
```javascript
> [ 1, 2, 3, 4 ]
```

### Menampilkan Hasil dari Fungsi
```javascript
> function add(a, b) {
  return a + b; 
}
>console.log(add(2, 3)); //hasil 5
```

### Menampilkan Tanggal dengan Objek Date
```javascript
> var currentDate = new Date();
> console.log(currentDate); // Sat Jun 25 2023 00:00:00 GMT+0000 (Coordinated Universal Time)
```

## Fork Repository
```
Klik tombol "Fork" di bagian kanan atas halaman repositori.
Pilih akun GitHub Anda untuk membuat fork dari repositori ini.

```
## Clone Repository

```
Buka halaman repositori yang sudah Anda fork di akun GitHub Anda.
Pilih akun GitHub Anda untuk membuat fork dari repositori ini.
Klik tombol "Code" yang berwarna hijau di bagian kanan atas halaman repositori.
Salin URL repositori ke terminal anda dan buka terminal
paste code dengan menambahkan git clone 
example :
git clone git@github.com:usernameanda/repositor.git (yang di copy)

```

## Cara Add, Commit, dan Push Perubahan
1. Buka terminal atau Git Bash di direktori repositori lokal Anda.
2. Buat perubahan yang diperlukan pada proyek Anda.
3. Jalankan perintah berikut untuk menambahkan perubahan ke staging area:

```
git add .
git commit -m "komentar yang akan anda berikan"
git push origin

```
Materi & Referensi tambahan :
- :notebook_with_decorative_cover:
[Belajar javascript di tutorialspoint](https://www.tutorialspoint.com/javascript/index.htm)
- :notebook_with_decorative_cover:
[Belajar javascript di w3schools](www.w3schools.com/js)
- :notebook_with_decorative_cover:
[Belajar javascript dari dasar di Sekolah koding  ](https://app.sko.dev/archived/track/belajar-javascript)