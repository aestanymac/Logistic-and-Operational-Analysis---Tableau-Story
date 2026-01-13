# Logistics Analytics – Tableau Story

## Project Overview
This project presents an exploratory data analysis and visual storytelling exercise focused on logistics and transportation operations. Using a synthetic dataset, the analysis aims to extract operational and strategic insights related to delivery performance, profitability, efficiency, and empty trips.

The final output is implemented as a **Tableau Story**, allowing a structured, narrative-driven exploration of key business questions: ([Story](https://public.tableau.com/app/profile/anna.estany.macia/viz/Practica2_17682542314680/Story1?publish=yes))

The dataset can be found on Kaggle: [[Logistics Operations Database]](https://www.kaggle.com/datasets/yogape/logistics-operations-database)
---

## Objectives
The main objectives of this project are to:

- Analyze logistics performance and operational efficiency
- Identify profitable and high-volume routes
- Explore driver efficiency and delivery punctuality
- Detect patterns in empty trips and their geographic distribution
- Communicate insights effectively through data visualization

---

## Why a Tableau Story?
While the project was initially conceived as a traditional dashboard, it evolved into a **Tableau Story** to:

- Guide the user through insights step by step
- Reduce cognitive overload caused by displaying too many metrics at once
- Provide context and narrative to each visualization
- Improve interpretability, especially given the balanced nature of the synthetic dataset

This approach prioritizes **data storytelling over KPI monitoring**.

---

## Visualizations Included
The story is composed of several key visualizations:

1. **On-time Delivery Map**  
   Geographic overview of delivery performance.

2. **Driver Efficiency Scatter Plot**  
   Relationship between efficiency metrics across drivers.

3. **Deviation from Average Loads (3-Year Comparison)**  
   Bar chart showing deviation from average performance by year.

4. **Route Profitability Matrix**  
   Scatter plot of margin vs. volume, with revenue represented by bubble size.

5. **Empty Trips Analysis**  
   Bar charts comparing absolute number and percentage of empty trips by city.

6. **Revenue Distribution by Industry Sector**  
   Boxplot comparing annual revenue contribution across customer sectors.

7. **Safety & Incidents Overview**  
   Breakdown of incident causes and identification of drivers with higher incident counts.

---

## Data Considerations & Limitations
- The dataset used in this project is **synthetic**, not real operational data.
- Many variables are intentionally balanced, which limits the visibility of strong trends.
- Some analyses that would be meaningful in a real-world scenario (e.g. maintenance efficiency, fuel optimization) do not show significant variation here.

These limitations are acknowledged and explicitly discussed in the Story.

---

## Interactivity & Accessibility Considerations
- Filters allow users to explore the data by time period, route, or city.
- Visual encodings (size, position, color) are used consistently to aid interpretation.
- Color choices and chart types were selected to enhance readability and avoid unnecessary complexity.
- Narrative annotations support users with less technical background.

---

## Repository Structure
- /tableau
- /data
- /docs

---

## How to View the Project
- Open the `.twbx` file using **Tableau Public**
- Or view the published story via Tableau Public ([Story](https://public.tableau.com/app/profile/anna.estany.macia/viz/Practica2_17682542314680/Story1?publish=yes))

---


## License
This project is licensed under the MIT License.
