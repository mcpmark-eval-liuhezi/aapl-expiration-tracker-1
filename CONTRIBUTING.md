# Contributing to aapl-expiration-tracker

Thank you for contributing to the AAPL options expiration tracker. This repo is used by the risk desk for weekly options reviews, so please follow these guidelines.

## How to Submit Changes

1. **Create a tracking issue first** for any new expiration or data update. Title it `Expiry YYYY-MM-DD` (real date substituted) and include:
   - The expiration's at-the-money strike
   - The highest-open-interest call strike
   - The highest-open-interest put strike
   - The share price you used

2. **Add a file on a new branch** (e.g. `add-<topic>`) and open a pull request into `main`.

3. **Keep market data live.** All figures must come from live data sources (Yahoo Finance). Where a number looks odd, report exactly what the source returned rather than silently correcting it.

## Repository Structure

- `expirations.md` — main tracking document (company snapshot, expiration map, per-expiration chain stats)
- Issues `#1`, `#2`, `#3` — per-expiration tracking issues in date order
- Pull Request #4 — brings `expirations.md` into `main`

## CODE_OF_CONDUCT

Be respectful, double-check numbers against the source, and note any data caveats in the PR description.
