# IMDb Movies Analysis Dashboard

## 📌 Project Overview
An interactive Power BI dashboard focused on analyzing global IMDb movie trends, revenue distributions, and audience preferences. This project showcases data engineering, advanced DAX modeling, and custom UI design to transform cinema data into meaningful business and cinematic insights.

## ❓ Business Questions
- What is the total global revenue generated, and how does it trend over time?
- How do movie revenues distribute across high and moderate profit tiers?
- Who are the top 5 highest-grossing directors in cinema history?
- How do critics' ratings compare directly to audience preferences for each film?
- Which films are most popular and frequently watched among Arab audiences?

## 🛠️ Tech Stack
- 📊 Power BI Desktop – Report creation and advanced interactive analytics.
- 🎨 Canva – Visual identity and custom dashboard background design.
- 🧠 DAX & Power Query – Used for data cleaning, text parsing, and building intelligent metrics.

## 🚀 Features & Logic
### 1. DAX Measures (Centralized Metrics)
Calculated measures were organized in a dedicated (_Measures) table to ensure performance optimization and clean code structure:
- Total Gross Revenue: The total global box office revenue accumulated across all records ($56B).
- Total Movies: Total number of unique movies analyzed (748 films).
- Average IMDb Rating: The mean rating score provided by the general user audience.
- Average Metascore: The mean rating score provided by official critics.
- Meta Score Out of 10: A normalized DAX calculation adjusting the critic score to a 10-point scale for direct, balanced comparison with IMDb ratings.

### 2. Custom Calculated Columns
The core data modeling involved creating custom columns within the main dataset to enhance segmentation and visual interactivity:
- Revenue Category: A classification column dividing movies into high and moderate profit tiers based on financial performance.
- Movie Stars: A concatenated text column merging principal actors (⁠Star1⁠, ⁠Star2⁠, ⁠Star3⁠, ⁠Star4⁠) into a single field optimized for tooltips.
- HQ Poster Column: A calculated URL column designed to pull and render high-quality movie posters within report elements

### 3. Key Performance Indicators (KPIs)
Direct high-level visibility into core project scope metrics:
- Total Revenue: $56B
- Total Movies: 748 
- Total Directors: 426
- Global Avg Critics Rating: 77.5/100
- Global Avg Audience Rating: 7.9/10
- Arab Picks Total Gross: Selection changes dynamically as the user interacts with the movie sample images (posters), instantly updating the detailed analytics for that specific film.

### 4. Advanced Visual Components & UX
- Arab Audience Track: A dedicated, interactive analysis section showcasing movie popularity trends in the Arab region, based on personal research and surveys.
- Revenue Over Time & Profit Distribution: Features a line chart for historical trends and a Pie Chart that segments movies into High vs. Moderate profit tiers
- Top 5 Directors by Gross: A bar chart pinpointing the top 5 directors driving the highest cinematic revenue.
- Audience vs Critics: Ratings by Movie: Utilizes a Clustered Column Chart to contrast critic scores directly against audience ratings. This chart is enhanced with a Dynamic Tooltip that instantly reveals the specific Director and Star Cast upon hovering.

## 💡 Key Insights
- Market Evolution: Box office revenues showed a massive historical surge over the years, driven by modern production scaling and global distribution.
- Commercial Distribution: 65% of the analyzed movies fall into the "Moderate Grossing" category, while 35% achieve "High Grossing" status, showing the realistic commercial spread of elite movies.
- Director Influence: Steven Spielberg leads the industry in total gross revenue, highlighting how elite directors act as primary drivers for commercial success.
- Rating Alignment: While audience and critics ratings generally align on cinematic quality, minor gaps exist in certain movies, often influenced by the popularity of the director or lead cast.
- Cultural Relevance: The dedicated Arab Picks track highlights high engagement with global blockbusters, allowing users to interactively view global metrics per movie (e.g., selecting Home Alone reveals its massive $286M global gross revenue).

## 📸 Screenshots

### 1. Dashboard Overview Page
![Overview Page]([YOUR_HOME_PAGE_IMAGE_LINK_HERE](https://github.com/AlshahraniAfaf/Top-IMDb-Movies-Project/blob/main/Overview_Screenshot.png))

### 2. Dashboard Insights
![Dashboard Insights](YOUR_DASHBOARD_IMAGE_LINK_HERE)

---
Developed by: Afaf Alshahrani
Tools used: CSV file, Power BI, DAX, Power Query, Canva.
