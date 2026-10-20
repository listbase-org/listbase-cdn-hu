# Környezet (Environment)

3 datasets — 3,297 records

> Browse at [listbase.org/hu/environment/](https://listbase.org/hu/environment/)

## Datasets

| Name | Records | Size | CSV | Excel | Preview |
|------|---------|------|-----|-------|---------|
| [Források (Springs)](hu-forrasok.json) | 2,674 | 275 KB | [CSV](hu-forrasok_HU.csv) | [Excel](hu-forrasok_HU.xlsx) | [View](https://listbase.org/hu/environment/hu-forrasok/) |
| [Erőművek Magyarországon](hu-eromuvek.json) | 619 | 314 KB | [CSV](hu-eromuvek_HU.csv) | [Excel](hu-eromuvek_HU.xlsx) | [View](https://listbase.org/hu/environment/hu-eromuvek/) |
| [Atomerőművek Magyarországon](hu-atomeromuvek.json) | 4 | 5 KB | [CSV](hu-atomeromuvek_HU.csv) | [Excel](hu-atomeromuvek_HU.xlsx) | [View](https://listbase.org/hu/environment/hu-atomeromuvek/) |

## Quick Start

```bash
# List all environment datasets
curl https://cdn.hu.listbase.org/index.json | jq '.datasets[] | select(.category=="environment") | .id'

# Fetch a dataset
curl https://cdn.hu.listbase.org/environment/hu-forrasok.json
```

---

[← Back to all categories](../README.md) · [Browse on ListBase](https://listbase.org/hu/environment/)
