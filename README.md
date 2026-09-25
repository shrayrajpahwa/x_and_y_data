# x&y data

The data behind every issue of [x&y](https://xandyregression.substack.com), one regression a day.

Browse: https://shrayrajpahwa.github.io/x_and_y_data/

Each issue lives in its own folder, `NNN/`:

| file | what |
|---|---|
| `index.html` | interactive chart: hover any point, toggle the linear to quartic fits, sort and download the data |
| `xy_NNN_data.xlsx` | README sheet (sources, series ids, licences, pull time, every transform), the data used, raw X, raw Y, fits |
| `xy_NNN_data.csv` | the exact rows used in the regression |
| `card.png` | the published image |

## Honesty notes

- Time series report Newey-West (HAC) p-values, because trending monthly data makes ordinary p-values far too small.
- Open sources (FRED, World Bank, Wikimedia) ship the full series as pulled. Third-party sources (Yahoo Finance, Sports Reference and similar) ship only the aggregated values used in the chart, with a link to the source.
- Correlation is not causation.

Data remain the property of their original publishers and are redistributed with attribution where their terms allow.
