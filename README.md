# Loan EMI Calculator

A free, client-side loan EMI calculator that breaks down your monthly loan repayments — principal, interest, total payment, and an amortization view — with interactive sliders, monthly/yearly breakdowns, PDF download, and share support. No sign-up, everything runs in your browser.

**Live:** https://girishlade111.github.io/loan-emi-calculator-html/

## Features

- **EMI computation** — Enter loan amount, interest rate, and tenure (sliders + inputs); get instant monthly EMI, total interest, and total payable.
- **Monthly / yearly breakdown** — Toggle between monthly and yearly views of the repayment schedule.
- **Amortization insight** — EMI period breakdown showing how each payment splits between principal and interest.
- **Download as PDF** — Export the calculation as a PDF (jsPDF + html2canvas).
- **Share** — Share your calculation via the share modal.
- **Reset** — One-click reset to defaults.
- **100% client-side** — No server, no tracking; your numbers never leave the browser.

## Tech stack

- Single HTML file (inline CSS + vanilla JavaScript)
- jsPDF and html2canvas via CDN (PDF export)

## Quick start

```bash
git clone https://github.com/girishlade111/loan-emi-calculator-html.git
cd loan-emi-calculator-html
# No build step — just open it:
open index.html
```

Works from `file://`; CDN scripts need internet access.

## Project structure

```
index.html                        # Entry point (latest version: share modal + PDF download)
loan-emi-calculator-html.html     # Earlier version
loan-emi-calculator-html (1).html # Source of index.html
README.md                         # This file
LICENSE
```

## Deploy notes

Static site — deployed via **GitHub Pages** from the repo root (`index.html`). Any static host works: upload `index.html` as-is, no build command needed.

## License

MIT — see [LICENSE](./LICENSE).

---

Built by Girish Lade — https://ladestack.in
