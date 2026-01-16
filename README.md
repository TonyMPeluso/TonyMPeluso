## ⭐ Tony Peluso, PhD — Energy Systems Modeling & Utility Analytics

Engineer–Economist | Energy System Modeler | Utility Dashboard Developer | Climate Risk Analyst

I build analytical tools that help utilities and public agencies evaluate electrification impacts, transformer reliability, investment tradeoffs, and financial risk. My work combines engineering-economic modeling, Monte Carlo simulation, GIS, optimization, and interactive dashboards (Shiny for Python / R).

### 🔧 Technical Profile

** Energy Modeling & Simulation **

* Distribution system planning under electrification (EVs, heat pumps)
* Transformer thermal aging (IEC/IEEE C57.91)
* Monte Carlo & stochastic load modeling
* Linear programming (investment + dispatch models)

** Dashboards & Visualization **

* Shiny for Python, R Shiny, Plotly, leaflet
* Dynamic UI/UX for planners, regulators, and stakeholders

** Programming & Tools **

* Python (pandas, numpy, PuLP, matplotlib)
* R (tidyverse, ggplot2, sf, cancensus)
* SQL, Git/GitHub, GIS

** Climate & Financial Risk **

* TCFD-aligned climate vulnerability mapping (multi-hazard index)
* Extreme value theory (Hill estimator, EVT-based VaR/ES)
* Investment prioritization & marginal abatement cost analysis

** Quantitative Methods **
* Machine learning
* Time-series modelling
* Mathematical optimization

---

### 📊 Featured Projects

#### 🔹 Investment Optimization Dashboard

** Live App:** [View Dashboard](https://tonympeluso.shinyapps.io/investment_dashboard/)

Shiny for Python app for utility-scale capacity planning and hourly dispatch. Combines generation, storage, and demand-side technologies to evaluate cost vs. emissions tradeoffs.

* Investment + dispatch LP solver (PuLP)
* Net-load formulation with T&D improvements
* Proxy LCOE & marginal abatement curves
* Scenario-driven planning tool for utilities, consultants, and regulators

#### 🔹 Feeder-Level Winter Peak Microsimulation

** Live App:** [View Dashboard](https://tonympeluso.shinyapps.io/feeder_microsimulation/)

Bottom-up microsimulation for winter peak load analysis under heat-pump adoption, thermostat setbacks, and DR programs.

* Stochastic Monte Carlo engine
* Feeder-level overload probabilities
* Household-level energy and bill impacts

#### 🔹 Transformer EV Load Dashboard

** Live App:** [View Dashboard](https://tonympeluso.shinyapps.io/ZEV_CT_Forecast_Simulator_Tor/)

Interactive R Shiny dashboard modeling ZEV adoption, charging behavior, and transformer peak loading over time in Ontario cities.

* Clickable time-series + dynamic map
* Charging mix controls (Level 1 vs 2, evening behavior)
* Planning tool for municipalities and utilities

#### 🔹 Transformer Thermal Aging Simulator

Reliability modeling for distribution transformers using stochastic EV + heating loads. Implements IEC/IEEE C57.91 to estimate:

* Hot-spot temperature distributions
* Daily loss-of-life (LOL)
* Thermal exceedance risk (110/120/140 °C thresholds)
* DR impact on reliability

Includes Shiny dashboard for scenario visualization.

#### 🔹 Climate Infrastructure Risk Explorer

Composite multi-hazard vulnerability dashboard for infrastructure assets. Based on climate exposure, sensitivity, and criticality.

* Interactive map (Python Shiny)
* Vulnerability index builder + downloadable data
* Scenario support: 2020, 2030, 2050, 2080

#### 🔹 Financial Risk Dashboard (Extreme Value)

Dashboard using extreme value theory to compute:

* Value at Risk (VaR) and Expected Shortfall (ES)
* Stock return vs. risk visualizations
* Smoothed Hill estimator for threshold selection
* Demonstrates modeling capacity beyond energy

---

### 📚 Background & Contact

PhD in Energy Modeling & Policy | Certificate in Sustainability & Climate Risk (GARP)

**Location:** Montreal, QC
**Email:** [tonympeluso@gmail.com](mailto:tonympeluso@gmail.com)
**GitHub:** [TonyMPeluso](https://github.com/TonyMPeluso)
**LinkedIn:** [tony-peluso-phd](https://www.linkedin.com/in/tony-peluso-phd/)

**License:** MIT
All dashboards and models use open-source tools and reproducible methods.
