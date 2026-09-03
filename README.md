# CHN50 1m OHLCV Index Historical Data — Free Sample

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE) [![Dataset rows](https://img.shields.io/badge/full_dataset-2_681_069_rows-blue)](https://getdata.finance/datasets/chn50) [![Updated](https://img.shields.io/badge/weekly_update-every_Saturday_8am_UTC-green)](https://getdata.finance) [![Full data on getdata.finance](https://img.shields.io/badge/download-getdata.finance-orange)](https://getdata.finance/datasets/chn50)

### -> [**Download the full CHN50 dataset on getdata.finance**](https://getdata.finance/datasets/chn50)

**CHN50 1m OHLCV index historical data** — ultra high-quality 1m OHLCV for **FTSE China A50**. Clean `time, open, high, low, close, volume` CSV for backtesting, algorithmic trading and quantitative research.

## Table of contents

- [Why this dataset?](#why-this-dataset)
- [Download sample CSV](#download-sample)
- [Sample vs full dataset](#sample-vs-full-dataset)
- [Timeframes on GetData](#timeframes-on-getdata)
- [Weekly updates](#weekly-updates)
- [Data preview](#data-preview)
- [Schema](#schema)
- [Download full data on getdata.finance](#download-full-data-on-getdata)

## Why this dataset?

- **Ultra high-quality 1m OHLCV** for **FTSE China A50** (Index)
- **Clean CSV schema** — `time, open, high, low, close, volume` (no gaps in formatting)
- **Free evaluation sample** on GitHub (`1m`) · **11 timeframes** on [getdata.finance](https://getdata.finance/datasets/chn50) · **2,681,069** `1m` rows in the full archive
- Built for **backtesting**, **algorithmic trading** and **quantitative finance** workflows
- **Weekly refresh** — [getdata.finance](https://getdata.finance) every **Saturday, 8am UTC+0**; GitHub `1m` sample updated in sync

> **Sample on GitHub** · `CHN50_1m.csv` (55,440 rows, `2026-06-26` -> `2026-09-02`). **Full archive on [getdata.finance](https://getdata.finance/datasets/chn50)** — **2,681,069** `1m` rows, **11 timeframes**, `2017-07-17` -> `2026-09-02`.

## Download sample

**[CHN50_1m.csv](https://github.com/getdata-finance/chn50-1m-ohlcv-index-historical-data/blob/main/CHN50_1m.csv)** on GitHub ([raw CSV](https://raw.githubusercontent.com/getdata-finance/chn50-1m-ohlcv-index-historical-data/main/CHN50_1m.csv))

## Sample vs full dataset

| | **Sample (this repo)** | **Full dataset ([getdata.finance](https://getdata.finance/datasets/chn50))** |
|---|--:|---|
| Instrument | FTSE China A50 · Index | FTSE China A50 · Index |
| Timeframes | `1m` (sample) | **11** — 1m · 3m · 5m · 15m · 30m · 1H · 4H · 12H · 1D · 3D · 1W |
| 1m rows | 55,440 | **2,681,069** |
| Period | `2026-06-26` -> `2026-09-02` | `2017-07-17` -> `2026-09-02` |
| File | `CHN50_1m.csv` | ZIP on [getdata.finance](https://getdata.finance/datasets/chn50) |
| Coverage report | — | [CHN50 coverage](https://getdata.finance/coverage/chn50) |
| Updates | Weekly (Saturday, 8am UTC+0) — GitHub sample | Weekly (Saturday, 8am UTC+0) — all timeframes |

## Timeframes on GetData

This GitHub repository ships a **`1m` evaluation sample** only. On **[getdata.finance](https://getdata.finance/datasets/chn50)**, each full asset archive is delivered as a ZIP with **11 gap-free OHLCV timeframes**:

**1m** · **3m** · **5m** · **15m** · **30m** · **1H** · **4H** · **12H** · **1D** · **3D** · **1W**

## Weekly updates

- **[getdata.finance](https://getdata.finance)** — Full datasets updated every Saturday, 8am UTC+0.
- **GitHub (this repo)** — GitHub samples refreshed weekly, in sync with getdata.finance.

## Data preview

First and latest rows from the GitHub sample **`CHN50_1m.csv`**:

**First rows**

| time | open | high | low | close | volume |
| --- | --- | --- | --- | --- | --- |
| 2026-06-26T01:47:00+00:00 | 15538.52 | 15542.52 | 15504.54 | 15506.04 | 769 |
| 2026-06-26T01:48:00+00:00 | 15506.04 | 15520.03 | 15503.02 | 15512.54 | 909 |
| 2026-06-26T01:49:00+00:00 | 15512.54 | 15525.53 | 15499.02 | 15524.54 | 1011 |
| 2026-06-26T01:50:00+00:00 | 15524.54 | 15551.54 | 15524.54 | 15544.53 | 1135 |
| 2026-06-26T01:51:00+00:00 | 15544.53 | 15568.54 | 15543.02 | 15551.53 | 1121 |

**Last rows**

| time | open | high | low | close | volume |
| --- | --- | --- | --- | --- | --- |
| 2026-09-02T01:56:00+00:00 | 14585 | 14586 | 14575 | 14575 | 316 |
| 2026-09-02T01:57:00+00:00 | 14575 | 14578.99 | 14565.99 | 14566.51 | 248 |
| 2026-09-02T01:58:00+00:00 | 14566.51 | 14571.01 | 14559.99 | 14567.01 | 300 |
| 2026-09-02T01:59:00+00:00 | 14567.01 | 14567.01 | 14552 | 14554.01 | 262 |
| 2026-09-02T02:00:00+00:00 | 14554.01 | 14554.51 | 14542.99 | 14543.99 | 114 |

## Schema

| Column | Description |
| --- | --- |
| `time` | Bar open timestamp (UTC, ISO-8601). |
| `open` | Opening price of the candlestick bar. |
| `high` | Highest price during the bar. |
| `low` | Lowest price during the bar. |
| `close` | Closing price of the candlestick bar. |
| `volume` | Tick volume (number of price updates) during the bar. |

```text
time,open,high,low,close,volume
```

## Download full data

Full CHN50 archive — 11 timeframes, gap-free, updated weekly:

**[-> Get the full CHN50 dataset on getdata.finance](https://getdata.finance/datasets/chn50)**
