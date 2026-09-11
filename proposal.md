# Pittsburgh Regional Transit Ridership Recovery Analysis – Proposal

**Jillian MacIntire**

## 1. Research Question

How did weekday ridership recovery after COVID-19 differ across Pittsburgh Regional Transit bus, rail, and incline service compared with 2019 levels?

## 2. Dataset

- **Dataset:** Pittsburgh Regional Transit Monthly Average Ridership by Route
- **Source:** Pittsburgh Regional Transit through the Western Pennsylvania Regional Data Center (WPRDC)
- **URL:** https://data.wprdc.org/dataset/prt-monthly-average-ridership-by-route
- **License:** Creative Commons Attribution
- **Retrieved:** September 10, 2026
- **File size:** about 1.87 MB

## 3. Grain

- One row represents the average ridership for one PRT route, during one month, for one day type (weekday, Saturday, or Sunday).
- 26,483 total rows and 26,483 unique Route + Mode + Month_Start + Day_Type combinations.

## 4. Comparison

- **Split by:** Mode (Bus, Rail, Incline)
- **Measure:** Avg_Riders
- Use weekday ridership, with 2019 as the pre-pandemic baseline and 2020-2025 as the recovery period.

## 5. Planned KPIs

- Average weekday ridership by mode
- Ridership recovery rate compared with 2019
- Year-over-year ridership change

## 6. Why Either Result Matters

- If recovery differs across modes, it could show that bus, rail, and incline ridership changed differently after COVID-19.
- If recovery is similar across modes, it could show that ridership changed in a similar way across the transit system.
