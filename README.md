# Isla Vista Housing Conditions Study

A spatial research and stratified random sampling project designed to study tenant-reported housing conditions across Isla Vista, California.

## Project Overview

This project develops a sampling framework for a tenant-centered study of housing conditions in Isla Vista. The goal is to collect geographically representative survey data while reducing clustering and selection bias.

The study focuses on tenant-reported experiences including housing conditions, utilities, landlord responsiveness, and overall housing satisfaction.

## Sampling Methodology

To improve geographic representation, Isla Vista was divided into 14 geographic zones that serve as sampling strata.

The sampling process includes:

1. Constructing a residential-unit sampling frame for each geographic zone
2. Cleaning and organizing unit records by zone
3. Allocating the target sample across zones based on the number of housing units
4. Randomly selecting units within each zone
5. Generating randomized reserve selections for nonresponse

This approach combines geographic stratification with random sampling to improve coverage across different areas of Isla Vista.

## Geographic Design

Geographic zones were developed using maps of Isla Vista and differences in characteristics such as housing density, building type, and location.

The resulting sampling frame contains approximately 895 residential units across 14 zones.

## Tools & Methods

- Geographic and land-use maps
- Stratified random sampling
- Proportional allocation
- Survey design
- Excel
- Python / pandas
- Statistical analysis

## Project Status

Sampling design and survey development are currently in progress. Future work will include survey collection, exploratory spatial analysis, and analysis of housing-condition patterns across Isla Vista.

## Repository Structure

- `analysis/` — reproducible sampling and analysis code
- `data/` — aggregated and de-identified data
- `maps/` — geographic sampling-zone visualizations
- `docs/` — sampling methodology and research design documentation
