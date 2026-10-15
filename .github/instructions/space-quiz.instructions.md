---
applyTo: "index.html"
---

# Space quiz (`index.html`)

- This is a standalone, single-page space exploration quiz. Keep it self-contained in `index.html`; it currently uses inline HTML, CSS, and JavaScript and has no build step or external dependencies.
- Preserve the existing quiz flow and behavior: 10 questions, answer feedback and facts, progress and score, results with answer review, and replay.
- Follow the existing visual direction and responsive layout. Preserve dark-mode and reduced-motion support when changing styles or animations.
- Maintain semantic HTML, keyboard focus behavior, accessible labels/status announcements, and safe DOM updates. Prefer `textContent` and DOM methods for dynamic content rather than interpolating untrusted strings into HTML.
- Keep quiz content and UI text consistent with the existing English-language interface. Verify changes by opening `index.html` directly in a browser; do not introduce a server or tooling unless the project requirements change.

