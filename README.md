# Sieve Analysis & Fineness Modulus Calculator
**ASTM C33 / C136 — Fine Aggregate Laboratory Report Tool**

A browser-based laboratory calculator for fine aggregate sieve analysis. Enter your retained masses or percentages and get instant gradation curves, fineness modulus, ASTM C33 compliance status, and a print-ready PDF report — all in a single HTML file with zero backend or installation required.

---

## Features

- **Two input modes** — enter % retained directly (Mode A) or mass per sieve (Mode B)
- **Live gradation curve** — Chart.js plot updates in real time as you type, with ASTM C33 conforming zone shaded
- **Fineness Modulus (FM)** — auto-calculated with ASTM C33 range check (2.3–3.1)
- **Grading classification** — Well Graded / Gap Graded / Poorly Graded / Non-Conforming
- **ASTM C33 compliance** — pass/fail status for every sieve
- **Absorption capacity** — enter any two of SSD mass, OD mass, or AC% and the third is auto-filled
- **Particle size parameters** — D10, D30, D60, coefficient of uniformity (Cu), coefficient of curvature (Cc)
- **Print / Save as PDF** — clean white-background report with header, chart, table, and footer
- **No install needed** — single `.html` file, works offline in any modern browser

---

## Screenshots

<img width="689" height="938" alt="Screenshot 2026-06-16 092739" src="https://github.com/user-attachments/assets/486fde15-f9ea-48a1-9db2-a9cedc08a395" />


---

## Usage

1. Download or clone the repository
2. Open `sieve-analysis.html` in any modern browser (Chrome, Firefox, Edge)
3. Fill in the report info (file name, project ID, test date)
4. Enter total sample SSD/OD mass and absorption capacity
5. Choose **Mode A** (% retained) or **Mode B** (mass retained) and fill the sieve table
6. Click **Print / Save as PDF** to export the report

No server, no build step, no npm — just open the file.

---

## Standards Referenced

| Standard | Description |
|---|---|
| ASTM C33 | Specification for Concrete Aggregates (gradation limits for fine aggregate) |
| ASTM C136 | Standard Test Method for Sieve Analysis of Fine and Coarse Aggregates |
| ASTM C128 | Absorption capacity formula: AC = (M_SSD − M_OD) / M_OD × 100 |

---

## Sieve Set (ASTM C33 Fine Aggregate)

`#4 → #8 → #16 → #30 → #50 → #100 → #200 → Pan`

---

## Tech Stack

| Layer | Technology |
|---|---|
| Structure | HTML5 |
| Styling | CSS3 (CSS variables, Grid, Flexbox) |
| Logic | Vanilla JavaScript (ES6+) |
| Chart | [Chart.js 4.4.1](https://www.chartjs.org/) via CDN |
| Fonts | Inter + JetBrains Mono via Google Fonts |

No frameworks. No build tools. No dependencies to install.

---

## File Structure

```
sieve-analysis.html   ← entire app (HTML + CSS + JS in one file)
README.md
```

---

## Author

**MD R Rafi**
Department of Civil Engineering
IUBAT — International University of Business Agriculture and Technology

---

## License

This project is open for academic and educational use.
If you use or adapt it, a credit to the original author is appreciated.
