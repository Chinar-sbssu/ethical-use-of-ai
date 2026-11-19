# Quality-check report — The Ethics Lab

## Technical checks performed

- Confirmed all **16 HTML pages** exist: `index.html`, practicals 01–12, quiz, facilitator, and tools directory.
- Parsed each HTML page and verified that every internal relative `href` and asset `src` points to a real file.
- Checked that all twelve practicals have step checklists, at least one copyable exact prompt, at least one free-tool shortcut, a timer, expected observations, a backup plan, and an instructor takeaway.
- Exercised the site's JavaScript in headless Chromium using in-memory HTML, CSS and script injection: search filtering, copy-to-clipboard logic, checklist selection, timer start/reset, reveal-answer, completion state, notes, color theme, stage mode, mobile menu, and all eight quiz questions with scoring/reset.
- Checked responsive rendering at desktop and 390px mobile width, including **no horizontal overflow** on the tested practical.
- No browser JavaScript exceptions occurred in the feature tests.
- Verified GitHub Pages static-site instructions and the existence/free-use descriptions of the principal external tools against official sources on November 19, 2026.

## Honest limits

- The headless-browser environment blocks navigation to both local files and localhost via policy, so the interactions were tested by injecting the pages into the test browser, while relative URLs were checked separately via HTML parsing. A live GitHub Pages deployment was **not** performed.
- External online services can change or impose free-tier rate limits, require a free account, or behave differently. The exercises therefore specify safe fallback examples and do not promise any particular AI error.
- The website does not transmit student notes, quiz scores, or progress to any backend; they use browser local storage. The tools opened externally have their own privacy policies.
- Google Scholar is free to search; reading an individual publisher article may require payment. Prefer freely available abstracts and open-access materials.
- The site's files can be hosted as a static GitHub Pages repository with no server or paid API.
