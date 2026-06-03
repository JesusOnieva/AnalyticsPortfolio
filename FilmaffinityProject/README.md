# 🎬 Filmaffinity Data Analytics Project

Welcome! In this project, I cleaned and analyzed movie-rating historical data from **Filmaffinity**, a Spanish website similar to Letterboxd. The dataset was taken from Kaggle, and the goal was to extract insights based on different genres, countries and year of production.

---

## 📊 Project Objectives
* **Data Wrangling:** Extract and clean the Filmaffinity dataset using Python, removing data not in-scope for this project (such as tv series, short films) and formatting categorical variables and dates.
* **Data Visualization:** Build an interactive dashboard using different slicers, focused on clean aesthetics adapted to the original website.
---

## 🛠️ Repository Structure
The repository is organized into the following directories:
* `ProyectoFilmaffinity_Py/`: Data cleaning, EDA and some initial visualizations.
* `ProyectoFilmaffinity/`: Contains the Power BI (`.pbix`) file with the data model and interactive dashboard.
* `README.md`: This file, providing a comprehensive overview of the project.

---

## 🚀 Tech Stack & Tools
* **Python**: Used for data cleaning, initial preprocessing (Pandas) and visualizations with Plotly.
* **Power BI**: Used for ad-hoc changes (Power Query), custom DAX measures and creating the final analytical dashboard.

---

## ⚠️ Project Limitations
Acknowledging data constraints is a core part of sound business intelligence. This project carries the following limitations based on the available dataset:
1. **No vote count:** The Kaggle dataset did not include the vote count of each title, an important metric to discern how influential a title has been. To make up for this, visualizations are normally filtered to only include directors/countries with a certain title threshold.
2. **Temporal Constraint:** The dataset only includes titles up until the year 2020, therefore future titles are not in-scope for this project.
3. **Survival Bias:** For older titles, normally those that were well-received or had some sort of impact have lasted to the present day, whereas for more current titles, exposure is more spread. This is reflected in the average ratings per decade.
4. **Platform Bias:** The data reflects the specific user base and cultural demographics of Filmaffinity, which may skew differently compared to other global databases like IMDb or Rotten Tomatoes.

---

## 📈 Key Insights & Findings
* **Glass ceiling:** An average score of 7 is already very hard to achieve, with the title count dramatically decreasing in the high range of 6. This would show users are quite reluctant to give a film a high score (8 or more).
* **Genre differences:** Drama is clearly the favored genre across the board, with animation also being quite well-regarded, particularly before the 90s. On the other hand, horror and child-friendly occupy the last two spots, probably due to wide variety of uneven quality and lesser affinity with the userbase, respectively.
* **Country differences:** Overall, the USSR is quite a step above the rest of the countries, while Sweden and Japan are also part of the top 3, which is reflected in the top directors visualization. Looking at the lower range, it is striking that Spain and the US, the two countries with the most titles, are among the countries with the worst average, which could be explained by the survival bias limitation above.
* **Decade differences:** Even if there is _some_ negative correlation with the production decade, it wasn't strong enough to deem it as relevant. However, the data does show some preference for productions before the 80s, while the average tends to become more stable in the following decades. Again, this can be attributed to the survival bias of older titles. 

---

## 📬 Contact
If you have any questions, suggestions or would like to connect and talk about data analytics (or cinema), feel free to reach out:

* **LinkedIn:** [linkedin.com/in/jesusonievapalomar](https://www.linkedin.com/in/jesusonievapalomar)
