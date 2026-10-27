# Flexbox Pricing Table

[![HTML](https://img.shields.io/badge/HTML5-markup-orange.svg)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![CSS](https://img.shields.io/badge/CSS3-layout-blue.svg)](https://developer.mozilla.org/en-US/docs/Web/CSS)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)

A responsive pricing-table practice project built with HTML and CSS. It presents three subscription tiers—Basic, Standard, and Premium—and explores how Flexbox and media queries can arrange pricing cards across different viewport sizes.

## Features

- Three pricing tiers with monthly prices and feature lists.
- Flexbox-based layout in the included reference implementation.
- Media queries intended to adapt the layout for smaller screens.
- Sono typeface loaded from Google Fonts.
- Separate challenge/attempt page and reference solution page.

## Preview Files

- `index.html` — the main project page, with its CSS embedded in a `<style>` element.
- `solution.html` — an alternate/reference implementation, also with embedded CSS.
- `goal-small.png` and `goal-large.png` — reference/goal images included in the repository.

## Run Locally

This is a static front-end project; there is no build step or package installation.

1. Clone or download this repository.
2. Open `index.html` in a modern browser to view the main page.
3. Open `solution.html` separately to compare the alternate implementation.

An editor such as Visual Studio Code can also be used with a local-preview extension.

## Concepts Practiced

- Flexbox containers and card alignment.
- Responsive layout with CSS media queries.
- Spacing, sizing, typography, colors, and rounded corners.
- Semantic HTML elements for plan names, prices, feature lists, and buttons.

## Pricing Plans in the Main Page

| Plan | Price | Included features |
| --- | ---: | --- |
| Basic | $9.99/month | 10GB storage, 1 user, no support |
| Standard | $19.99/month | 50GB storage, 5 users, phone and email support |
| Premium | $49.99/month | 100GB storage, 10 users, 24/7 support |

These are sample values displayed by the page, not purchasable offers.

## Known Limitations and Possible Improvements

- The **Sign Up** buttons are visual only; no links, form handling, or checkout flow is implemented.
- The CSS in `index.html` uses a very large gap and extra right margin at some viewport widths, which may cause awkward spacing or overflow.
- The first responsive media query in `index.html` uses a nested-looking condition that should be simplified and tested across browsers.
- The buttons in `solution.html` open as button elements but use `</a>` closing tags; these should be corrected to valid button closing tags.
- Add document language metadata, a viewport meta tag, and clearer keyboard-focus styling.
- Consider moving the embedded styles into separate CSS files for easier maintenance.

This README records the repository's current structure and observed limitations. The source HTML and CSS have not been changed.

## External Resources and Asset Rights

The page requests the Sono font from Google Fonts. The repository also contains `goal-small.png` and `goal-large.png`; their original source and redistribution terms are not documented here. Verify rights for these assets before redistributing them. This repository's MIT License does not supersede separate third-party licenses or terms.

## License

This project is licensed under the MIT License. See [LICENSE](LICENSE) for the full text.
