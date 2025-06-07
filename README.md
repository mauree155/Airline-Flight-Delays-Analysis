# Airline-Flight-Delays-Analysis
### Project Overview
This project provides a comprehensive view of airline flight delays across the United States in 2015. By analyzing 5,000,000+ flight records from the U.S. Department of Transportation’s Air Travel Consumer Report, this project uncovers patterns in flight volumes, cancellation reasons, and delay trends. An interactive Power BI dashboard was developed to deliver these insights visually and empower data-driven decision-making by airlines, airport authorities, and logistics partners.

### Business Problem
#### Airline Flight Delays
Flight delays and cancellations are a persistent challenge in commercial aviation, impacting both airline profitability and customer satisfaction. This project aims to address key questions:
1. How does overall flight volume vary by month and day of the week?
2. What percentage of flights experienced departure delays in 2015? Among those, what was the average delay time?
3. How does the percentage of delayed flights change over the year? What do you think about flights departing from Boston (BOS)?
4. How many flights were cancelled, and what were the primary reasons (weather, airline issues, etc.)?
5. Which airlines demonstrate the best and worst on-time performance?

### Data Source
The dataset used in this analysis was shared with me by **Quantum Analytics** during my training. It originates from the **U.S. Department of Transportation’s Air Travel Consumer Report** for the year **2015**, covering over **5 million Airline names**
- Flight number
- Origin and destination airports
- Flight distance
- Scheduled and actual departure/arrival times
- Reasons for delays and cancellations
  
**Note:** This rich and comprehensive dataset provides a robust foundation for data-driven insights into airline performance, operational efficiency, and seasonal patterns.

### Tools
- **Power BI**: Data cleaning, transformation, and interactive dashboard design.
- **Power Query**: Used within Power BI for data preparation and transformation.
- **DAX (Data Analysis Expressions)**: Calculated columns and measures to derive insights and KPIs.
- 
### Dashboard
The interactive Power BI dashboard presents a clear, visual narrative of airline performance in 2015. Key dashboard elements include:
- Flight Volume by Month & Day of Week
- Departure Delay by City
- Arrival Delay and Departure Delay Counts
- Cancellation Breakdown by Reason
- Top 5 Airlines with the Most Departure Delays

![image](https://github.com/user-attachments/assets/768630c2-64ae-4a4d-a00b-b191f52731da)

### Processes
#### Step 1: Data Cleaning and Transformation
•	Removed duplicates and irrelevant columns.
•	Standardized date/time formats for accurate delay calculations.
•	Extracted Month, Day of Week, and City columns to enable deeper analysis.
•	Created calculated measures for departure delay, arrival delay, and cancellation rates.
#### Step 2: Dashboard Design and Storytelling
- Built an intuitive Power BI dashboard with slicers for city, airline, and cancellation reason.
- Integrated key metrics:
  - Total flights
  - Total cancelled flights
  - Average delay times
  - Delay and cancellation breakdowns by airline and city- Designed clear visuals (line charts, pie charts, and bar charts) to make complex data easy to interpret.
  - Enabled dynamic exploration of trends across months, cities, and airlines.

### Key Insights
The comprehensive analysis of 2015 U.S. airline flight data revealed several critical patterns and areas of concern:
#### Flight Volume & Seasonality
- Peak Flight Volume: July recorded the highest flight activity with 521,000 flights, while February saw the lowest at 429,000 flights.
- Weekly Patterns: Weekends, specifically Saturdays and Sundays, consistently showed the highest flight volumes, contrasting with midweek (Wednesdays), which had the lowest.
#### Departure Delays
- Total Delays: 1,218 departure delays were observed across 14 airlines.
- City-Level Analysis: Boston (BOS) emerged as the top city for departure delays, accounting for 35.75% of major city-level delays.
- Operational Efficiency: The average departure delay across all flights was 9.37 minutes, indicating both systemic challenges and opportunities for improvement.
#### Arrival Delays
- A total of 5.71 million arrival delays were reported, signaling broader issues with airspace congestion, turnaround delays, and operational bottlenecks affecting timely arrivals.
#### Flight Cancellations & Causes
- Volume of Cancellations: 90,000 flights were cancelled, representing a modest but significant share of total flights in 2015.
- **Primary Causes:**
- Airline/Carrier-Related: 54.35% of cancellations were due to airline-specific operational factors (e.g., maintenance, crew issues).
- Weather-Related: Weather disruptions accounted for 28.11% of cancellations.
- Other Causes: Security concerns and National Air System issues contributed to the remainder.
#### Airline Reliability Performance
- Southwest Airlines: Accounted for the highest share of departure delays among the top 5 airlines (58.58%).
- Other Notable Carriers: United Airlines and Spirit Airlines also featured prominently among top contributors to departure delays, while Virgin America consistently outperformed in on-time departures.

### Recommendations
Based on these findings, the following targeted recommendations are proposed to enhance operational performance, passenger experience, and overall airline reliability:
#### Flight Volume & Operational Efficiency
- **Crew and Aircraft Scheduling**: Align crew availability and aircraft maintenance windows with peak travel periods—particularly during summer months and weekends—to ensure optimal resource utilization.
- **Capacity Management**: Expand airport and airline operational resources during high-volume periods (July–August) to mitigate operational strain and improve service delivery.
#### Delay Reduction Strategies
-**Boston (BOS) Focus**: Implement targeted operational interventions at Boston Logan International Airport to address congestion and turnaround challenges. Potential strategies include runway optimization, gate reassignment processes, and real-time traffic flow management.
- **Proactive Delay Management:**
 - Conduct root cause analyses to identify and mitigate bottlenecks causing the 9.37-minute average delay.
 - Enhance predictive maintenance programs and crew scheduling optimization to minimize unplanned disruptions.
   Cancellation Mitigation
- **Weather-Related Cancellations:**
  - Invest in advanced weather forecasting and monitoring systems.
  - Develop and refine contingency planning for rapid recovery and service restoration during weather-related disruptions.
- **Carrier-Related Cancellations:**
  - Undertake operational audits to pinpoint inefficiencies (e.g., aircraft turnaround times, crew scheduling gaps, maintenance practices).
  - Benchmark performance against top-performing airlines to adopt and tailor best-in-class operational strategies.
#### Airline Reliability Focus
- **outhwest Airlines:** Prioritize comprehensive operational reviews and targeted improvement initiatives for Southwest Airlines, focusing on minimizing departure delays and enhancing passenger satisfaction.
- **Industry-Wide Best Practices:**
  - Implement real-time analytics and monitoring systems to dynamically respond to emerging delays.
  - Strengthen collaboration with airport operators to improve gate turnaround efficiency and taxiway congestion management.

### Conclusion 
Here’s a simpler, yet still professional and well-rounded conclusion:
This analysis highlights both the challenges and opportunities within the U.S. airline industry in 2015. While strong flight volumes show healthy demand, issues like delays, cancellations, and airline-specific bottlenecks suggest a need for more efficient operations. The data points to the importance of better planning during peak periods, addressing weather and carrier-related cancellations, and focusing on operational improvements in key airports and airlines.
By taking these insights and translating them into practical actions, airlines and airports can improve reliability, customer satisfaction, and overall performance. Ultimately, a data-driven approach will be crucial for building a more resilient and competitive airline industry in the future.
