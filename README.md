# EURUSD 1h OHLCV Forex Historical Data — Free Sample

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE) [![Full data on getdata.finance](https://img.shields.io/badge/download-getdata.finance-orange)](https://getdata.finance/datasets/eurusd)

## -> [Download the full EURUSD dataset on getdata.finance](https://getdata.finance/datasets/eurusd)

**EURUSD 1h OHLCV forex historical data** — ultra high-quality 1h OHLCV for **Euro / US Dollar**. Clean `datetime, open, high, low, close, volume` CSV for backtesting, algorithmic trading and quantitative research.

## Table of contents

- [Why this dataset?](#why-this-dataset)
- [Download sample](#download-sample)
- [Sample vs full dataset](#sample-vs-full-dataset)
- [Timeframes on GetData](#timeframes-on-getdata)
- [Weekly updates](#weekly-updates)
- [Data preview](#data-preview)
- [Schema](#schema)
- [Download full data](#download-full-data-on-getdata)

## Why this dataset?

- **Ultra high-quality 1h OHLCV** for **Euro / US Dollar** (forex)
- **Clean CSV schema** — `datetime, open, high, low, close, volume`
- **Free evaluation sample** on GitHub (`1h`)
- **11 timeframes** on [getdata.finance](https://getdata.finance/datasets/eurusd)
- Built for **backtesting**, **algorithmic trading** and **quantitative finance** workflows
- **Weekly refresh** — [getdata.finance](https://getdata.finance) every **Saturday, 8am UTC+0**

## Download sample

**[EURUSD_1h.csv](EURUSD_1h.csv)** — free evaluation sample (1,614 rows).

## Sample vs full dataset

| | **Sample (this repo)** | **Full dataset ([getdata.finance](https://getdata.finance/datasets/eurusd))** |
|---|--:|---|
| Instrument | Euro / US Dollar · Forex | Euro / US Dollar · Forex |
| Timeframes | `1h` (sample) | **11** — 1m · 3m · 5m · 15m · 30m · 1H · 4H · 12H · 1D · 3D · 1W |
| 1h rows | 1,614 | **28 096** |
| Size | sample only | ~64.86 MB |
| Period | `2026-05-31` -> `2026-09-02` | full archive |
| File | `EURUSD_1h.csv` | ZIP on [getdata.finance](https://getdata.finance/datasets/eurusd) |
| Coverage report | — | [EURUSD coverage](https://getdata.finance/coverage/eurusd) |
| Updates | Weekly (Saturday, 8am UTC+0) — GitHub sample | Weekly (Saturday, 8am UTC+0) — all timeframes |

## Timeframes on GetData

This GitHub repository ships a **`1h` evaluation sample** only. On **[getdata.finance](https://getdata.finance/datasets/eurusd)**, each full asset archive is delivered as a ZIP with **11 gap-free OHLCV timeframes** (one CSV per timeframe):

**1m** · **3m** · **5m** · **15m** · **30m** · **1H** · **4H** · **12H** · **1D** · **3D** · **1W**

GitHub = `1h` sample · [getdata.finance](https://getdata.finance/datasets/eurusd) = all **11** timeframes above for the same instrument.

## Weekly updates

- **[getdata.finance](https://getdata.finance)** — Full datasets updated every Saturday, 8am UTC+0.
- **GitHub (this repo)** — GitHub samples refreshed weekly, in sync with getdata.finance.

When a new `1h` sample is published on GitHub, the README, chart preview and CSV reflect the latest week of data.

## Data preview

First and latest rows from the GitHub sample **`EURUSD_1h.csv`**:

**First rows**

| datetime | open | high | low | close | volume |
| --- | --- | --- | --- | --- | --- |
| 2026-05-31T21:00:00+00:00 | 1.17657 | 1.1776100000000003 | 1.17653 | 1.1773500000000003 | 541.407417375544 |
| 2026-05-31T22:00:00+00:00 | 1.1773500000000003 | 1.1774700000000002 | 1.1767800000000004 | 1.1771000000000003 | 2896 |
| 2026-05-31T23:00:00+00:00 | 1.1771000000000003 | 1.1772300000000002 | 1.1765100000000004 | 1.1765200000000002 | 4822 |
| 2026-06-01T00:00:00+00:00 | 1.1765200000000002 | 1.1770500000000004 | 1.1761600000000003 | 1.1764300000000003 | 7428 |
| 2026-06-01T01:00:00+00:00 | 1.1764300000000003 | 1.1764900000000003 | 1.1758600000000003 | 1.1761500000000003 | 4560 |

**Last rows**

| datetime | open | high | low | close | volume |
| --- | --- | --- | --- | --- | --- |
| 2026-09-01T22:00:00+00:00 | 1.15911 | 1.1596 | 1.15911 | 1.15925 | 1336 |
| 2026-09-01T23:00:00+00:00 | 1.15925 | 1.15931 | 1.15903 | 1.15903 | 1153 |
| 2026-09-02T00:00:00+00:00 | 1.15903 | 1.15917 | 1.15832 | 1.15832 | 6319 |
| 2026-09-02T01:00:00+00:00 | 1.15832 | 1.15842 | 1.15768 | 1.15789 | 5469 |
| 2026-09-02T02:00:00+00:00 | 1.15789 | 1.1579 | 1.15781 | 1.15781 | 63 |

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

## Download full data

Full EURUSD archive — 11 timeframes, gap-free, updated weekly:

**[-> Get the full EURUSD dataset on getdata.finance](https://getdata.finance/datasets/eurusd)**
