# Egészség (Health)

4 datasets — 4,602 records

> Browse at [listbase.org/hu/health/](https://listbase.org/hu/health/)

## Datasets

| Name | Records | Size | CSV | Excel | Preview |
|------|---------|------|-----|-------|---------|
| [Gyógyszertárak (Pharmacies)](hu-gyogyszertarak.json) | 1,812 | 194 KB | [CSV](hu-gyogyszertarak_HU.csv) | [Excel](hu-gyogyszertarak_HU.xlsx) | [View](https://listbase.org/hu/health/hu-gyogyszertarak/) |
| [Orvosi rendelők (Doctors’ offices)](hu-orvosi-rendelok.json) | 1,533 | 168 KB | [CSV](hu-orvosi-rendelok_HU.csv) | [Excel](hu-orvosi-rendelok_HU.xlsx) | [View](https://listbase.org/hu/health/hu-orvosi-rendelok/) |
| [Fogorvosok (Dentists)](hu-fogorvosok.json) | 683 | 73 KB | [CSV](hu-fogorvosok_HU.csv) | [Excel](hu-fogorvosok_HU.xlsx) | [View](https://listbase.org/hu/health/hu-fogorvosok/) |
| [Optikák (Opticians)](hu-optikak.json) | 574 | 59 KB | [CSV](hu-optikak_HU.csv) | [Excel](hu-optikak_HU.xlsx) | [View](https://listbase.org/hu/health/hu-optikak/) |

## Quick Start

```bash
# List all health datasets
curl https://cdn.hu.listbase.org/index.json | jq '.datasets[] | select(.category=="health") | .id'

# Fetch a dataset
curl https://cdn.hu.listbase.org/health/hu-gyogyszertarak.json
```

---

[← Back to all categories](../README.md) · [Browse on ListBase](https://listbase.org/hu/health/)
