# AAPL Options Expiration Tracker

> **Weekly tracking repo for the risk desk.** All market figures below were pulled live from Yahoo Finance on the date of review. Where a number looks odd, it is reported exactly as the source returned it.

## 1. Company Snapshot — Apple Inc. (AAPL)

| Field | Value |
|-------|-------|
| **Company** | Apple Inc. |
| **Ticker** | AAPL (NasdaqGS) |
| **Headquarters Street Address** | One Apple Park Way, MS 927-4GC |
| **City** | Cupertino, CA 95014, United States |
| **Sector** | Technology |
| **Industry** | Consumer Electronics |
| **Current Share Price** | **$355.63** (USD, Nasdaq Real Time Price; post-market $356.35) |
| **Market Cap** | ~$5.17T |
| **Employees** | 167,000 |
| **Website** | https://www.apple.com |
| **Phone** | (408) 996-1010 |

**Other profile notes (from live data):** apostolic officers include John Ternus (CEO), Kevan Parekh (CFO), Sabih Khan (COO). Analyst consensus: Buy (mean 2.2, 40 analysts, mean target $344.62). Trailing P/E 39.6, forward P/E 33.7. 52-week range: $243.42 – $355.90.

## 2. Expiration Map — Available AAPL Option Expiration Dates

The option expiration dates currently available for AAPL (in date order):

| # | Expiration Date |
|---|-----------------|
| 1 | 2026-11-13 |
| 2 | 2026-11-16 |
| 3 | 2026-11-18 |
| 4 | 2026-11-20 |
| 5 | 2026-11-27 |
| 6 | 2026-12-04 |
| 7 | 2026-12-11 |
| 8 | 2026-12-18 |
| 9 | 2026-12-24 |
| 10 | 2027-01-15 |
| 11 | 2027-02-19 |
| 12 | 2027-03-19 |
| 13 | 2027-04-16 |
| 14 | 2027-06-17 |
| 15 | 2027-09-17 |
| 16 | 2027-12-17 |
| 17 | 2028-01-21 |
| 18 | 2028-03-17 |
| 19 | 2028-06-16 |
| 20 | 2028-12-15 |
| 21 | 2029-01-19 |

**This week's focus (3 soonest upcoming expirations, skipping anything earlier than today):** **2026-11-13**, **2026-11-16**, and **2026-11-18**.

## 3. Per-Expiration Chain Stats

**Share price used for ATM determination (all three expirations): $355.63**

### Expiration 2026-11-13

| Metric | Value |
|--------|-------|
| **At-The-Money (ATM) Strike** | **355** (closest strike to $355.63; distance = 0.63) |
| **Highest-OI Call Strike** | **360** (Open Interest = 16,819) |
| **Highest-OI Put Strike** | **265** (Open Interest = 10,654) |

 supporting contracts (Yahoo Finance, calls): Strike 360 OI 16,819; Strike 355 OI 11,813; Strike 350 OI 7,547; Strike 365 OI 11,856; Strike 360 OI 16,819.
 supporting contracts (Yahoo Finance, puts): Strike 265 OI 10,654; Strike 330 OI 10,223; Strike 340 OI 9,560; Strike 300 OI 3,672; Strike 322.5 OI 6,921.

### Expiration 2026-11-16

| Metric | Value |
|--------|-------|
| **At-The-Money (ATM) Strike** | **355** (closest strike to $355.63; distance = 0.63) |
| **Highest-OI Call Strike** | **355** (Open Interest = 5,737) |
| **Highest-OI Put Strike** | **330** (Open Interest = 1,537) |

 Supporting contracts (Yahoo Finance, calls): Strike 355 OI 5,737; Strike 350 OI 559; Strike 360 OI 801; Strike 352.5 OI 435.
 Supporting contracts (Yahoo Finance, puts): Strike 330 OI 1,537; Strike 320 OI 951; Strike 340 OI 1,175; Strike 312.5 OI 311.

### Expiration 2026-11-18

| Metric | Value |
|--------|-------|
| **At-The-Money (ATM) Strike** | **355** (closest strike to $355.63; distance = 0.63) |
| **Highest-OI Call Strike** | **362.5** (Open Interest = 7,037) |
| **Highest-OI Put Strike** | **340** (Open Interest = 439) |

 Supporting contracts (Yahoo Finance, calls): Strike 362.5 OI 7,037; Strike 357.5 OI 5,043; Strike 352.5 OI 2,176; Strike 355 OI 138.
 Supporting contracts (Yahoo Finance, puts): Strike 340 OI 439; Strike 330 OI 231; Strike 345 OI 158; Strike 350 OI 145.

## 4. Summary Table

| Expiration | Share Price Used | ATM Strike | Top-OI Call Strike (OI) | Top-OI Put Strike (OI) |
|------------|------------------|------------|--------------------------|------------------------|
| 2026-11-13 | $355.63 | 355 | 360 (16,819) | 265 (10,654) |
| 2026-11-16 | $355.63 | 355 | 355 (5,737) | 330 (1,537) |
| 2026-11-18 | $355.63 | 355 | 362.5 (7,037) | 340 (439) |

## 5. Tracking Issues (created in this repo, in date order)

1. **#1 — Expiry 2026-11-13** — ATM strike 355, top-OI call 360 (OI 16,819), top-OI put 265 (OI 10,654). Share price used: $355.63.
2. **#2 — Expiry 2026-11-16** — ATM strike 355, top-OI call 355 (OI 5,737), top-OI put 330 (OI 1,537). Share price used: $355.63.
3. **#3 — Expiry 2026-11-18** — ATM strike 355, top-OI call 362.5 (OI 7,037), top-OI put 340 (OI 439). Share price used: $355.63.

## 6. Repository Notes

- **Repository URL:** https://github.com/mcpmark-eval-liuhezi/aapl-expiration-tracker-1
- **Note on naming:** The preferred name `aapl-expiration-tracker` was already taken in the `mcpmark-eval-liuhezi` organization (along with `-2`, `-3`, `-4`, `-5`, `-7`, `-8`, `-9`, `-10`, `-11`, `-12`, `-13`, `-14`, `-15`, `-16`, and `-desk`), so this repo was created as `aapl-expiration-tracker-1` per the fallback convention.
- **Default branch:** `main`
- **Tracking branch:** `add-expirations-markdown` (this PR adds `expirations.md` at the repo root)
- **Source:** All market data pulled live from Yahoo Finance (company profile, option expiration dates, and call/put option chains for each of the three nearest expirations).
