# Olist E-Commerce Lakehouse

An end-to-end Data Engineering portfolio project built with Databricks, PySpark, Delta Lake, Unity Catalog and GitHub Actions.

## Overview
Transforms the public Brazilian Olist e-commerce dataset into trusted
analytical tables using the Medallion Architecture (Bronze, Silver, Gold).

## Business questions
Daily revenue, top products, repeat customers, order-to-delivery time.

## Architecture
See docs/architecture.md (diagram added in the final phase).

## Data
The dataset is not stored in this repository. See docs/data_acquisition.md.

## Free Edition notes
Serverless-only compute, limited concurrent job tasks and restricted outbound
internet access. Design decisions that follow from this are documented in docs/.

## Status
Phase 1 – setup in progress.