# Hi, I'm Ahammed Nabil

## Data and AI Engineering Portfolio

I build practical data and AI systems in Python, progressing from analytics foundations to production-oriented workflows.

My work focuses on reliable data movement, measurable analysis, deployable model inference, and evaluation of retrieval systems. I document assumptions, preserve source context, add tests, and state limitations clearly.

## Portfolio map

| Repository | What it demonstrates |
|---|---|
| [Data Analytics Portfolio](https://github.com/Ahammed-Nabil/data-analytics-portfolio) | Python, SQL, DuckDB, KPI design, dimensional modeling, RFM/cohort retention, segmentation, anomaly detection, dashboards, experiment analysis |
| [Data Engineering Portfolio](https://github.com/Ahammed-Nabil/data-engineering-portfolio) | CSV ETL, REST APIs, retries, data contracts, schema/completeness checks, freshness, distributions, atomic writes, structured logging, orchestration, run history, incremental ELT, Docker |
| [AI/ML Engineering Portfolio](https://github.com/Ahammed-Nabil/ai-ml-engineering-portfolio) | scikit-learn, model evaluation, FastAPI inference, health checks, Docker, TF-IDF retrieval, RAG evaluation, KS/PSI monitoring, model registries, promotion gates, subgroup fairness evaluation, feature contracts, offline/online parity checks |

## Selected projects

### Production Data Pipeline

A production-style reference pipeline with raw-response preservation, JSON contracts, retries, quality metrics, atomic output publication, structured logs, tests, operations documentation, and Docker packaging.

### Model API

A validated FastAPI service that loads a reproducible classifier artifact, checks feature inputs, returns predictions and probabilities, exposes health and metadata endpoints, and includes tests and Docker packaging.

### RAG Evaluation

A deterministic evaluation workflow using documented source passages, TF-IDF retrieval, extractive grounded answers, expected-source labels, citation checks, keyword coverage, latency, and reproducible reports.

### Executive Dashboard

A decision-ready analytics workflow with data-quality validation, revenue and order KPIs, product and customer segmentation, anomaly detection, and reproducible dashboard artifacts.

### RFM and Cohort Retention

A reproducible customer analytics workflow that calculates RFM scores, segments customers, builds first-purchase cohorts, and exports retention tables and charts from a real sales dataset.

### Model Monitoring

A monitoring workflow that compares red and white UCI wine populations with baseline/current model metrics, KS tests, PSI thresholds, and a visual drift report.

### SQL Analytics Engineering

A DuckDB warehouse workflow with staging, fact, customer, product, and KPI mart models, exported tables, quality checks, and automated tests over a real sales dataset.

### A/B-Test Experiment Analysis

A statistically cautious workflow that validates treatment/page assignment, compares conversion rates, calculates confidence intervals and p-values, measures practical lift, and produces a reproducible launch decision.

### Data Quality Observability

A reusable contract-driven framework that checks schema, completeness, primary-key uniqueness, freshness, numeric ranges, and distribution shifts, then emits machine-readable JSON and human-readable Markdown health reports.

### Model Registry and Promotion Gates

A reproducible MLOps workflow that evaluates logistic regression and random forest candidates, enforces accuracy and macro-F1 gates, registers versioned artifacts, promotes a champion, and carries model lineage into batch predictions.

### Fairness and Subgroup Evaluation

A descriptive audit on the UCI Adult dataset that excludes sex from predictive features, reports subgroup selection, TPR, and FPR, sweeps decision thresholds, and documents responsible-use limits.

### Post-Rollback Verification

A recovery-verification workflow that checks rollback authorization, champion version, feature-contract width, known-good parity, and a deterministic smoke prediction. The reference recovery passed all five checks and produced a hashed audit record.

### Monitoring Drift and Alert Evaluation

Extended model monitoring with the real UCI Wine Quality dataset by comparing reference and current populations using KS and PSI metrics, performance degradation checks, warning/critical severity, and machine-readable alert reports. The reference run flagged all 11 features and showed ROC-AUC moving from 0.872 to 0.755.

### Production Model Serving Observability

A privacy-safe inference observability layer that records structured request metadata, aggregates p50/p95/max latency and error rates, checks model-version consistency, and emits threshold-based health alerts. The reference run processed 25 successful requests at 18 ms p95 latency with zero alerts.

### Batch/Online Inference Parity Harness

A release-gating harness that compares batch and request-time predictions from the same calibrated model artifact. It enforces an exact 30-feature contract, rejects missing and non-finite inputs, compares labels, probabilities, and model lineage across 25 rows, and reports zero mismatches.

### Feature Store and Training-Serving Consistency

A lightweight feature-store pattern built on real Adventure Works sales data. Versioned a customer feature contract, generated a 12,427-entity offline snapshot, implemented online-style point lookup with missing-entity and freshness checks, and compared serving vectors against training features to detect skew.

### Pipeline Orchestration and Recovery

A dependency-aware workflow that runs ingestion and quality validation as separate tasks, retries transient failures, blocks downstream work after upstream failure, and persists task-level run history.

### Incremental Warehouse ELT

A partition-aware warehouse load that fingerprints CSV inputs, processes only new or changed partitions, preserves historical sales facts, deduplicates order-line keys, and exports current customer and product dimensions.

## Tools

`Python` `SQL` `DuckDB` `Pandas` `Requests` `pytest` `scikit-learn` `FastAPI` `Docker` `GitHub Actions` `Matplotlib` `REST APIs` `ETL` `Data Contracts` `Data Quality` `Freshness Monitoring` `Observability` `Orchestration` `Retries` `Run History` `Incremental ELT` `Partition Fingerprinting` `Dimensional Modeling` `RAG Evaluation` `RFM` `Cohort Analysis` `A/B Testing` `Confidence Intervals` `Practical Lift` `Model Registry` `Promotion Gates` `Fairness Auditing` `Subgroup Metrics` `Responsible AI` `KS Test` `PSI` `Feature Contracts` `Offline Snapshots` `Online Lookup` `Training-Serving Skew` `Inference Parity` `Release Gates` `Structured Logging` `Latency Metrics` `Error Rates` `Alert Thresholds` `KS Test` `PSI` `Drift Alerts` `Severity Levels` `Rollback Verification` `Smoke Tests` `Recovery Evidence`

## What I am learning next

I am deepening cloud data engineering, SQL, Linux, testing, system design, model monitoring, and asynchronous remote collaboration skills.

## Contact

- LinkedIn: [Add your LinkedIn URL]
- Email: [Add your professional email]
- Location/time zone: [Add your location and preferred overlap]

> Portfolio projects are educational demonstrations. Each repository includes its own source, methodology, validation evidence, and limitations.
