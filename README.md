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

* Two study modes:

  * Kanji → Reading
  * Reading → Kanji
* Meaning can be shown or hidden
* Tracks known and unknown words
* Words marked as unknown are repeated in future rounds
* Displays overall progress and round information
* Unknown words list can be shown or hidden

---

## CSV Input Format

The app accepts a CSV file with **exactly three columns in this order**:

```
kanji, reading, meaning
```

Example:

```
交差点, こうさてん, crossing; intersection
IKE麺, いけめん, the best dad joke
```

> IKE麺 is the name of a restaurant found inside Ikebukuro Station that serves noodle dishes. It is a wordplay on イケメン (good-looking guy), replacing メン with 麺 (noodles). I love it：） 

⚠️ If your data contains commas inside fields, parsing issues may occur.

---

## Intended Use

This tool is built for a **very specific personal workflow** and is not a versatile flashcard system.

That said, I hope to continue improving it over time.

---

