# Dissertation

**Author**: Xintong Li  
**Degree**: MSc in Financial Mathematics, University of Edinburgh  
**Supervisor**: Dr Oana Lang  
**Date**: August 2025

## Project Overview

This repository accompanies the dissertation *"Interest Rate Modelling with Fractional Brownian Motion: Pricing and Hedging Implications"*:contentReference[oaicite:0]{index=0}.  
The project investigates how **fractional Brownian motion (fBm)** can be incorporated into classical short-rate models (Vasicek, CIR, Hull–White) to capture **long-memory effects** in interest rate dynamics.  

We develop and implement Monte Carlo simulation frameworks for pricing **zero-coupon bonds (ZCBs)**, **forward rate agreements (FRAs)**, and **interest rate options (Caplets/Floorlets)**, as well as analyzing **delta hedging strategies** under long-memory regimes.  

## Repository Structure

### Jupyter Notebooks
- **CH2_fbm_generation.ipynb**  
  Implements and compares different simulation methods for fractional Brownian motion (Cholesky, Davies–Harte).  
- **CH3_model_formulation.ipynb**  
  Constructs fBm-driven Vasicek, CIR, and Hull–White models; calibrates Hurst exponent from Bank of England data.  
- **CH4_derivative_pricing.ipynb**  
  Monte Carlo pricing of ZCBs, FRAs, Caplets/Floorlets; analyzes the effect of Hurst parameter on prices, volatility, VaR, and CVaR.  
- **CH5_hedging.ipynb**  
  Simulation of delta hedging strategies for FRA and Caplets under different Hurst regimes.  

### Data
- **BoE-Database_export.csv**  
  Official Bank Rate data from the [Bank of England](https://www.bankofengland.co.uk/monetary-policy/the-interest-rate-bank-rate), used for Hurst exponent calibration. 

### Configurations
- **LICENSE** – MIT License.  
- **README.md** – Project overview (this file). 

## Key Contributions
- Extend classical short-rate models with **fractional Brownian motion** to incorporate long-memory.    
- Price ZCBs, FRAs, and Caplets/Floorlets via **Monte Carlo simulation**.  
- Quantify the impact of the **Hurst parameter** on derivative pricing, volatility, and tail risk.  
- Analyze **delta hedging performance** and limitations in non-Markovian settings.  