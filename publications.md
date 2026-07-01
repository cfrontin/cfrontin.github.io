---
layout: default
title: Publications
---

# Publications

[Frontin, C. and Millstein, D., 2026, May. Financial-technical co-design for capital-intensive, resource-responsive energy systems. In _Journal of Physics: Conference Series_ (Vol. 3224, No. 2, p. 022050). IOP Publishing.](https://doi.org/10.1088/1742-6596/3224/2/022050)

- gap:
  - wind energy systems generate energy that varies significantly on a minute-to-minute, hour-to-hour, month-to-month, and even year-to-year basis
  - wind energy systems are financed on a monthly or quarterly basis
  - wind energy systems are designed _almost always_ to maximize annually-averaged production or cost-of-energy metrics
  - once set, initial design decisions determine how productive _and how variable_ the output of a wind energy system will be on each of these timescales
- methodology:
  - create a model for hourly revenue as a function of wind turbine design
    - using simple physics-based wind turbine model
    - use hourly meteorology data for wind resource characterization
    - price energy offtake assuming merchant operation with real-time market CAISO hub data
  - reduce revenues to monthly cashflows and pair with assumed debt expenses
    - for simplicity assume 100% debt model
  - visualize how variation in designs creates net profit and profit variability
- results:
  - only for one site in California, based on a five-year period of resource and market data, and subject to Biden-era tax policy
  - you can trade some overall profit for less variability, measured by the cash flows in the 5th percentile month
  - on average the worst month return on investment gets two basis points better for each basis point worse the mean profit gets
  - _however_ the first basis point of mean profit buys a four basis point return in terms of improvement of the 5th percentile month
  - the design control that drives this tradeoff is the specific power: the ratio of the generator size to the size of the rotor
    - we amortize the cost for a bigger generator every hour but we only exploit it in the most windy hours
    - a big rotor pushes the generator to its rated power during many more hours of the operating year
- holes:
  - all of the models are super simple, to prove the point
  - real wind energy systems are not financed on 100% debt
    - in reality, cashflow waterfall and equity portion ROI are key
  - intermittency is only one piece of "bankability": need to capture uncertainty of outcomes (and reliability, for that matter)
    - really, banks do financing based on their estimates of the mean (P50) and fifth-percentile (P95) AEP estimates due to uncertainty
    - this would require big changes to the financing analyses that are standard

[Frontin, C. and Darmofal, D.L., 2025. Small-sample Bayesian error estimation for ergodic, chaotic systems of ordinary differential equations. Journal of Computational Physics, 521, p.113559.](https://doi.org/10.1016/j.jcp.2024.113559)

- gap
  - TBD
- methodology
  - TBD
- results
  - TBD
- holes
  - TBD

[Brody, S. and Frontin, C., 2023, February. Revising the Stolen Bases Model. In _Baseball Prospectus_.](https://www.baseballprospectus.com/news/article/80420/pecota-2023-revising-the-stolen-bases-model/)

- gap:
  - in 2023, Major League Baseball took three rules changes from minor league baseball and implemented them in the majors: 1) limiting pick-off attempts, 2) adding a pitch clock, and 3) increasing the size of baseballs
  - each of these makes stealing bases easier and more appetizing for a team or player to attempt
  - there was/is no data for how much these would change going into the 2023 season except for data from minor league seasons
- methodology:
  - break the process of stealing (or getting caught trying) into pieces:
    1. stolen base opportunities (SBOs): when a player gets to 1B with nobody at 2B or to 2B with nobody at 3B
      - result in either a stolen base attempt (SBA) or not
    2. stolen base attempt (SBA): a player takes the plunge and tries to steal a base
    3. successful stolen base (SB) or caught stealing (CS)
  - model the rates each occur:
    - SBO/PA (stolen base attempts per plate appearance)
      - based on historical tendencies
    - SBA/SBO (attempts per opportunities)
      - based on historical tendencies 
      - add league-level adjustments based on the minor league data
    - SB/SBA (steals per attempt)
      - based on historical tendencies 
      - add league-level adjustments based on the minor league data
- results:
  - predictions of player-by-player steal numbers for 2023
  - in retrospect, everyone ran much more than we predicted...

