# ListBase CDN — Magyar (hu)

Open dataset collection for **Magyar** (Hungarian).
443 datasets across 12 categories with 263,022 total records.

> Browse and download at [https://listbase.org/hu/](https://listbase.org/hu/)

## Categories

| Category | Datasets |
|----------|----------|
| [Kultúra és vallás (Culture & Religion)](culture/) | 7 |
| [Oktatás (Education)](education/) | 3 |
| [Környezet (Environment)](environment/) | 3 |
| [Pénzügy és kereskedelem (Finance & Trade)](finance/) | 2 |
| [Étel (Food & Nutrition)](food/) | 6 |
| [Földrajz (Geography)](geography/) | 221 |
| [Egészség (Health)](health/) | 4 |
| [Politika (Politics)](politics/) | 1 |
| [Referencia (Reference)](reference/) | 162 |
| [Idő és naptár (Time & Calendar)](time/) | 3 |
| [Turizmus (Tourism)](tourism/) | 7 |
| [Közlekedés (Transport)](transport/) | 24 |

## Usage

### Browse on the web
Visit [listbase.org/hu/](https://listbase.org/hu/) to search, preview, and download in Excel, CSV, or PDF.

### Fetch via CDN
```bash
# Dataset index (metadata only)
curl https://cdn.hu.listbase.org/index.json

# Full dataset (JSON)
curl https://cdn.hu.listbase.org/geography/th-central-provinces.json

# Download as Excel or CSV
curl -O https://cdn.hu.listbase.org/geography/th-central-provinces_HU.xlsx
curl -O https://cdn.hu.listbase.org/geography/th-central-provinces_HU.csv

# Build dump (metadata + sample rows, gzipped)
curl https://cdn.hu.listbase.org/dump.json.gz | gunzip
```

### Use in JavaScript
```js
const res = await fetch('https://cdn.hu.listbase.org/geography/th-central-provinces.json');
const data = await res.json();
console.log(data.name);    // "ภาคกลาง — จังหวัดในภาคกลาง"
console.log(data.rows);    // [{ ... }, ...]
```

## File Structure

```
├── index.json              # Dataset index (metadata + file info)
├── dump.json.gz            # Build dump (metadata + 20 sample rows per dataset)
├── {category}/
│   ├── README.md           # Category overview
│   ├── {dataset}.json      # Full dataset with rows
│   ├── {dataset}_HU.csv   # CSV download
│   └── {dataset}_HU.xlsx  # Excel download
```

## Dataset JSON Format

Each `.json` file contains:

| Field | Description |
|-------|-------------|
| `id` | Unique dataset identifier |
| `name` | Dataset name |
| `description` | What this dataset contains |
| `category` | Category (e.g. geography, finance) |
| `source` | Data source attribution |
| `updated` | Last updated date |
| `record_count` | Number of records |
| `columns` | Column definitions (key, label, type) |
| `rows` | Array of data records |

## License

Data is provided under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/).
See individual dataset `source` fields for original data attribution.

---

Part of [ListBase](https://listbase.org) — Free Reference Tables & Lists
