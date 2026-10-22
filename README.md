# VocabVault

**Minimalist Language Vocabulary Builder**

A clean, mobile-first single-page web app for collecting, organizing, and practicing vocabulary across multiple languages.

## Features

- **Add / Edit / Delete** vocabulary items (term, definition, notes)
- **Folder / Category system** — organize words into custom folders (Travel, Verbs, Idioms, etc.)
- **Search** across terms, definitions, and notes
- **Text-to-Speech (TTS)** pronunciation with language selector (EN / JA / KO / ES / FR / ZH)
- **LocalStorage persistence** — your data stays in the browser, no account required
- **Responsive & touch-friendly** UI with smooth animations

## How to Use

1. Open `index.html` in any modern browser (or host it on GitHub Pages / any static host).
2. Tap the **+** button to add a new word.
3. Create folders to group related vocabulary.
4. Use the speaker icon next to any word to hear its pronunciation.
5. Switch the global language in the header to change the default TTS voice.

## Supported Languages (TTS)

| Code   | Language              |
|--------|-----------------------|
| en-US  | English               |
| ja-JP  | Japanese              |
| ko-KR  | Korean                |
| es-ES  | Spanish               |
| fr-FR  | French                |
| zh-TW  | Traditional Chinese   |

## Tech Stack

- Pure HTML + Tailwind CSS (CDN) + Vanilla JavaScript
- Font Awesome icons
- Web Speech API for TTS
- LocalStorage for data persistence

## License

MIT — feel free to use, modify, and share for personal or educational purposes.

---

Made for language learners who prefer a simple, distraction-free vocabulary notebook.
