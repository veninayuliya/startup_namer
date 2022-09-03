# startup_namer

Write your first Flutter app, part 1

## 3. Create the starter Flutter app

![3](images/3.jpg)

## 4. Use an external package

Menambahkan package `english_words`

<img src="images/4.1.jpg" width="800">

Menggunakan package `english_words`

Terdapat error

<img src="images/4.2.jpg" width="700">

Setelah diperbaiki

<img src="images/4.3.jpg" width="700">

#### Output

<img src="images/4.4.jpg">

Praktikum ini menggunakan class WordPair dari package `english_words` untuk menampilkan pasangan kata acak dengan properti `asPascalCase` untuk mengkapitalisasikan huruf depan setiap kata

## 5. Add a stateful widget

Menambahkan widget stateful `RandomWords` dan membuat class `_RandomWordsState`.
<img src="images/5.1.jpg" width="700">

Mengubah method `build()` di `_RandomWordsState`.<br>
<img src="images/5.2.jpg" width="700">

Mengubah kode program pada `MyApp`.<br>
<img src="images/5.3.jpg" width="700">

#### Output

![](images/5.4.jpg)

Praktikum ini sama seperti praktikum sebelumnya, akan tetapi disini class `WordPair` dari package `english_words` disimpan di dalam stateful widget `RandomWords`.
