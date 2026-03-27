---
layout: archive
title: "Projects"
permalink: /projects/
author_profile: true
---

## Active Research Projects

---

### GEDEx: Global Education Data Exchange
*Funded by the Spencer Foundation (RPP)*

GEDEx is a research-practice partnership focused on improving the quality, interoperability, and use of education management information systems (EMIS) in the Global South. The project brings together researchers and practice partners — including ANSA — to develop frameworks for cross-national education data sharing, anomaly detection, and policy-relevant data quality diagnostics.

**Key questions:**
- How can cross-national EMIS data be standardized for comparative analysis?
- What machine learning approaches can detect falsified or anomalous reporting in education datasets?
- How can GeoAI tools support evidence-based education planning in data-scarce contexts?

---

### Empirical Scale Recovery (ESR)
*Novel methodological framework*

ESR is a new research framework for inferring the geographic scale at which socioeconomic processes operate, using cross-resolution satellite imagery. By comparing model performance across spatial resolutions (e.g., Planet 3m vs. Sentinel-2 10m vs. Landsat 30m), ESR recovers the implicit scale of the underlying process — without requiring ground truth at multiple resolutions.

A first paper applying ESR to education outcomes is in preparation.

---

### Coordinate Uncertainty in GeoAI
*Methods + equity implications*

This project treats location as a noisy, probabilistic input rather than a fixed point. Using a continuous earth representation with a learned 2D Gaussian coordinate distribution and the reparameterization trick, we model coordinate uncertainty as input-space aleatoric uncertainty. A parallel paper examines how realistic positional error in GeoAI models produces inequitable prediction errors affecting Title I school funding eligibility.

**Related outputs:**
- Locational uncertainty methods paper *(targeting ACM SIGSPATIAL)*
- Title I equity implications paper *(targeting Computers, Environment and Urban Systems)*
- DHS geomasking diagnostic framework paper *(targeting GIScience & Remote Sensing)*

---

### GNN-based EMIS Anomaly Detection
*Transfer learning for education data integrity*

This project trains a graph neural network on high-integrity U.S. NCES Common Core of Data (CCD) records and transfers to Philippine DepEd data to detect falsified statistical reporting. Schools are represented as nodes with spatial and administrative edges; anomaly scores flag records that deviate from expected patterns given spatial context.

---

### `geoetl`: Python Package for Geospatial ETL
*Open source*

`geoetl` is a Python package for geospatial extract-transform-load workflows, with a `GEESource` class supporting Landsat 5, Landsat 8, and Sentinel-2 downloads via Google Earth Engine. The package handles cloud masking, compositing, and projection standardization.

[View on GitHub](https://github.com/heatherbaier)

---

## Past Projects

*Add past projects here.*
