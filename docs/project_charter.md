# Project Charter

## Project name
Open-Fund Risk Intelligence

## Research question
Can a public-data platform detect hidden risk in investment funds by combining holdings-based quantitative risk models with document-grounded mandate interpretation, while abstaining when the evidence is too weak to support a strong claim?

## Version 1 goal
Build a reproducible public-data pipeline using SEC N-PORT data and implement:
1. holdings ingestion and normalization
2. concentration and covariance-based risk views
3. one stress-testing module
4. initial liquidity-fragility proxies
5. a narrow evidence-grounded document layer

## In scope
- Public SEC N-PORT data
- Original code
- Deterministic quantitative risk calculations
- Evidence-grounded text interpretation
- Explainable alerts and abstention logic

## Out of scope
- Investment recommendations
- Private or licensed data
- Employer or client material
- Claims to fully infer hidden derivatives or collateral mechanics from public filings

## First milestone
Produce a clean sample ingestion pipeline and a documented set of 8–12 N-PORT fields for v1 analytics.

## Success condition for milestone 1
A raw sample can be ingested, validated, and converted into the same clean table twice without manual fixes.
