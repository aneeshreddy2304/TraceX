<p align="center"><img src="docs/assets/banner.svg" alt="TraceX — Explore proximity patterns through spatial clustering." width="100%"></p>

<p align="center"><img src="docs/assets/badges/python.svg" alt="python" height="28"> <img src="docs/assets/badges/streamlit.svg" alt="streamlit" height="28"> <img src="docs/assets/badges/pandas.svg" alt="pandas" height="28"> <img src="docs/assets/badges/scikit-learn.svg" alt="scikit-learn" height="28"></p>

<p align="center"><strong>A Streamlit prototype that turns timestamped coordinate records into explorable contact clusters and optional notifications.</strong></p>

## Overview

A Streamlit prototype that turns timestamped coordinate records into explorable contact clusters and optional notifications.

### Why it matters

TraceX makes spatial-analysis workflows tangible: load location records, inspect DBSCAN groupings, and review candidate contacts in one interface.

## Key features

- Interactive contact and cluster exploration
- DBSCAN-based grouping of latitude and longitude records
- Visual plots for reviewing candidate proximity
- Optional SMTP notification path

## Architecture

```mermaid
flowchart LR
  A[Coordinate records] --> B[Streamlit interface]
  B --> C[DBSCAN clustering]
  C --> D[Contact review + plots]
  D --> E[Optional email notification]
```

## Technology stack

**python** · **streamlit** · **pandas** · **scikit learn**

## Getting started

Install the imported Python packages, place the expected JSON and image assets in the repository root, then run `streamlit run main.py`. Use synthetic, permission-cleared location data for demonstrations.
