---
name: geoskill-dam-safety-monitoring
description: '融合 InSAR 形变、水位变化、NDVI 异常与热红外渗流的大坝安全综合风险评估'
---

# 大坝安全遥感监测 | Dam Safety Monitoring

(Fill in 2-3 paragraphs of Chinese introduction here: features, application scenarios, core algorithms.)

## Dependencies / 依赖

```bash
pip install 'numpy' 'rasterio' 'scipy' 'geopandas' 'shapely'
```

## Usage / 使用方法

### Basic Usage

```bash
python geoskill-dam-safety-monitoring.py --bbox 116.0 39.0 117.0 40.0 [other parameters]
```

### Example 1 (synthetic data, offline)

```bash
python geoskill-dam-safety-monitoring.py --bbox 116.0 39.0 117.0 40.0 --synthetic --output-dir ./out
```

### Examples 2-5

(Add at least 4 real usage examples.)

## Output / 输出

| File | Format | Description |
|---|---|---|
| `result.tif` | GeoTIFF | Primary output |
| `output-manifest.json` | JSON | Run manifest |

## Data Source / 数据源 / Source

(Describe the data source: free satellite data / local input / synthetic.)

## Privacy / 隐私声明 / Privacy

- Runs offline by default; `--synthetic` mode requires no network at all.
- All processing is done locally; no user data is uploaded.

## License / License

MIT

---

> 中文完整版：需要时再读 [references/SKILL.zh-CN.md](references/SKILL.zh-CN.md)，不要默认全量加载。
