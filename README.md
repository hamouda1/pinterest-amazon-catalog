# Pinterest Amazon Catalog Database

Curated Amazon product catalogs organized by the **6 active Pinterest accounts** and their verified boards. Each product includes **all available high-resolution image variants** (`MAIN`, `PT01`–`PT08`).

## Accounts & Catalogs

| Account | Boards | Products | File |
|---|---:|---:|---|
| `@marrytreasures` | 23 | 2,241 | `catalogs/marrytreasures.json` |
| `@habiboumez` | 10 | 996 | `catalogs/habiboumez.json` |
| `@anisds1995` | 9 | 898 | `catalogs/anisds1995.json` |
| `@ThePantryHaven` | 6 | 600 | `catalogs/ThePantryHaven.json` |
| `@montessorinest_` | 5 | 487 | `catalogs/montessorinest_.json` |
| `@koreanskincare_finds` | 5 | 467 | `catalogs/koreanskincare_finds.json` |

**Total Unique Products:** 5,663 across 58 niche boards (~3.45 MB total).

## Item Schema

```json
{
  "asin": "B0...",
  "board_id": "...",
  "board_name": "...",
  "title": "...",
  "brand": "...",
  "image_url": "https://m.media-amazon.com/images/I/...",
  "images": ["MAIN", "PT01", "PT02", "..."]
}
```
