# Open-Fund Risk Intelligence

Public-data platform for open-fund risk intelligence using SEC N-PORT holdings, quantitative risk models, and a limited evidence-grounded document layer.

## Objective
Build a production-style research platform that ingests public fund holdings, normalizes them, estimates concentration and fragility metrics, and compares observable holdings with stated strategy using only public data.

## Version 1 scope
- SEC N-PORT holdings ingestion and normalization
- Concentration, covariance, volatility, and one stress module
- Initial liquidity-fragility proxies
- Limited evidence-grounded document interpretation
- Clear abstention when evidence is weak

## Out of scope
- Investment advice
- Private or licensed data
- Client or employer material
- Reconstructing hidden derivatives or collateral mechanics with unjustified certainty

## Repository structure
- `src/` core code
- `tests/` tests
- `docs/` charter, data dictionary, IP note, reading plan
- `data/` raw, interim, processed samples
- `experiments/` research runs
- `report/` final write-up

## Current status
Initial repository scaffold and project setup.

## Data source
SEC Form N-PORT public datasets.

## IP note
This project uses only public data, original code, and original write-up.
