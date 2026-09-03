# SPX500 1m OHLCV Index Historical Data — Free Sample

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE) [![Dataset rows](https://img.shields.io/badge/full_dataset-5_964_774_rows-blue)](https://getdata.finance/datasets/spx500) [![Updated](https://img.shields.io/badge/weekly_update-every_Saturday_8am_UTC-green)](https://getdata.finance) [![Full data on getdata.finance](https://img.shields.io/badge/download-getdata.finance-orange)](https://getdata.finance/datasets/spx500)

### -> [**Download the full SPX500 dataset on getdata.finance**](https://getdata.finance/datasets/spx500)

**SPX500 1m OHLCV index historical data** — ultra high-quality 1m OHLCV for **S&P 500**. Clean `time, open, high, low, close, volume` CSV for backtesting, algorithmic trading and quantitative research.

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

- **Ultra high-quality 1m OHLCV** for **S&P 500** (Index)
- **Clean CSV schema** — `time, open, high, low, close, volume` (no gaps in formatting)
- **Free evaluation sample** on GitHub (`1m`) · **11 timeframes** on [getdata.finance](https://getdata.finance/datasets/spx500) · **5,964,774** `1m` rows in the full archive
- Built for **backtesting**, **algorithmic trading** and **quantitative finance** workflows
- **Weekly refresh** — [getdata.finance](https://getdata.finance) every **Saturday, 8am UTC+0**; GitHub `1m` sample updated in sync

> **Sample on GitHub** · `SPX500_1m.csv` (55,440 rows, `2026-07-07` -> `2026-09-02`). **Full archive on [getdata.finance](https://getdata.finance/datasets/spx500)** — **5,964,774** `1m` rows, **11 timeframes**, `2008-08-19` -> `2026-09-02`.

## Download sample

**[SPX500_1m.csv](https://github.com/getdata-finance/spx500-1m-ohlcv-index-historical-data/blob/main/SPX500_1m.csv)** on GitHub ([raw CSV](https://raw.githubusercontent.com/getdata-finance/spx500-1m-ohlcv-index-historical-data/main/SPX500_1m.csv))

## Sample vs full dataset

| | **Sample (this repo)** | **Full dataset ([getdata.finance](https://getdata.finance/datasets/spx500))** |
|---|--:|---|
| Instrument | S&P 500 · Index | S&P 500 · Index |
| Timeframes | `1m` (sample) | **11** — 1m · 3m · 5m · 15m · 30m · 1H · 4H · 12H · 1D · 3D · 1W |
| 1m rows | 55,440 | **5,964,774** |
| Period | `2026-07-07` -> `2026-09-02` | `2008-08-19` -> `2026-09-02` |
| File | `SPX500_1m.csv` | ZIP on [getdata.finance](https://getdata.finance/datasets/spx500) |
| Coverage report | — | [SPX500 coverage](https://getdata.finance/coverage/spx500) |
| Updates | Weekly (Saturday, 8am UTC+0) — GitHub sample | Weekly (Saturday, 8am UTC+0) — all timeframes |

## Timeframes on GetData

This GitHub repository ships a **`1m` evaluation sample** only. On **[getdata.finance](https://getdata.finance/datasets/spx500)**, each full asset archive is delivered as a ZIP with **11 gap-free OHLCV timeframes**:

**1m** · **3m** · **5m** · **15m** · **30m** · **1H** · **4H** · **12H** · **1D** · **3D** · **1W**

## Weekly updates

- **[getdata.finance](https://getdata.finance)** — Full datasets updated every Saturday, 8am UTC+0.
- **GitHub (this repo)** — GitHub samples refreshed weekly, in sync with getdata.finance.

## Data preview

First and latest rows from the GitHub sample **`SPX500_1m.csv`**:

**First rows**

| time | open | high | low | close | volume |
| --- | --- | --- | --- | --- | --- |
| 2026-07-07T18:59:00+00:00 | 7499.05 | 7499.32 | 7497.55 | 7498.3 | 601 |
| 2026-07-07T19:00:00+00:00 | 7498.3 | 7500.32 | 7494.3 | 7495.05 | 989 |
| 2026-07-07T19:01:00+00:00 | 7495.05 | 7495.32 | 7491.55 | 7493.8 | 1102 |
| 2026-07-07T19:02:00+00:00 | 7493.8 | 7496.56 | 7493.8 | 7495.32 | 1047 |
| 2026-07-07T19:03:00+00:00 | 7495.32 | 7496.8 | 7494.56 | 7494.56 | 698 |

**Last rows**

| time | open | high | low | close | volume |
| --- | --- | --- | --- | --- | --- |
| 2026-09-02T01:56:00+00:00 | 7628.83 | 7629.08 | 7627.83 | 7627.83 | 126 |
| 2026-09-02T01:57:00+00:00 | 7627.83 | 7628.47 | 7627.34 | 7627.58 | 100 |
| 2026-09-02T01:58:00+00:00 | 7627.58 | 7629.6 | 7627.58 | 7629.6 | 117 |
| 2026-09-02T01:59:00+00:00 | 7629.6 | 7629.85 | 7628.6 | 7629.58 | 82 |
| 2026-09-02T02:00:00+00:00 | 7629.58 | 7629.85 | 7629.58 | 7629.85 | 29 |

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

Full SPX500 archive — 11 timeframes, gap-free, updated weekly:

**[-> Get the full SPX500 dataset on getdata.finance](https://getdata.finance/datasets/spx500)**
