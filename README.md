# Hungarian Culture Exam Trainer

Unofficial practice app for Hungary's cultural knowledge exam (*magyar kulturális ismereti vizsga*). Third-country nationals need to pass it when applying for a national residence card or an EU residence card (applications submitted on or after 1 January 2025).

**Open the app:** https://yarvalcher.github.io/hungarian-culture-exam-trainer/

## What it does

- **Flashcards** with spaced repetition: 219 exam questions across the six official topics, plus 40 cards of exam Hungarian (question words and instructions).
- **Mock exam** in the official format: 12 questions (2 per topic), 30 points, pass at 16, 60-minute timer. Questions are shown in Hungarian only; each English hint you open is counted.
- **Topic drills**: 6 untimed questions from one topic.
- **Readiness verdict**: shows "Ready" only when (1) the estimated chance of scoring 16+ is at least 95%, from a Beta-binomial model of your auto-graded answers, and (2) your last two mock exams scored 20/30 or more with at most 2 translation hints each.
- **Three translation languages**: English, Українська (Ukrainian) and हिन्दी (Hindi), switched at the top of the page. The Hungarian exam text never changes; the interface, question translations, answer explanations and notes follow the chosen language. Translations live in `lang/uk.js` and `lang/hi.js` and load only when selected. Answers are still typed in Hungarian, as on the real exam.

## Your data

- No account, no analytics, no server-side code. Progress and your language choice are saved in your browser's `localStorage` only.
- Progress does not sync between devices or browsers, and clearing site data erases it.
- Fonts are self-hosted, so the app makes no requests to third-party servers.
- GitHub Pages itself logs visitors' IP addresses for security purposes ([GitHub docs](https://docs.github.com/en/pages/getting-started-with-github-pages/what-is-github-pages)).

## Sources

- [OIF factsheet: Hungarian cultural knowledge exam](https://oif.gov.hu/factsheets/hungarian-cultural-knowledge-exam)
- [BFKH information sheet on the exam (PDF, Hungarian)](https://oif.gov.hu/storage/media/Kultur%C3%A1lis%20Ismereti%20Vizsga/magyar-kulturalis-ismereti-vizsga-tajekoztato.pdf)
- [Official study material, August 2026 version (PDF, Hungarian)](https://oif.gov.hu/storage/media/Kultur%C3%A1lis%20Ismereti%20Vizsga/kiv_segedanyag_bfkh_honlapra_aug.pdf)
- [Fundamental Law of Hungary, English translation](https://www.partylaw.leidenuniv.nl/party-law/51ef8d28-521c-4299-912a-050484e5412d.pdf)

Facts follow the August 2026 study material. Officeholders change, so check them before your exam date. Question wording is the app's own; the real exam words its questions differently.

## Run locally

Open `index.html` in a browser. There is no build step.

## License

The code is MIT-licensed (see `LICENSE`). The fonts are Bricolage Grotesque, Atkinson Hyperlegible Next, Atkinson Hyperlegible Mono, Noto Sans (Cyrillic) and Noto Sans Devanagari, all under the SIL Open Font License 1.1 (see `fonts/`).

Not affiliated with Budapest Főváros Kormányhivatala (BFKH) or the National Directorate-General for Aliens Policing (OIF).
