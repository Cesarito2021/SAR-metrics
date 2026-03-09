# SAR-metrics

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

Python, R and Google Earth Engine (GEE) scripts for processing and extracting 
SAR-derived backscatter metrics and polarimetric variables from L-band (NISAR, UAVSAR) 
and C-band (Sentinel-1) data for vegetation and carbon applications.

## Platform

- **Google Colab** — Python scripts for NISAR/UAVSAR processing and metrics extraction
- **Google Earth Engine (JavaScript/Python API)** — SAR data access and preprocessing
- **R** — Statistical modeling, bootstrap validation and figure generation

## Contents (in progress)
- `GEE/` — Google Earth Engine scripts for Sentinel-1 backscatter and PALSAR processing *(coming soon)*
- `colab/` — Google Colab notebooks for NISAR dual- and quad-polarization metrics extraction and AGCt modelling
- `utils/` — Helper functions *(coming soon)*

## SAR Variables

- Backscatter: σ⁰_HH, σ⁰_HV [linear and dB]
- Derived: √σ⁰_HV, σ⁰_HH×HV, σ⁰_HH+HV, CPR, NDSI
- Polarimetric indices: RVI, DpRVI, H, α, DoP

## Status

> ⚠️ This repository is currently under active development. 
> Scripts and documentation are being added progressively.

## Dependencies

### Python (Google Colab)
```python
pip install polsartools rasterio numpy geopandas
```

### R
```r
install.packages(c("terra", "sf", "dplyr", "ggplot2", "patchwork", "MetBrewer"))
```

## Author

Cesar Ivan Alvites Diaz — University of Florida

## Citation

Alvites Diaz et al. (in prep.) — Mapping aboveground carbon stocks in Brazilian Cerrado using NISAR L-band SAR variables.
