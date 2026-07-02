# US30 1m OHLCV Index Historical Data — Free Sample

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE) [![Dataset rows](https://img.shields.io/badge/full_dataset-4_904_563_rows-blue)](https://ork.ad/) [![Updated](https://img.shields.io/badge/weekly_update-every_Sunday-green)]() [![Full data on ork.ad](https://img.shields.io/badge/download-ork.ad-orange)](https://ork.ad/)

### → [**Download the full US30 dataset on ork.ad**](https://ork.ad/)

**US30 1m OHLCV Stock index historical data** — ultra high-quality one-minute OHLCV for **Dow Jones 30**. Global cash and extended index sessions — Asia, Europe and US coverage, not US-hours only. Clean `time, open, high, low, close, volume` CSV for backtesting, algorithmic trading and quantitative research.

## Table of contents

- [Why this dataset?](#why-this-dataset)
- [Download sample CSV](#download-sample)
- [GitHub Pages preview](#github-pages)
- [Sample vs full dataset](#sample-vs-full-dataset)
- [Timeframes on ork.ad](#timeframes-on-orkad)
- [Weekly updates](#weekly-updates)
- [Data preview](#data-preview)
- [Schema](#schema)
- [Code examples](#code-examples)
- [Download full data on ork.ad](#download-full-data)

## Why this dataset?

- **Ultra high-quality 1-minute OHLCV** for **Dow Jones 30** (Stock index)
- **Global cash and extended index sessions — Asia, Europe and US coverage, not US-hours only**
- **Clean CSV schema** — `time, open, high, low, close, volume` (no gaps in formatting)
- **Free evaluation sample** on GitHub (`1m` only) · **13 timeframes** on [ork.ad](https://ork.ad/) · **4,904,563** `1m` rows in the full archive
- Built for **backtesting**, **algorithmic trading** and **quantitative finance** workflows
- **Weekly refresh** — [ork.ad](https://ork.ad/) every **Sunday**; GitHub `1m` sample updated in sync

> **Sample on GitHub** · `US30_1m.csv` (175,633 rows, `2025-12-26` → `2026-06-26`). **Full archive on [ork.ad](https://ork.ad/)** — **4,904,563** `1m` rows (~271.88 MB), **13 timeframes** (``1m`, `3m`, `5m`, `15m`, `30m`, `1H`, `2H`, `4H`, `8H`, `12H`, `16H`, `1D`, `1W``), `2011-11-13` → `2026-06-26`.

## Download sample

**[US30_1m.csv](https://github.com/ork-ad/us30-1m-ohlcv-index-historical-data/blob/main/US30_1m.csv)** on GitHub ([raw CSV](https://raw.githubusercontent.com/ork-ad/us30-1m-ohlcv-index-historical-data/main/US30_1m.csv)) · [GitHub Releases](https://github.com/ork-ad/us30-1m-ohlcv-index-historical-data/releases) when the release workflow is active.

## GitHub Pages

Interactive chart & stats: **[https://ork-ad.github.io/us30-1m-ohlcv-index-historical-data/](https://ork-ad.github.io/us30-1m-ohlcv-index-historical-data/)**

## Sample vs full dataset

| | **Sample (this repo)** | **Full dataset ([ork.ad](https://ork.ad/))** |
|---|--:|---|
| Instrument | Dow Jones 30 · Stock index | Dow Jones 30 · Stock index |
| Timeframes | `1m` only (sample) | **13** — `1m`, `3m`, `5m`, `15m`, `30m`, `1H`, `2H`, `4H`, `8H`, `12H`, `16H`, `1D`, `1W` |
| 1m rows | 175,633 | **4,904,563** |
| Size | 10.17 MB | ~271.88 MB |
| Period | `2025-12-26` → `2026-06-26` | `2011-11-13` → `2026-06-26` |
| File | `US30_1m.csv` | ZIP on [ork.ad](https://ork.ad/) |
| Updates | Weekly (Sunday) — GitHub sample | Weekly (Sunday) — all timeframes |

## Timeframes on ork.ad

This GitHub repository ships a **1-minute (`1m`) evaluation sample** only. On **[ork.ad](https://ork.ad/)**, each full asset archive is delivered as a ZIP with **13 gap-free OHLCV timeframes** (one CSV per timeframe):

**1m** · **3m** · **5m** · **15m** · **30m** · **1H** · **2H** · **4H** · **8H** · **12H** · **16H** · **1D** · **1W**

GitHub = `1m` sample · [ork.ad](https://ork.ad/) = all **13** timeframes above for the same instrument.

## Weekly updates

- **[ork.ad](https://ork.ad/)** — Full datasets on ork.ad are updated every Sunday.
- **GitHub (this repo)** — GitHub 1m samples are refreshed weekly (every Sunday), in sync with ork.ad.

When a new `1m` sample is published on GitHub, the README, chart preview and CSV reflect the latest week of data.

## Data preview

First and latest rows from the GitHub sample **`US30_1m.csv`**:

**First rows**

| time | open | high | low | close | volume |
| --- | --- | --- | --- | --- | --- |
| 2025-12-26T20:44:00Z | 48690.85 | 48694.85 | 48684.85 | 48686.35 | 205 |
| 2025-12-26T20:45:00Z | 48686.35 | 48686.85 | 48679.35 | 48681.85 | 254 |
| 2025-12-26T20:46:00Z | 48681.85 | 48686.85 | 48680.85 | 48683.85 | 160 |
| 2025-12-26T20:47:00Z | 48683.85 | 48691.85 | 48682.35 | 48689.85 | 168 |
| 2025-12-26T20:48:00Z | 48689.85 | 48689.85 | 48681.85 | 48685.85 | 225 |

**Last rows**

| time | open | high | low | close | volume |
| --- | --- | --- | --- | --- | --- |
| time | open | high | low | close | volume |
| 2026-06-26T20:40:00Z | 51849.50 | 51851.00 | 51826.00 | 51826.50 | 476.00 |
| 2026-06-26T20:41:00Z | 51826.50 | 51843.50 | 51826.00 | 51830.00 | 524.00 |
| 2026-06-26T20:42:00Z | 51830.00 | 51839.00 | 51822.50 | 51834.50 | 495.00 |
| 2026-06-26T20:43:00Z | 51834.50 | 51853.00 | 51832.50 | 51851.00 | 581.00 |

## Schema

```text
time,open,high,low,close,volume
```

## Code examples

### pandas

```python
import pandas as pd

df = pd.read_csv('US30_1m.csv', parse_dates=['time'])
df.set_index('time', inplace=True)
print(df.describe())
print(df.resample('1h').agg({'open': 'first', 'high': 'max',
                              'low': 'min', 'close': 'last', 'volume': 'sum'}).head())
```

### backtrader

```python
import backtrader as bt
import pandas as pd

df = pd.read_csv('US30_1m.csv', parse_dates=['time'])
df.set_index('time', inplace=True)

class PandasData(bt.feeds.PandasData):
    params = (('datetime', None), ('open', 'open'), ('high', 'high'),
              ('low', 'low'), ('close', 'close'), ('volume', 'volume'))

cerebro = bt.Cerebro()
cerebro.adddata(PandasData(dataname=df))
# cerebro.addstrategy(YourStrategy)
# cerebro.run()
```

### vectorbt

```python
import pandas as pd
import vectorbt as vbt

df = pd.read_csv('US30_1m.csv', parse_dates=['time'])
close = df.set_index('time')['close']
fast, slow = vbt.MA.run(close, 10), vbt.MA.run(close, 50)
entries = fast.ma_crossed_above(slow)
exits = fast.ma_crossed_below(slow)
pf = vbt.Portfolio.from_signals(close, entries, exits, init_cash=10_000, freq='1min')
print(pf.stats())
```

## Download full data

The complete **US30** archive on **[ork.ad](https://ork.ad/)** includes **13 OHLCV timeframes** (`1m`, `3m`, `5m`, `15m`, `30m`, `1H`, `2H`, `4H`, `8H`, `12H`, `16H`, `1D`, `1W`) — **4,904,563** rows at `1m`, plus all higher timeframes in the same ZIP.

**[→ Get the full US30 dataset on ork.ad](https://ork.ad/)**

---
*GetData · US30 1m OHLCV sample on GitHub · Full historical data on [ork.ad](https://ork.ad/) · 2026-07-02 UTC*