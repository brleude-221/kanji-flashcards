# Kanji Flashcards

A simple, minimal flashcard web app designed specifically for studying kanji.

Many existing flashcard platforms feel overly complex, and even then, they are not well suited for kanji study, which often requires "three-sided" flashcards with kanji, reading, and meaning.
This project was created to meet that specific need in a straightforward way, with no unnecessary features.

I hope it can be useful.

---

## Live Website

[https://brleude-221.github.io/kanji-flashcards/](https://brleude-221.github.io/kanji-flashcards/)

---

## Features

* CSV files can be loaded directly from the `csv` folder in this directory or from your device.  
  This is a stupid, self-centered design choice, but it’s practical for personal use. I'm sorry for the extra botton. 
* Two study modes:
  * Kanji → Reading
  * Reading → Kanji
* Meaning can be shown or hidden
* Optional example sentences
  * A 4th column may be included in the CSV to contain an example sentence
  * When present, a button is shown to toggle the example sentence display
  * When the Reading → Kanji mode is chosen, the kanji of the word thats being studied is replaced with the reading
* Tracks known and unknown words
  * Unknown words can be saved as a CSV file
  * The filename includes the study set name and the study mode from which the words were extracted
* Words marked as unknown are repeated in future rounds
* Displays overall progress and round information
* Unknown words list can be shown or hidden
* CSV files can be loaded directly from the `csv` folder in this directory.  
  This is admittedly a simple, self-centered design choice, but it’s practical and convenient for personal use.

---

## CSV Input Format

The app accepts a CSV file with **three required columns** and **one optional column**, in the following order:

```
kanji, reading, meaning, example sentence (optional)
```

### Example

```
交差点, こうさてん, crossing; intersection, いつかこの交差点ゲームを絶対に作ってやる。
IKE麺, いけめん, the best dad joke
```

> IKE麺 is the name of a restaurant found inside Ikebukuro Station that serves noodle dishes.
> It is a wordplay on イケメン (good-looking guy), replacing メン with 麺 (noodles). I love it：）

⚠️ If your data contains commas inside fields, there will be parsing issues.

---

## Intended Use

This tool is built for a **very specific personal workflow** and is not a versatile flashcard system.
