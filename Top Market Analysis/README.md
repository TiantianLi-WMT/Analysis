# Top Market Analysis

## How do we select Top Market?
We find all essential information about each store, including:
1. current capacity (MPC)
2. 10 years demand forecast (FY24-FY34) (compare ubber bound rebaseline and one demand forecast) _(pending to compare results from one demand fcst, team having an updated version by end of week)_
3. future capacity under PU2.0 remode schedule (future MPC post FY25 remodel)
4. future capacity under PU2.0 and approved MFC (1100 MMFC, 1300 Gen1 AMFC)
5. UPLH average in past 12 weeks (for available ones only from Gunish)
6. order basket and size for OPD and unscheduled in past 3 months (Scheduled = OG_delivery + OG_pickup + In Home, Unscheduled = DFS + SFS)  
7. Unscheduled (DFS/SFS/FC-LMD): a separate metric to measure store demand

Once store level information is collected, we aggregate the results into each market based on the new market definition which generate a list of 2k non overlapping markets:
1. FY24 utilization
2. FY26 utilization with PU2.0
3. FY26 utilization with PU2.0 and MFC
4. FY29 utilization with PU2.0
5. FY29 utilization with PU2.0 and MFC
6. UPLH avg
7. Order basket and size
8. Unscheduled orders demand

Then assess for each BU:
1. What's the percentile for each metric, market demand, store demand, FY26 utilization: percentile is calculated based on national performance. 
2. How many markets / stores within a BU currently exceed MPC, etc.
