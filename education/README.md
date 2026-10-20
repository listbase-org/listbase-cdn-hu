# Oktatás (Education)

3 datasets — 5,104 records

> Browse at [listbase.org/hu/education/](https://listbase.org/hu/education/)

## Datasets

| Name | Records | Size | CSV | Excel | Preview |
|------|---------|------|-----|-------|---------|
| [Iskolák (Schools)](hu-iskolak.json) | 3,136 | 405 KB | [CSV](hu-iskolak_HU.csv) | [Excel](hu-iskolak_HU.xlsx) | [View](https://listbase.org/hu/education/hu-iskolak/) |
| [Óvodák (Kindergartens)](hu-ovodak.json) | 1,926 | 218 KB | [CSV](hu-ovodak_HU.csv) | [Excel](hu-ovodak_HU.xlsx) | [View](https://listbase.org/hu/education/hu-ovodak/) |
| [Hungary — Universities (egyetemek)](hu-egyetemek.json) | 42 | 13 KB | [CSV](hu-egyetemek_HU.csv) | [Excel](hu-egyetemek_HU.xlsx) | [View](https://listbase.org/hu/education/hu-egyetemek/) |

## Quick Start

```bash
# List all education datasets
curl https://cdn.hu.listbase.org/index.json | jq '.datasets[] | select(.category=="education") | .id'

# Fetch a dataset
curl https://cdn.hu.listbase.org/education/hu-iskolak.json
```

---

[← Back to all categories](../README.md) · [Browse on ListBase](https://listbase.org/hu/education/)
