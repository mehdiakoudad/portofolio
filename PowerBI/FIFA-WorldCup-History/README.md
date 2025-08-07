# 90 Years of FIFA World Cup History in Power BI

An interactive, story-driven dashboard visualizing the rich history of the FIFA Men's World Cup using Power BI.

---

## ​ Project Overview

This project dives into over 90 years of World Cup history and transforms raw historical match data into a visually engaging Power BI dashboard that answers key questions such as:

- Which country scored the most goals?
- Which country reached the most finals?
- Which year saw the most goals?
- Do host nations have an advantage?

---

##  Medium Post

A brief write-up of the project is available on Medium:

**[“90 Years of FIFA World Cup History in Power BI” by Mehdi Akoudad (3 min read)](https://medium.com/@akoudadmehdi01/90-years-of-fifa-world-cup-history-in-power-bi-3a0aba31f74d)**

The article provides an overview of the project’s purpose, design, and key insights. [oai_citation:0‡Medium](https://medium.com/%40akoudadmehdi01/90-years-of-fifa-world-cup-history-in-power-bi-3a0aba31f74d?utm_source=chatgpt.com)

---

##  Structure of the Report

### Page 1: **Overview**
- Presents big-picture trends across 21 World Cups.
- Visual elements include:
  - Finals reached by each country
  - Host nation win rate (~28.6 %)
  - Goal distributions per tournament (box plots)
- Top insights:
  - Total tournaments covered: 21
  - Germany leads in final appearances with 8—followed by Brazil and Italy [oai_citation:1‡Medium](https://medium.com/%40akoudadmehdi01/90-years-of-fifa-world-cup-history-in-power-bi-3a0aba31f74d?utm_source=chatgpt.com)

### Page 2: **By Tournament**
- Enables exploration of individual World Cup editions.
- Features:
  - Host nation for the year
  - Goals scored by each team
  - Geographical map of match locations
  - Tooltips displaying match details by city (e.g., A Coruña) [oai_citation:2‡Medium](https://medium.com/%40akoudadmehdi01/90-years-of-fifa-world-cup-history-in-power-bi-3a0aba31f74d?utm_source=chatgpt.com) [oai_citation:3‡Wikipedia](https://en.wikipedia.org/wiki/1990_FIFA_World_Cup?utm_source=chatgpt.com)
- Example given:  
  In 1938, hosted by France, the top goal scorers were Hungary and Brazil, with matches held in cities including Paris, Marseille, and Bordeaux [oai_citation:4‡Medium](https://medium.com/%40akoudadmehdi01/90-years-of-fifa-world-cup-history-in-power-bi-3a0aba31f74d?utm_source=chatgpt.com).

---

##  How It Was Built

### Data Preparation
- Used **Power Query** to:
  - Clean and standardize raw data
  - Harmonize team codes
  - Correct date formats [oai_citation:5‡Medium](https://medium.com/%40akoudadmehdi01/90-years-of-fifa-world-cup-history-in-power-bi-3a0aba31f74d?utm_source=chatgpt.com)

### Data Modeling & Metrics
- Created using **DAX** formulas to calculate:
  - Host nation win percentage
  - Number of finals reached by each country
  - Goal distributions for each tournament year [oai_citation:6‡Medium](https://medium.com/%40akoudadmehdi01/90-years-of-fifa-world-cup-history-in-power-bi-3a0aba31f74d?utm_source=chatgpt.com)

### Design & Interactivity
- Two-page report:
  - **Overview**: Trend analysis and big-picture insights
  - **By Tournament**: Drill-down details per World Cup
- Interactive features:
  - Hover tooltips that show match-level data (e.g., city, match results)
  - Map-based and other visual interactivity for richer exploration [oai_citation:7‡Medium](https://medium.com/%40akoudadmehdi01/90-years-of-fifa-world-cup-history-in-power-bi-3a0aba31f74d?utm_source=chatgpt.com) [oai_citation:8‡Medium](https://medium.com/%40akoudadmehdi01/90-years-of-fifa-world-cup-history-in-power-bi-3a0aba31f74d?utm_source=chatgpt.com)

---

##  Usage Instructions

1. Clone/download this repository.
2. Open the `.pbix` file in **Power BI Desktop**.
3. Navigate between the **Overview** and **By Tournament** pages.
4. Interact with slicers, maps, and tooltips to explore the data and uncover insights.

---

##  Future Enhancements

- **Expand Data Coverage**: Include additional tournaments or women’s World Cups.
- **Additional Metrics**: Consider appending stats such as assists, bookings, or attendance figures.
- **Visual Refinements**: Add trend lines or custom visuals to enrich storytelling.
- **Export Capabilities**: Enable users to export filtered data or visual snapshots.

---

##  Credits

- **Mehdi Akoudad** – Medium article and Power BI project inspiration [oai_citation:9‡Medium](https://medium.com/%40akoudadmehdi01/90-years-of-fifa-world-cup-history-in-power-bi-3a0aba31f74d?utm_source=chatgpt.com)  
- Open-source tools and data repositories used (add specifics here as needed).

---

Thank you for checking out this historical data visualization project. Let me know if you'd like help refining sections or adding visuals to the README!
