# ujian-n5

Kumpulan 110 soal grammar JLPT N5, 11 part, plus kunci jawaban.

Buka **`quiz.html`** langsung di browser — satu file, tanpa build, tanpa
dependency, tanpa server. Cukup klik dua kali.

## Isi

| File | Keterangan |
|---|---|
| [`quiz.html`](quiz.html) | Kuis interaktif, 110 soal, lengkap dengan romaji, furigana, pembahasan, dan TTS |
| [`Tes Bunpou N5 - semua.md`](Tes%20Bunpou%20N5%20-%20semua.md) | Semua soal dalam markdown, untuk dicetak atau dibaca di mana saja |
| [`KUNCI.txt`](KUNCI.txt) | Kunci jawaban, teks jawaban ditulis penuh |

## Fitur kuis

- 11 part, 10 soal tiap part
- **Furigana** di atas kanji (77 kanji), plus **romaji** untuk seluruh soal
- **Pembahasan** per soal, dikelompokkan per grammar point dan partikel
- **TTS** bahasa Jepang (tombol kecil di sebelah furigana)
- Link ke Google Form asli tiap part
- Tema terang/gelap, progres, filtro salah saja, shortcut keyboard
- Jawaban tersimpan otomatis di `localStorage`
- **Logo hanko** di header: cap 朱文 berisi 文 ("bun" = tulisan/grammar),
  dengan favicon yang sama di tab browser

## Cara pakai

```
quiz.html
```

Buka dua kali. Tidak perlu server, tidak perlu internet (TTS perlu internet).

-shortcut: `1`–`4` pilih jawaban, `Enter` berikutnya, `R` ulangi.

## Catatan

- Kunci jawaban ada di `KUNCI.txt` dan juga tertanam di `quiz.html`, jadi
  file ini cocok untuk belajar, bukan untuk ujianDiam.
- 4 soal dirapikan dari teks form aslinya, karena sumbernya salah ketik:
  1 soal tertukar urutan kata, 2 soal kehilangan tanda baca, 1 soal spasi berlebih.
  Semuanya sudah dicatat sebagai catatan di bawah soal terkait.
- Teks soal di `.md` sengaja dibuat dari sumber data yang sama dengan
  `quiz.html`, jadi keduanya dijamin identik.
