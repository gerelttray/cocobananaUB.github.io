# Coco Banana — Interactive Digital Menu

**Responsive web experience · Vanilla JavaScript · Bilingual interface**

A mobile-first digital menu concept for a nightlife venue. The project combines product discovery, visual presentation, and lightweight interactions in a single-page website without a frontend framework.

## What it includes

| Feature | Implementation |
| --- | --- |
| Menu browsing | Searchable items and category-based navigation |
| Language options | Mongolian and English content switching |
| Personalization | Choice-based recommendations using mood and preference inputs |
| Interactions | Animated menu components and interactive reward-wheel UI |
| Mobile experience | Responsive layout and touch-friendly controls |
| Technology | HTML, CSS, JavaScript, browser-native APIs |

## Engineering approach

The UI is implemented in a self-contained `index.html` file. It uses JavaScript to filter menu data, switch languages, generate recommendations, and manage interaction states. Styling includes reusable design tokens, responsive layouts, and motion effects.

**Scope note:** This is a client-side website concept. Interactive prize-wheel behavior runs in the browser and is not a server-verified promotional or transaction system. It should not be treated as a production-grade security, payments, or fulfillment implementation.

## Run locally

Open [`index.html`](index.html) in a browser or serve this directory using a local web server:

```bash
npx serve .
```

## Repository contents

- [`index.html`](index.html) — page layout, styles, bilingual content, menu data, and interactions.

---

Designed and developed as an example of interactive, mobile-oriented frontend work.
