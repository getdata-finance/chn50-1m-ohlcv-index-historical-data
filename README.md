# CHN50 1m OHLCV Index Historical Data — Free Sample

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE) [![Dataset rows](https://img.shields.io/badge/full_dataset-2_684_426_rows-blue)](https://getdata.finance/datasets/chn50) [![Updated](https://img.shields.io/badge/weekly_update-every_Saturday_8am_UTC-green)](https://getdata.finance) [![Full data on getdata.finance](https://img.shields.io/badge/download-getdata.finance-orange)](https://getdata.finance/datasets/chn50)

### -> [**Download the full CHN50 dataset on getdata.finance**](https://getdata.finance/datasets/chn50)

**CHN50 1m OHLCV index historical data** — ultra high-quality 1m OHLCV for **FTSE China A50**. Clean `datetime, open, high, low, close, volume` CSV for backtesting, algorithmic trading and quantitative research.

## Table of contents

- [Why this dataset?](#why-this-dataset)
- [Download sample CSV](#download-sample)
- [GitHub Pages preview](#github-pages)
- [Sample vs full dataset](#sample-vs-full-dataset)
- [Timeframes on GetData](#timeframes-on-getdata)
- [Weekly updates](#weekly-updates)
- [Data preview](#data-preview)
- [Schema](#schema)
- [Code examples](#code-examples)
- [Download full data on getdata.finance](#download-full-data-on-getdata)

## Why this dataset?

- **Ultra high-quality 1m OHLCV** for **FTSE China A50** (Index)
- **Clean CSV schema** — `datetime, open, high, low, close, volume` (no gaps in formatting)
- **Free evaluation sample** on GitHub (`1m`) · **11 timeframes** on [getdata.finance](https://getdata.finance/datasets/chn50) · **2,684,426** `1m` rows in the full archive
- Built for **backtesting**, **algorithmic trading** and **quantitative finance** workflows
- **Weekly refresh** — [getdata.finance](https://getdata.finance) every **Saturday, 8am UTC+0**; GitHub `1m` sample updated in sync

> **Sample on GitHub** · `CHN50_1m.csv` (55,440 rows, `2026-06-30` -> `2026-09-04`, 3.92 MB). **Full archive on [getdata.finance](https://getdata.finance/datasets/chn50)** — **2,684,426** `1m` rows (full `1m`: 2,664,006), **11 timeframes**, `2017-07-17` -> `2026-09-04`.

## Download sample

**[CHN50_1m.csv](https://github.com/getdata-finance/chn50-1m-ohlcv-index-historical-data/blob/main/CHN50_1m.csv)** on GitHub ([raw CSV](https://raw.githubusercontent.com/getdata-finance/chn50-1m-ohlcv-index-historical-data/main/CHN50_1m.csv)) · [GitHub Releases](https://github.com/getdata-finance/chn50-1m-ohlcv-index-historical-data/releases)

## GitHub Pages

Interactive chart & stats: **[https://getdata-finance.github.io/chn50-1m-ohlcv-index-historical-data/](https://getdata-finance.github.io/chn50-1m-ohlcv-index-historical-data/)**

Full archive & live chart on getdata.finance: **[https://getdata.finance/datasets/chn50](https://getdata.finance/datasets/chn50)**

## Sample vs full dataset

| | **Sample (this repo)** | **Full dataset ([getdata.finance](https://getdata.finance/datasets/chn50))** |
|---|--:|---|
| Instrument | FTSE China A50 · Index | FTSE China A50 · Index |
| Timeframes | `1m` (sample) | **11** — 1m · 3m · 5m · 15m · 30m · 1H · 4H · 12H · 1D · 3D · 1W |
| 1m rows | 55,440 | **2,684,426** |
| Size | 3.92 MB | full ZIP on [getdata.finance](https://getdata.finance/datasets/chn50) |
| Period | `2026-06-30` -> `2026-09-04` | `2017-07-17` -> `2026-09-04` |
| File | `CHN50_1m.csv` | ZIP on [getdata.finance](https://getdata.finance/datasets/chn50) |
| Coverage report | — | [CHN50 coverage](https://getdata.finance/coverage/chn50) |
| Updates | Weekly (Saturday, 8am UTC+0) — GitHub sample | Weekly (Saturday, 8am UTC+0) — all timeframes |

## Timeframes on GetData

This GitHub repository ships a **`1m` evaluation sample** only. On **[getdata.finance](https://getdata.finance/datasets/chn50)**, each full asset archive is delivered as a ZIP with **11 gap-free OHLCV timeframes** (one CSV per timeframe):

**1m · 3m · 5m · 15m · 30m · 1H · 4H · 12H · 1D · 3D · 1W**

GitHub = `1m` sample · [getdata.finance](https://getdata.finance/datasets/chn50) = all **11** timeframes above for the same instrument.

## Weekly updates

- **[getdata.finance](https://getdata.finance)** — Full datasets are updated every Saturday, 8am UTC+0.
- **GitHub (this repo)** — GitHub samples are refreshed weekly (every Saturday, 8am UTC+0), in sync with getdata.finance.

When a new `1m` sample is published on GitHub, the README, chart preview and CSV reflect the latest week of data.

## Data preview

First and latest rows from the GitHub sample **`CHN50_1m.csv`**:

**First rows**

| datetime | open | high | low | close | volume |
| --- | --- | --- | --- | --- | --- |
| 2026-06-30T19:44:00+00:00 | 15629.41 | 15631.41 | 15629.41 | 15630.92 | 6 |
| 2026-06-30T19:45:00+00:00 | 15630.92 | 15631.93 | 15628.91 | 15629.41 | 20 |
| 2026-06-30T19:46:00+00:00 | 15629.41 | 15630.43 | 15629.41 | 15629.92 | 4 |
| 2026-06-30T19:47:00+00:00 | 15629.92 | 15629.93 | 15628.91 | 15629.41 | 4 |
| 2026-06-30T19:48:00+00:00 | 15629.41 | 15629.93 | 15628.92 | 15629.41 | 6 |

**Last rows**

| datetime | open | high | low | close | volume |
| --- | --- | --- | --- | --- | --- |
| 2026-09-04T20:40:00+00:00 | 14701.59 | 14701.6 | 14701.59 | 14701.59 | 3 |
| 2026-09-04T20:41:00+00:00 | 14701.59 | 14701.59 | 14701.08 | 14701.08 | 1 |
| 2026-09-04T20:42:00+00:00 | 14701.08 | 14702.1 | 14701.08 | 14702.09 | 4 |
| 2026-09-04T20:43:00+00:00 | 14702.09 | 14702.09 | 14702.08 | 14702.08 | 1 |
| 2026-09-04T20:44:00+00:00 | 14702.08 | 14702.09 | 14702.08 | 14702.09 | 1 |

## Schema

| Column | Description |
| --- | --- |
| `datetime` | Bar open timestamp (UTC, ISO-8601). |
| `open` | Opening price of the candlestick bar. |
| `high` | Highest price during the bar. |
| `low` | Lowest price during the bar. |
| `close` | Closing price of the candlestick bar. |
| `volume` | Tick volume (number of price updates) during the bar. |

```text
datetime,open,high,low,close,volume
```

## Code examples

### pandas

```python
import pandas as pd

df = pd.read_csv('CHN50_1m.csv', parse_dates=['datetime'])
df.set_index('datetime', inplace=True)
print(df.describe())
```

### backtrader

```python
import backtrader as bt
import pandas as pd

df = pd.read_csv('CHN50_1m.csv', parse_dates=['datetime'])
df.set_index('datetime', inplace=True)

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

df = pd.read_csv('CHN50_1m.csv', parse_dates=['datetime'])
close = df.set_index('datetime')['close']
fast, slow = vbt.MA.run(close, 10), vbt.MA.run(close, 50)
entries = fast.ma_crossed_above(slow)
exits = fast.ma_crossed_below(slow)
pf = vbt.Portfolio.from_signals(close, entries, exits, init_cash=10_000, freq='1min')
print(pf.stats())
```

## Download full data

The complete **CHN50** archive on **[getdata.finance](https://getdata.finance/datasets/chn50)** includes **11 OHLCV timeframes** (1m · 3m · 5m · 15m · 30m · 1H · 4H · 12H · 1D · 3D · 1W) — **2,684,426** rows at `1m`, plus all other timeframes in the same ZIP.

**[-> Get the full CHN50 dataset on getdata.finance](https://getdata.finance/datasets/chn50)**

---
*GetData · CHN50 1m OHLCV sample on GitHub · Full historical data on [getdata.finance](https://getdata.finance/datasets/chn50)*
