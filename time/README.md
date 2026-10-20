# Idő és naptár (Time & Calendar)

3 datasets — 1,238 records

> Browse at [listbase.org/hu/time/](https://listbase.org/hu/time/)

## Datasets

| Name | Records | Size | CSV | Excel | Preview |
|------|---------|------|-----|-------|---------|
| [Magyarország ünnepnapjai (1945–2030) — multilingual completos](hu-unnepnapok-completos.json) | 1,068 | 336 KB | [CSV](hu-unnepnapok-completos_HU.csv) | [Excel](hu-unnepnapok-completos_HU.xlsx) | [View](https://listbase.org/hu/time/hu-unnepnapok-completos/) |
| [Magyar állami ünnepnapok (2020–2030) — többnyelvű (HU/DE/EN)](hu-unnepnapok-tobbnyelvu.json) | 121 | 57 KB | [CSV](hu-unnepnapok-tobbnyelvu_HU.csv) | [Excel](hu-unnepnapok-tobbnyelvu_HU.xlsx) | [View](https://listbase.org/hu/time/hu-unnepnapok-tobbnyelvu/) |
| [Magyar iskolai szünetek (2014–2026) — többnyelvű (HU/DE/EN)](hu-iskolai-szunetek.json) | 49 | 23 KB | [CSV](hu-iskolai-szunetek_HU.csv) | [Excel](hu-iskolai-szunetek_HU.xlsx) | [View](https://listbase.org/hu/time/hu-iskolai-szunetek/) |

## Quick Start

```bash
# List all time & calendar datasets
curl https://cdn.hu.listbase.org/index.json | jq '.datasets[] | select(.category=="time") | .id'

# Fetch a dataset
curl https://cdn.hu.listbase.org/time/hu-unnepnapok-completos.json
```

---

[← Back to all categories](../README.md) · [Browse on ListBase](https://listbase.org/hu/time/)
