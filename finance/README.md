# Pénzügy és kereskedelem (Finance & Trade)

2 datasets — 3,285 records

> Browse at [listbase.org/hu/finance/](https://listbase.org/hu/finance/)

## Datasets

| Name | Records | Size | CSV | Excel | Preview |
|------|---------|------|-----|-------|---------|
| [Kávézók (Cafés)](hu-kavezok.json) | 2,328 | 239 KB | [CSV](hu-kavezok_HU.csv) | [Excel](hu-kavezok_HU.xlsx) | [View](https://listbase.org/hu/finance/hu-kavezok/) |
| [Bankautomaták (ATMs)](hu-bankautomatak.json) | 957 | 93 KB | [CSV](hu-bankautomatak_HU.csv) | [Excel](hu-bankautomatak_HU.xlsx) | [View](https://listbase.org/hu/finance/hu-bankautomatak/) |

## Quick Start

```bash
# List all finance & trade datasets
curl https://cdn.hu.listbase.org/index.json | jq '.datasets[] | select(.category=="finance") | .id'

# Fetch a dataset
curl https://cdn.hu.listbase.org/finance/hu-kavezok.json
```

---

[← Back to all categories](../README.md) · [Browse on ListBase](https://listbase.org/hu/finance/)
