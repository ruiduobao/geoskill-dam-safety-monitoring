# Dam Safety Remote Sensing Monitoring (geoskill-dam-safety-monitoring)

> Comprehensive dam safety risk assessment integrating InSAR deformation, water level changes, NDVI anomalies, and thermal infrared seepage

---

## 1. Overview

(Fill in 2-3 paragraphs of Chinese introduction here: features, application scenarios, core algorithms.)

## 3. Quick Start

```bash
pip install -r requirements.txt
python geoskill-dam-safety-monitoring.py --bbox 116 39 117 40 --synthetic --output-dir ./out
```

## 4. CLI Parameters

Run `python <skill>.py --help` for the full list. Common parameters:

| Parameter | Type | Description |
|---|---|---|
| `--bbox` | `float[4]` | WGS84 bounding box `min_lon min_lat max_lon max_lat` |
| `--input` | `path` | Local input file (GeoJSON/GeoTIFF/etc.) |
| `--output-dir` | `path` | Output directory (default `./output`) |
| `--synthetic` | `flag` | Use synthetic data instead of real input |
| `--quiet` | `flag` | Suppress non-essential stdout |

## 5. Input / Output

| File | Format | Description |
|---|---|---|
| `result.tif` | GeoTIFF | Primary output |
| `output-manifest.json` | JSON | Run manifest |

## 6. Technical Principle

(see SKILL.md for details)

## 8. License

MIT License. See [`LICENSE`](./LICENSE) for full text.

---

> 中文完整版：[references/SKILL.zh-CN.md](references/SKILL.zh-CN.md)
