# 🌿 Herbal Retrieval System

Mini Project mata kuliah **Information Retrieval**.

## Deskripsi

Project ini merupakan implementasi sederhana sistem pencarian tanaman obat Indonesia menggunakan metode Information Retrieval.

Pengguna memasukkan penyakit atau khasiat, kemudian sistem mencari tanaman obat yang paling relevan menggunakan TF-IDF dan Cosine Similarity.

---

## Metode yang Digunakan

- Text Preprocessing
- Case Folding
- Remove Punctuation
- Tokenization
- Stopword Removal
- TF-IDF
- Cosine Similarity
- Vector Space Model

---

## Dataset

Dataset terdiri dari 10 tanaman obat Indonesia beserta khasiatnya.

Contoh:

| Tanaman | Khasiat |
|----------|----------|
| Jahe | Mengatasi masuk angin, mual, batuk |
| Kunyit | Antiinflamasi, maag |
| Temulawak | Menjaga kesehatan hati |

---

## Library

- pandas
- scikit-learn
- nltk
- re

---

## Cara Menjalankan

1. Buka Google Colab.
2. Upload file `Herbal_Retrieval_System.ipynb`.
3. Jalankan seluruh cell.
4. Masukkan query pencarian.
5. Sistem akan menampilkan tanaman obat yang paling relevan.

---

## Output

Contoh query:

```
batuk
```

Hasil:

```
1. Jahe
2. Kencur
3. Daun Sirih
```

---

## Author

Adhi Prasetyo
