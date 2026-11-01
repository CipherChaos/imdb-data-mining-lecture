# imdb-data-mining-lecture

**داده کاوی سینما** — a Data Mining course presentation built on the IMDb Top 1000 Movies dataset (2006–2016).

`imdb-datamining-presentation.html` is a single, self-contained 20-slide deck in Farsi (RTL). All charts are hand-built inline SVG — no chart libraries, no build step — and every number on every slide is computed from the CSV, not hardcoded by hand.

## Pages

| File | Purpose |
| --- | --- |
| `index.html` | Landing page — «مشاهده ارائه» opens the deck, «دانلود ارائه» downloads the PDF |
| `imdb-datamining-presentation.html` | The 20-slide deck (desktop + mobile, RTL keyboard and swipe) |
| `imdb-datamining-presentation.pdf` | 20-page PDF, ready to print or submit |

## Usage

Open `imdb-datamining-presentation.html` in any modern browser. Navigate with the arrow keys (RTL-aware), the dots or the bottom pill; the URL hash tracks the current slide (`#slide-N`).

To export the deck: `Ctrl+P` → *Save as PDF*. The print stylesheet hides all UI and produces exactly 20 pages at 13.333 × 7.5 in.

## Data

| File | Description |
| --- | --- |
| `imdb_movies_cleaned.csv` | Source of truth — 1,000 rows × 12 columns |
| `imdb_movies_featured.csv` | Derived feature set (same 1,000 rows) |
| `imdb_movie_dataset.csv` | Original raw export |

## Contents

1. Cover · 2. Agenda · 3. Why this dataset · 4. Schema · 5. Data quality
6–11. Exploratory analysis (KPIs, rating, runtime, year, genre) · 12–18. Deeper analysis (correlation, skew, top lists) · 19–20. Findings & thanks.

## Presenters

بنیامین کشاورز · ملیکا قصاب‌نژاد · آرین بلندی — استاد: فرزانه استاداکبری
