# Étel (Food & Nutrition)

6 datasets — 12,863 records

> Browse at [listbase.org/hu/food/](https://listbase.org/hu/food/)

## Datasets

| Name | Records | Size | CSV | Excel | Preview |
|------|---------|------|-----|-------|---------|
| [Éttermek (Restaurants)](hu-ettermek.json) | 5,957 | 619 KB | [CSV](hu-ettermek_HU.csv) | [Excel](hu-ettermek_HU.xlsx) | [View](https://listbase.org/hu/food/hu-ettermek/) |
| [Gyorséttermek (Fast food)](hu-gyorsettermek.json) | 3,807 | 384 KB | [CSV](hu-gyorsettermek_HU.csv) | [Excel](hu-gyorsettermek_HU.xlsx) | [View](https://listbase.org/hu/food/hu-gyorsettermek/) |
| [Pékségek (Bakeries)](hu-peksegek.json) | 1,877 | 194 KB | [CSV](hu-peksegek_HU.csv) | [Excel](hu-peksegek_HU.xlsx) | [View](https://listbase.org/hu/food/hu-peksegek/) |
| [Fagylaltozók (Ice cream shops)](hu-fagylaltozok.json) | 583 | 61 KB | [CSV](hu-fagylaltozok_HU.csv) | [Excel](hu-fagylaltozok_HU.xlsx) | [View](https://listbase.org/hu/food/hu-fagylaltozok/) |
| [Cukrászdák (Pastry shops)](hu-cukraszdak.json) | 563 | 61 KB | [CSV](hu-cukraszdak_HU.csv) | [Excel](hu-cukraszdak_HU.xlsx) | [View](https://listbase.org/hu/food/hu-cukraszdak/) |
| [Michelin éttermek Magyarországon](hu-michelin-ettermek.json) | 76 | 86 KB | [CSV](hu-michelin-ettermek_HU.csv) | [Excel](hu-michelin-ettermek_HU.xlsx) | [View](https://listbase.org/hu/food/hu-michelin-ettermek/) |

## Quick Start

```bash
# List all food & nutrition datasets
curl https://cdn.hu.listbase.org/index.json | jq '.datasets[] | select(.category=="food") | .id'

# Fetch a dataset
curl https://cdn.hu.listbase.org/food/hu-ettermek.json
```

---

[← Back to all categories](../README.md) · [Browse on ListBase](https://listbase.org/hu/food/)
