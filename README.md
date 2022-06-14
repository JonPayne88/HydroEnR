---
HydroEnR
================
Jonathan Payne
14/06/2022

# Welcome to HydroEnR!

This package is designed for members of Evidence and Risk. It allows you
to;

  - Easily load data from WISKI
      - Carry out quality checks on these data  
  - Aggregate data by different periods and through various functions
    using rapid C++ elements
  - Detect peaks in hydrological data
  - Convert flow data to a volumetric measure over a designated time
    step
  - Develop Thiessen polygons for use in our realtime flood forecast
    models
  - Download up-to-date meta data on EA gauges
  - Import recent flow, stage and rain gauge data via the EAs API
  - Detect trends in hydrological data
  - Inspect ARMA parameters for stability in a real time forecasting
    context
  - Use basic hydraulic equations such as the Mannings’ equation
      - Import cross sectional data and carry out rudimentry analyses
  - Carry out single site analyses
      - ESS in the near future
  - Use a greater selection of objective functions during model
    calibration

<!-- end list -->

``` r
monthplot(Buildwas_Analysis, name = 'Buildwas', polar = FALSE)
```

![](README_figs/README-unnamed-chunk-3-1.png)<!-- -->

``` r
monthplot(Buildwas_Analysis, name = 'Buildwas', polar = TRUE)
```

![](README_figs/README-unnamed-chunk-4-1.png)<!-- -->
