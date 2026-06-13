# 📋 Master's Final Group Project
This repository contains the exploratory data analysis for a comprehensive job market study conducted as our Master's Final Group Project. The project was commissioned by a Spanish headhunting agency seeking to understand current labor market trends across Europe. We analyzed job data from 2022 related to the salary range, location, work mode (hybrid, remote)... 
For this file, my contribution was focused on sections 5 to 9 of the notebooks.


## 🎯 Project Objectives
* **Data Wrangling:** Clean and validate job offer data across multiple countries, handling inconsistencies in salary formatting, currency variations, and categorical inconsistencies.
* **Exploratory Analysis**: Identify patterns in salary distribution, geographic concentration and sectoral trends.
* **Business Insights**: Provide actionable insights on labor market dynamics to support hiring strategy decisions.
---


## 📂 File Structure
Eda_MasterProject: Data cleaning, EDA and some initial visualizations, as well as the answers to the project questions.
README.md: This file, documenting the project.

---

## 🛠️ Tech Stack
* **Python**: Used for data cleaning, initial preprocessing (Pandas) and visualizations with Plotly.
* **Power BI**: NOTE: Power BI has not been included in this repository as my contributions were not as major.

---

## ⚠️ Project Limitations
1. **Temporal discrepancy:** The original dataset contained job offers from 2022, however, the project was done in 2025-2026, and the data we scraped was therefore from this timeline, meaning comparisons could not be done 1:1, but rather taking into account how the market had evolved and how the geopolitical situation had played a role in it.
2. **Geographic scope:** The dataset contained worldwide data, however, it was decided to focus exclusively on Spain, France (Paris) and the UK (London). Spain was prioritized, as it contained the highest number of job offers and it was the country the client was the most interested in. To enrich the analysis, Paris and London were also included as there was a significant volume from these locations and for geographical proximity. 
3. **Salary transparency:** For Spain in particular, it was noted that a significant percentage of the job offers (over 80%) did not include the salary range, which was not the case for the other analyzed locations. While this was an important location, this was a key insight too, as it reflected the opacity of the Spanish market compared to other countries. 
4. **Job categorization:** The job offers were re-categorized in different sectors as the initial categorization was not suitable (for instance, the category names were too similar), so we decided to do our own categorization, bearing in mind many of the job offers were related to the IT sector, so the categories were "Data", "Software", "Engineering" and "Executive". An "Other" category was created too for offers that could not fit into any of the other categories, but this was done by trial and error extracting the role name, prioritizing the role names with the highest count.
5. **Different currencies:** For the UK, we converted the GBP salary into EUR to establish clear comparisons. However, as we didn't have the exact date from when the data was extracted, we used an average from the year and month for those job offers (second half of 2022).

---

## 📈 Key Insights & Findings
* **Geographical saturation:** It was noted how most job offers (over 70%) were located in big hubs (Madrid, Barcelona, London, Paris), as well as the surrounding areas of the Spanish cities. 
* **Salary differences:** The average Spanish salary was dramatically lower than that of Paris and London. In fact, the London salary was over half the Spanish average. 
* **Remote work:** An uptick of hybrid work was noticed in both Madrid and Barcelona when compared to the to scraped data from 2025 and 2026.
* **Spanish market opacity:** As mentioned in the limitations, salary data from Spain was very often (80%) not included, which showed how opaque this information is. However, this showed opportunity as well, and it was suggested to the client to include this info as a differentiator and to be more appealing.

---

## 📬 Contact
If you have any questions, suggestions or would like to connect, feel free to reach out:

* **LinkedIn:** [linkedin.com/in/jesusonievapalomar](https://www.linkedin.com/in/jesusonievapalomar)
