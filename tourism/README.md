# Turizmus (Tourism)

7 datasets — 18,283 records

> Browse at [listbase.org/hu/tourism/](https://listbase.org/hu/tourism/)

## Datasets

| Name | Records | Size | CSV | Excel | Preview |
|------|---------|------|-----|-------|---------|
| [Turistainformációs pontok (Tourist information points)](hu-turistainformacios-pontok.json) | 9,365 | 1022 KB | [CSV](hu-turistainformacios-pontok_HU.csv) | [Excel](hu-turistainformacios-pontok_HU.xlsx) | [View](https://listbase.org/hu/tourism/hu-turistainformacios-pontok/) |
| [Panziók (Guest houses)](hu-panziok.json) | 3,253 | 345 KB | [CSV](hu-panziok_HU.csv) | [Excel](hu-panziok_HU.xlsx) | [View](https://listbase.org/hu/tourism/hu-panziok/) |
| [Látnivalók (Tourist attractions)](hu-latnivalok.json) | 2,046 | 216 KB | [CSV](hu-latnivalok_HU.csv) | [Excel](hu-latnivalok_HU.xlsx) | [View](https://listbase.org/hu/tourism/hu-latnivalok/) |
| [Szállodák (Hotels)](hu-szallodak.json) | 1,580 | 167 KB | [CSV](hu-szallodak_HU.csv) | [Excel](hu-szallodak_HU.xlsx) | [View](https://listbase.org/hu/tourism/hu-szallodak/) |
| [Kilátók (Viewpoints)](hu-kilatok.json) | 819 | 90 KB | [CSV](hu-kilatok_HU.csv) | [Excel](hu-kilatok_HU.xlsx) | [View](https://listbase.org/hu/tourism/hu-kilatok/) |
| [Apartmanok (Tourist apartments)](hu-turista-apartmanok.json) | 713 | 76 KB | [CSV](hu-turista-apartmanok_HU.csv) | [Excel](hu-turista-apartmanok_HU.xlsx) | [View](https://listbase.org/hu/tourism/hu-turista-apartmanok/) |
| [Kempingek (Campsites)](hu-kempingek.json) | 507 | 56 KB | [CSV](hu-kempingek_HU.csv) | [Excel](hu-kempingek_HU.xlsx) | [View](https://listbase.org/hu/tourism/hu-kempingek/) |

## Quick Start

```bash
# List all tourism datasets
curl https://cdn.hu.listbase.org/index.json | jq '.datasets[] | select(.category=="tourism") | .id'

# Fetch a dataset
curl https://cdn.hu.listbase.org/tourism/hu-turistainformacios-pontok.json
```

---

[← Back to all categories](../README.md) · [Browse on ListBase](https://listbase.org/hu/tourism/)
