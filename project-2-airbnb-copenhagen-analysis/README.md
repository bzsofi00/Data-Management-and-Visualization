# Copenhagen Airbnb Market Analysis

A data analytics project examining Airbnb's market performance in Copenhagen, developed as part of the **Data Management and Visualization** course at Copenhagen Business School. The project combines data preparation, exploratory analysis, PostgreSQL database management and Tableau dashboard development to identify business performance drivers, market trends and growth opportunities.

## Project Objectives

The objective was to assess Airbnb's business performance in Copenhagen and identify critical success factors and opportunities for growth.

The analysis was designed to provide actionable insights for three main stakeholder groups:

- **Management:** Understand the overall market situation and monitor key business performance indicators.
- **Operational Teams:** Identify factors influencing host performance and guest satisfaction.
- **Business Development Teams:** Discover promising neighbourhoods and opportunities to expand the accommodation market.

## Interactive Tableau Dashboards

Explore the three interactive dashboards through the Tableau Story:

**[Open Airbnb Copenhagen – Tableau Story](https://public.tableau.com/app/profile/meng.yun.lu/viz/Airbnb_dashboard_17354801209280/Story1)**

The Tableau Story brings together three dashboards:

1. **Overview Dashboard** – Overall Airbnb market performance in Copenhagen.
2. **Host Information Dashboard** – Host performance, response times and Superhost analysis.
3. **Neighbourhood Information Dashboard** – Geographical market trends, pricing and growth opportunities.

## Data Preparation and Exploratory Analysis

The project started with a dataset containing **20,909 listings and 75 variables**. Data preparation involved:

- Removing irrelevant columns and handling missing or inconsistent values.
- Identifying and addressing outliers and potential sources of bias.
- Standardising neighbourhood names and correcting formatting issues.
- Filtering listings based on review counts to focus on more established listings and reduce the influence of small review samples.
- Creating additional calculated fields, including average ratings by neighbourhood and accommodation type.
- Exploring relationships between pricing, ratings, reviews and other listing characteristics.

Following the filtering process, the dataset contained **10,503 listings and 72 variables**, before further column reduction.

Exploratory analysis was conducted to understand the characteristics of the Copenhagen Airbnb market and identify patterns relevant to business performance.

## Database Management

The cleaned dataset was imported into a **PostgreSQL database** to provide a centralised data source for the project team.

Tableau was connected directly to PostgreSQL, allowing dashboards to retrieve data from a shared database and ensuring consistency across the analysis.

This approach also enabled team members to work with the same updated data source when making adjustments or extending the analysis.

## Tableau Dashboard Overview

### 1. Overview Dashboard

<text color="secondary" weight="medium" size="sm">Strategic performance overview</text>

Provides management-level insights into the overall Airbnb market in Copenhagen.

Key metrics and visualisations include:

- Number of listings, average price, average rating, number of hosts and acceptance rate.
- Geographical distribution of listings, prices and reviews across neighbourhoods.
- Accommodation supply by neighbourhood and room type.
- Average guest ratings across neighbourhoods.

The dashboard helps identify established markets, understand geographical differences and highlight areas with potential for further development.

### 2. Host Information Dashboard

<text color="secondary" weight="medium" size="sm">Host performance and guest satisfaction</text>

Examines host characteristics and identifies factors associated with stronger listing performance.

Key areas of analysis include:

- Top hosts ranked by total reviews.
- Relationship between host response times and guest ratings.
- Distribution of Superhosts and non-Superhosts.
- Performance differences between Superhosts and other hosts.

The dashboard highlights host practices associated with stronger guest engagement and satisfaction, providing opportunities to improve overall host performance.

### 3. Neighbourhood Information Dashboard

<text color="secondary" weight="medium" size="sm">Geographical market analysis and growth opportunities</text>

Explores differences across Copenhagen's neighbourhoods to identify promising areas for business development.

Key areas of analysis include:

- Monthly booking patterns and seasonal demand.
- Distribution of listings across neighbourhoods.
- Average accommodation prices by area.
- Comparison of neighbourhood-level guest ratings.
- Opportunities to expand accommodation supply in less developed areas.

The dashboard helps identify differences in market maturity, affordability and guest experience across Copenhagen.

## Key Findings and Business Recommendations

The analysis revealed several insights into Airbnb's Copenhagen market:

- **Host responsiveness matters:** Hosts responding within an hour achieved the highest average rating (4.81), highlighting the importance of timely communication for guest satisfaction.
- **Superhost performance:** Superhosts represented approximately 21.5% of hosts and generally demonstrated stronger performance in response times and guest ratings.
- **The city centre is a key market:** Indre By had the highest average accommodation prices and strong guest engagement, making it an important area for Airbnb's business.
- **Growth opportunities in surrounding neighbourhoods:** Valby, Vanløse and Amager Øst offered more affordable accommodation options while maintaining relatively comparable guest ratings.
- **Seasonality influences demand:** Booking activity increased significantly during the summer months, highlighting the importance of seasonal market strategies.

Based on these findings, the project proposed three main recommendations:

1. **Improve host performance:** Encourage hosts to reduce response times and work towards achieving Superhost status through better communication and guest experience management.
2. **Strengthen the city centre market:** Focus on improving guest experience ratings in Indre By to maintain the performance and long-term sustainability of this important market.
3. **Explore opportunities in emerging neighbourhoods:** Promote affordable, high-potential areas such as Valby, Vanløse and Amager Øst to attract budget-conscious travellers and expand market reach.

Overall, the recommendations aim to improve host performance and guest satisfaction while supporting Airbnb's sustainable growth in Copenhagen.

## Tools and Technologies

- **Python:** Data preparation and exploratory analysis
- **PostgreSQL:** Database management and centralised data storage
- **Tableau:** Interactive dashboard development and data visualisation
- **Data Analytics:** Statistical analysis, KPI development and business performance assessment

## Academic Context

**Course:** Data Management and Visualization  
**Course Code:** CDSCO2402U  
**Institution:** Copenhagen Business School
