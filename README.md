# Mera Ration – Frontend Prototype

A single-page, front-end-only prototype of a citizen-services portal for public distribution (ration card) services. Built with plain HTML, CSS and vanilla JavaScript — no frameworks, no build step, no backend.

> **Disclaimer:** This is a design/learning prototype. It is **not** an official government website and is not affiliated with any government body. All names, numbers, shops and statistics are fictitious. No data is collected or sent anywhere.

## Features

- **Accessibility tools:** text size (A- / A / A+), high-contrast mode, skip-to-content link, keyboard-friendly and screen-reader-friendly markup
- **Bilingual UI:** English / हिन्दी toggle
- **Citizen login (mock):** by ration card number or mobile OTP (demo OTP: `123456`)
- **Dashboard:** digital ration card, monthly entitlement with progress bars, family members with e-KYC status, transaction history, print e-card
- **12 citizen services:** card status, entitlement, apply, add/remove member, portability, find shop, track, grievance, download e-card, transaction history, e-KYC, helpline
- **New ration card application:** 4-step wizard with validation, document upload fields, review and reference number
- **Fair Price Shop locator:** filter by state, name and open/closed status
- **Portability:** generate a demo token to draw ration from a shop in another state
- **Track status:** application and grievance tracking by reference number
- **Grievance form:** with character counter and ticket number
- **FAQs, help chatbot ("Raashan Mitra"), announcements ticker, animated statistics**
- Responsive (mobile → desktop) and print-friendly

## Getting started

1. Download `Mera-Ration.html`.
2. Double-click it to open in any modern browser. That's it.

To host on GitHub Pages:

1. Rename the file to `index.html`.
2. Push it to a GitHub repository.
3. Go to **Settings → Pages**, choose the `main` branch and `/ (root)`, and save.
4. Your site will be live at `https://<your-username>.github.io/<repo-name>/`.

## Demo credentials & test data

| Item | Value |
|---|---|
| Ration card number | any 12-digit number (e.g. `123456789012`) |
| Mobile number | any 10-digit number |
| OTP | `123456` |
| Sample application ID | `MR-2026-1001` |
| Sample grievance ID | `GR-2026-2002` |

## Project structure

```
.
├── Mera-Ration.html   # the entire app (HTML + CSS + JS)
└── README.md
```

## Tech stack

- HTML5, CSS3 (custom properties, grid, flexbox)
- Vanilla JavaScript (ES6)
- `localStorage` for remembering demo application/grievance IDs on the device

## Possible next steps

- Connect to a real backend/API for authentication and data
- Add more regional languages
- Add a map-based shop locator
- Split into components (e.g. React/Vue) and add automated tests
- Run an accessibility audit (WCAG 2.1 AA)

## License

Released for educational use. Add a license of your choice (e.g. MIT) before publishing.
