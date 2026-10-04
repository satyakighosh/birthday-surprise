# ❤️ Birthday Website — Personalization Guide

This is a completely static website. No backend, database, analytics, or external personal-data service is used.

## 1. Photos
Put your six photos in `photos/` and name them:
- photo1.jpg
- photo2.jpg
- photo3.jpg
- photo4.jpg
- photo5.jpg
- photo6.jpg

You can use PNG/WebP too, but then change the filename in `index.html`.

## 2. Personal messages
Open `index.html` in a text editor and search for:
`EDIT HERE`
Then replace the placeholder captions/messages.

## 3. Quiz
Find the `const questions=[...]` section near the bottom and replace the five questions, choices, and correct-answer indexes.

Example:
`c:1` means the second answer is correct because indexes start at 0.

## 4. Voice note
Put your recording at:
`audio/voice.mp3`

If you don't want a voice note, you can remove the audio section from index.html.

## 5. Preview
Double-click `index.html` to preview it in your browser.

## 6. Hosting
For a free public link, GitHub Pages can publish static files from a repository.
Official guide:
https://docs.github.com/en/pages/getting-started-with-github-pages

Important privacy note:
GitHub Pages websites are public on the internet. Do not put anything on a public website that you need to keep genuinely private.
