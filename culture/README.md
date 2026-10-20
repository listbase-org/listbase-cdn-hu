# Kultúra és vallás (Culture & Religion)

7 datasets — 13,625 records

> Browse at [listbase.org/hu/culture/](https://listbase.org/hu/culture/)

## Datasets

| Name | Records | Size | CSV | Excel | Preview |
|------|---------|------|-----|-------|---------|
| [Templomok (Places of worship)](hu-templomok.json) | 7,222 | 809 KB | [CSV](hu-templomok_HU.csv) | [Excel](hu-templomok_HU.xlsx) | [View](https://listbase.org/hu/culture/hu-templomok/) |
| [Köztéri alkotások (Public artworks)](hu-kozteri-alkotasok.json) | 2,653 | 272 KB | [CSV](hu-kozteri-alkotasok_HU.csv) | [Excel](hu-kozteri-alkotasok_HU.xlsx) | [View](https://listbase.org/hu/culture/hu-kozteri-alkotasok/) |
| [Útmenti keresztek (Wayside crosses)](hu-utmenti-keresztek.json) | 1,165 | 120 KB | [CSV](hu-utmenti-keresztek_HU.csv) | [Excel](hu-utmenti-keresztek_HU.xlsx) | [View](https://listbase.org/hu/culture/hu-utmenti-keresztek/) |
| [Útmenti szentélyek (Wayside shrines)](hu-utmenti-szentelyek.json) | 1,006 | 102 KB | [CSV](hu-utmenti-szentelyek_HU.csv) | [Excel](hu-utmenti-szentelyek_HU.xlsx) | [View](https://listbase.org/hu/culture/hu-utmenti-szentelyek/) |
| [Múzeumok Magyarországon (Museums in Hungary)](hu-muzeumok.json) | 878 | 187 KB | [CSV](hu-muzeumok_HU.csv) | [Excel](hu-muzeumok_HU.xlsx) | [View](https://listbase.org/hu/culture/hu-muzeumok/) |
| [Könyvtárak (Libraries)](hu-konyvtarak.json) | 693 | 81 KB | [CSV](hu-konyvtarak_HU.csv) | [Excel](hu-konyvtarak_HU.xlsx) | [View](https://listbase.org/hu/culture/hu-konyvtarak/) |
| [Világörökségi helyszínek Magyarországon](hu-vilagorokseg-unesco.json) | 8 | 9 KB | [CSV](hu-vilagorokseg-unesco_HU.csv) | [Excel](hu-vilagorokseg-unesco_HU.xlsx) | [View](https://listbase.org/hu/culture/hu-vilagorokseg-unesco/) |

## Quick Start

```bash
# List all culture & religion datasets
curl https://cdn.hu.listbase.org/index.json | jq '.datasets[] | select(.category=="culture") | .id'

# Fetch a dataset
curl https://cdn.hu.listbase.org/culture/hu-templomok.json
```

---

[← Back to all categories](../README.md) · [Browse on ListBase](https://listbase.org/hu/culture/)
