# Crypto Time-Series Lab Workflow

## Pipeline

1.  Ingest and validate schema (OHLCV, timestamps).
2.  Normalize timezones and align datasets.
3.  Compute baseline statistics (returns, volatility, volume).
4.  Compare microstructure features.
5.  Detect volatility/volume regimes.
6.  Export clean dataset + feature set.
7.  Optional dashboard generation.

## Safeguards

-   Check for missing minutes.
-   Clearly distinguish spot vs derivatives.
-   Avoid implicit assumptions.
