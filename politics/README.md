# Politika (Politics)

1 datasets — 2,242 records

> Browse at [listbase.org/hu/politics/](https://listbase.org/hu/politics/)

## Datasets

| Name | Records | Size | CSV | Excel | Preview |
|------|---------|------|-----|-------|---------|
| [Városházák (Town halls)](hu-varoshazak.json) | 2,242 | 243 KB | [CSV](hu-varoshazak_HU.csv) | [Excel](hu-varoshazak_HU.xlsx) | [View](https://listbase.org/hu/politics/hu-varoshazak/) |

## Quick Start

```bash
# List all politics datasets
curl https://cdn.hu.listbase.org/index.json | jq '.datasets[] | select(.category=="politics") | .id'

# Fetch a dataset
curl https://cdn.hu.listbase.org/politics/hu-varoshazak.json
```

---

[← Back to all categories](../README.md) · [Browse on ListBase](https://listbase.org/hu/politics/)
