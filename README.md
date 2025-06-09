# CANADA ELECTRIC COMPANY - ELECTRICTY USAGE ANALYSIS  

## OVERWIER
This project documents and analyze the electricty usage pattern Canada Electric co., the primary electricity provider serving Peterborough, Ontario and surrounding rural communities since 1971.
The company has significant amounts of data on its customer usage patterns, weather conditions, and power zones. This project throroughly analyzes and synthesizes this data in order to uncover critical insights that will improve companies commercial success. 

## TECH STACK
- Programming language -> Python [Pandas / Seaborn]
- IDE -> Jupyter Notebook

## AREAS OF KEY INSIGHT'S
- Weekly consumption
- Daily usage patterns

## CONSUMPTION OVER TIME

![image](https://github.com/user-attachments/assets/8a2dfb6f-ed9b-45b4-9d19-40daae1a2f42)

### Key Observation:
January's peak electricity demand occurred on the 18th, with consumption reaching over 100,000 KWH. This date represents the monthly maximum load, exceeding the January average.

### Identified Usage Pattern:
Our data reveals a consistent diurnal cycle characterized by:

Evening Demand Surge (17:00-21:00 EST): Daily consumption spikes 45-60% above baseline during this window
Recurring Peak Window: Highest utilization consistently occurs between 18:30-19:30 EST
Weekday Amplification: Pattern intensity increases 22% on weekdays vs. weekends

### Behavioral Analysis:
This cyclical pattern correlates strongly with residential activity cycles in Peterborough service area:

### Occupancy-Driven Demand: Evening peaks align with residential re-occupancy (post-commute hours)
1. Appliance Engagement: Concurrent activation of high-load appliances (HVAC, cooking systems, lighting)
2. Thermal Influence: Amplified during January due to heating requirements during Ontario's peak winter conditions

### Strategic Recommendations:
1. Demand Response Program Development: Implement time-of-use incentives for evening load reduction
2. Launch "Peak Rewards" initiative for rural customers
3. Predictive Grid Management based on usage patterns
4. Deploy AI forecasting models using historical pattern data
5. Pre-position technical crews during predicted high-load days


### Customer Engagement
1. Develop educational campaigns on evening energy optimization
2. Introduce smart thermostat subsidy programs
3. Infrastructure Planning
4. Prioritize transformer upgrades in high-growth rural sectors

## CONSUMPTION BY THE DAY OF THE WEEK

![image](https://github.com/user-attachments/assets/5d5fa662-546e-4a7e-8601-e6dedfdd79e7)

### Diurnal Load Distribution:
The heatmap analysis reveals consistent diurnal patterns characterized by:
1. Evening/Night Peak Demand (19:00-21:00):
2. 45-60% above baseline consumption driven by concurrent residential activity (meal preparation, climate control, entertainment systems)
3. Early Morning Low-Utilization Period (04:00-07:00):
4. Maintains 30-40% below daily average
5. Gradual Morning Ramp-up (07:00-12:00):

### Day-of-Week Variance Analysis:

| Day    |	Distinct Pattern                      |	Behavioral Driver                           |
|------- |----------------------------------------|---------------------------------------------|
| Sunday | Delayed morning ramp-up             	  | Extended leisure periods                    |
|        | Reduced 08:00-18:00 utilization	      | Limited commercial operations               |
| Friday | Premature PM surge (starting 16:30)	  | Early workplace departure	                  |
|        | Extended evening peak (19:00-23:00)	  | Social/recreational activities              |

### Strategic Recommendations:
1. Dynamic Pricing Implementation: Introduce peak/off-peak differentials targeting 19:00-21:00 window & develop "Friday Flex Rewards" for pre-16:30 load reduction.
2. Develop temporal segmentation profiles (e.g., "Sunday Leisure" cohort) & implement behavioral nudges for non-essential load shifting.
3. Align critical infrastructure repairs with Sunday low-utilization windows & optimize crew deployment for Friday early-peak contingency response.
4. Leverage morning ramp period for solar energy integration

