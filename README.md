# Data Engineering Portfolio

## Target role

I am building practical evidence for an Azure Data Engineer role through real, documented data-engineering work.

## Overview

This repository contains an end-to-end portfolio project using real public data: ingestion, SQL analysis, data quality checks, modelling, testing, orchestration, reliability testing, and cost analysis.

## Planned artifacts

1. [Real-data ingestion](#1-real-data-ingestion)
2. [SQL query pack](#2-sql-query-pack)
3. [Query performance analysis](#3-query-performance-analysis)
4. [Data quality and quarantine](#4-data-quality-and-quarantine)
5. [Dimensional model and SCD Type 2](#5-dimensional-model-and-scd-type-2)
6. [PySpark and file-format comparison](#6-pyspark-and-file-format-comparison)
7. [End-to-end pipeline](#7-end-to-end-pipeline)
8. [Reliability, CI, serving, and cost analysis](#8-reliability-ci-serving-and-cost-analysis)

### 1. Real-data ingestion

Planned: load a real, changing public dataset with an idempotent ingestion process.

### 2. SQL query pack

Planned: solve interview-shaped SQL questions against my own data.

### 3. Query performance analysis

Planned: measure slow queries, add indexes where appropriate, and document the before-and-after results.

### 4. Data quality and quarantine

Planned: clean data with tests and send failed records to quarantine instead of deleting them.

### 5. Dimensional model and SCD Type 2

Planned: build a star schema and preserve historical changes correctly.

### 6. PySpark and file-format comparison

Planned: compare pandas and PySpark processing, plus CSV, Parquet, and Delta formats.

### 7. End-to-end pipeline

Planned: orchestrate ingestion, transformation, modelling, and serving with reconciled row counts.

### 8. Reliability, CI, serving, and cost analysis

Planned: document failure recovery, automated checks, a small report, and actual cloud-cost measurements.

## Repository structure

- `sql/` — SQL scripts and query pack
- `src/` — Python ingestion, cleaning, and modelling code
- `pipelines/` — pipeline definitions
- `notebooks/` — PySpark notebooks
- `docs/` — technical explanations and decisions
- `tests/` — automated tests
