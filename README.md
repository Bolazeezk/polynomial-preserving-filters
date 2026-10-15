# Polynomial-Preserving Linear Filters for Time Series Smoothing

**Master's Thesis — MS in Mathematics**  
**Institution:** Illinois State University  
**Author:** Kaosarat Bola Azeez  
**Year:** 2026

**Official Thesis:** [Theoretical Analysis of Filtering and Smoothing Techniques in Stochastic Time Series](https://ir.library.illinoisstate.edu/etd/2399)

## Overview

This repository accompanies my master's thesis, *Theoretical Analysis of Filtering and Smoothing Techniques in Stochastic Time Series*, completed at Illinois State University.

The thesis presents a unified mathematical treatment of polynomial-preserving linear filters used in time series smoothing and trend extraction, with particular emphasis on Savitzky–Golay filters and the Spencer 15-point moving average.

## Research Objectives

The research focuses on:

- Examining the mathematical foundations of polynomial-preserving linear filters.
- Deriving coefficient vectors for classical Savitzky–Golay and Spencer smoothing filters.
- Verifying polynomial reproduction properties using moment conditions.
- Investigating the relationship between local least-squares smoothing and successive averaging methods.
- Comparing filter performance using synthetic and real-world time series data.

## Mathematical Methods

The thesis examines symmetric linear filters and the moment conditions required for exact reproduction of polynomials up to a specified degree.

The filters studied include:

- Savitzky–Golay SG(5,2)
- Savitzky–Golay SG(7,3)
- Spencer 15-point moving average

A central focus is the detailed, self-contained derivation of the Spencer 15-point filter and its interpretation within the same polynomial-reproduction framework as Savitzky–Golay filters.

## Numerical Experiments

The theoretical analysis is complemented by numerical experiments using synthetic and real-world time series data.

These experiments illustrate the tradeoff between smoothing short-term fluctuations and preserving responsiveness to changes in the underlying trend.

## Thesis

**Azeez, K. B. (2026).** *Theoretical Analysis of Filtering and Smoothing Techniques in Stochastic Time Series* [Master's thesis, Illinois State University].

[Read the full thesis in the Illinois State University repository](https://ir.library.illinoisstate.edu/etd/2399)

## Repository Status

This repository currently provides an overview of the thesis and links to the official university publication. Supporting code, numerical experiments, and figures may be added as they are prepared for public release.
