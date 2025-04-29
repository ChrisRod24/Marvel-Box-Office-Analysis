# Marvel-Box-Office-Analysis
Analyzing Marvel movie data: Budget vs Worldwide Earnings, Box Office Trends, and Movie Ratings.

## Visualizations
Here are some key visualizations from the analysis:

![Scatter Plot](https://github.com/your-username/repository-name/raw/main/[Budget_Earnings_Scatterplot](https://github.com/ChrisRod24/Marvel-Box-Office-Analysis/blob/main/Budget_Earnings_Scatterplot.png?raw=true))
![Bar Chart](https://github.com/your-username/repository-name/raw/main/Boxoffice_Revenue_Pivot & Bargraph)

## Overview
This project involves analyzing Marvel movie data to explore the relationship between **production budgets** and **worldwide earnings**. The analysis includes cleaning the raw data, creating insightful visualizations, and drawing conclusions on how budget correlates with earnings.

## Data Sources
The data used for this analysis comes from two main sources:
1. **Marvel movie data** (`marvel.csv`) containing the **budget** and **box office earnings** for each Marvel movie.
2. **Marvel reviews data** (`marvel_reviews.csv`) containing the **ratings** for each movie from Rotten Tomatoes, Metacritic, and CinemaScore.

## Data Cleaning and Preparation
### Step 1: Cleaning the Raw Data
1. **Removed unwanted characters** (e.g., dollar signs, commas) from the **Budget** and **Worldwide Earnings** columns.
2. Converted the **Budget** and **Worldwide Earnings** data into **numerical format** for analysis.
3. **Cleaned date and rating columns**, ensuring data consistency (e.g., formatting **release dates** properly).
4. Fixed data issues such as **N/A values** and missing or incomplete data in the columns.

### Step 2: Merging Data
1. Merged the two data sources (`marvel.csv` and `marvel_reviews.csv`) into one dataset based on the **movie title**.
2. Created a **combined dataset** that includes **movie title**, **budget**, **box office earnings**, and **ratings**.

---

## Visualizations

### 1. **Pivot Table: Total Worldwide Box Office Earnings by Year and Distributor**
- A **Pivot Table** was created to analyze the total **worldwide box office earnings** by year and distributor.
- The **distributor** filter allows you to examine how earnings evolved over time for different movie distributors.
- The **pivot table** provides a summary of earnings and can be filtered by **release year** and **distributor**.

### 2. **Bar Chart: Box Office Revenue by Year**
- A **bar chart** was created to show **box office revenue by year** for Marvel movies.
- The **x-axis** represents the **release year**, while the **y-axis** shows the **total worldwide box office earnings** for that year.
- This chart allows for a visual comparison of **box office performance** over time.

### 3. **Scatter Plot: Budget vs. Worldwide Earnings**
- A **scatter plot** was created to visualize the **relationship** between **production budget** and **worldwide earnings**.
- The **X-axis** represents the movie **budget** (in millions), while the **Y-axis** represents the **worldwide earnings** (in millions).
- Each point on the scatter plot represents a **movie**, and it helps identify how **high-budget movies** perform compared to **lower-budget ones**.
- Movies with **higher budgets** and **higher earnings** are typically positioned in the **top-right corner**, while movies with **lower budgets** and **lower earnings** are located in the **bottom-left corner**.

---

## How to Run the Project
1. **Clone the Repository**:
   To download and explore the project, clone the repository to your local machine:
   ```bash
   git clone https://github.com/your-username/repository-name.git
