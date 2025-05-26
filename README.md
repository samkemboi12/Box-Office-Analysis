# MICROSOFT MOVIE STUDIO INSIGHT
Analysis to help Microsoft choose profitable movie types

##  Overview
This project provides **data-driven insights** to assist **Microsoft** as it establishes a new movie studio. It explores which **film types and genres** are most successful in terms of **ratings** and **box office returns**, helping Microsoft make strategic decisions in content production.

---

##  Business Problem
As a tech company with limited experience in the film industry, Microsoft faces key challenges such as:
- Identifying film genres that are currently performing well.
- Understanding what factors drive a movie's success.

This project solves these challenges by analyzing industry trends and delivering actionable recommendations based on data.

---
## Data Preparation Steps
- Loaded and merged IMDb and The Numbers datasets.

- Filtered top 10 genres based on frequency.

- Exploded multi-genre rows for genre-level analysis.

- Assigned experience levels to directors and actors.

- Binned production budgets and worldwide gross into Low, Medium, and High categories.

- Merged and cleaned all relevant tables for analysis.


##  Objectives
- Analyze what film genres and styles are both **highly rated** and **financially successful**.
- Guide Microsoft’s production team toward market-aligned content creation.
- Support leadership in making **informed, strategic decisions** as they enter the movie industry.

---

##  Sample Insight
![download](https://github.com/user-attachments/assets/5ae813e5-f334-409c-be32-56efe1acf200)



![Film Analysis Graph](plot.png)
![download](https://github.com/user-attachments/assets/027f43a5-fa5d-4491-81a9-04652960dd3c)


> *(Actual graph generated from the dataset showing trends in film genre or performance)*

---

---![download](https://github.com/user-attachments/assets/b4bb93bc-b961-4ce0-8da1-ac4110b0deb1)

## 📂 Dataset
The data used for this project includes:
- movie_budgets.csv
- im.db database
- Revenue (Box Office Gross)
- 
## Technologies Used
- Python
- Pandas & NumPy
- Matplotlib & Seaborn
- Jupyter Notebook
- Git & GitHub
## ANOVA test to assess significance

 **Director, Writer, and Actor Influence**
### Steps:

- Calculated number of movies each director has made (experience count)

- Mapped experience to names

- Filtered data to top 10 genres for focused analysis

---

##  How to Run 
Clone this repo:
