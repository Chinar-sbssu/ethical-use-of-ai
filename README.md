# The Ethics Lab — GitHub Pages practical handbook

Static classroom site with **12 step-by-step practicals**, a built-in ethics quiz, presenter controls, prompt copy buttons, countdown timers, notes, and a facilitator guide. No framework, build pipeline, external scripts, trackers or paid API keys required.

## Quick start

1. Open `index.html` in your browser, or serve the folder using `python -m http.server 8000`.
2. For GitHub Pages, upload **the contents** of this folder (not the ZIP file) to the root of a public repository on the `main` branch.
3. Under repository **Settings → Pages**, select **Deploy from a branch → main → / (root)**.
4. GitHub Pages serves `index.html` automatically. All links use relative paths and work in project repositories such as `https://username.github.io/repo/`.

## Pages

- `index.html` — main dashboard
- `practical-01.html` through `practical-12.html` — individual labs
- `quiz.html` — offline-capable, self-scoring 8-question ethics quiz
- `facilitator.html` — presenter notes and GitHub Pages instructions
- `tools.html` — free tool directory
- `assets/style.css`, `assets/app.js`, `assets/favicon.svg` — local resources

## Practical guarantees and limitations

- The local HTML, CSS, navigation, copy buttons, timer, quiz and local-storage features are testable without hosting.
- AI model behavior is nondeterministic: no live demonstration can guarantee a hallucination, bias or injection success.
- ChatGPT Free and Duck.ai have usage limits. Google Docs and Forms need a Google account. Google Scholar may link to paywalled articles; search access is free.
- The library/image materials should be checked on the actual Wikimedia Commons file page for source and license.
- Prepared fictional control items are clearly marked. Do not represent them as real scholarly citations or news stories.
- Notes, step checkmarks, and quiz results stay in the local browser; they are not synced across devices.

This material is for educational demonstrations, not legal compliance or a formal bias audit.
