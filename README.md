# Movies-Analysis

“An exploratory data analysis across three major movie platforms—Disney, IMDB, and Netflix—to uncover trends in revenue, ratings, content distribution, and cross-platform insights.”

---

## 📁 Project Structure

Movies-Analysis/
│
├── data/               # Raw CSV datasets
├── notebooks/          # Exploratory Jupyter Notebooks
├── visuals/            # Graphs and analysis images
├── README.md           # Project documentation
└── requirements.txt    # Python dependencies

## Table of Contents

1. Overview
2. Exploratory Visuals  
3. Project Results and Insights  
4. Methodology  
5. Data Sources  
6. Contributing  
7. Future Plans  
8. Author  
9. License  

---

## 1. Overview

This repository houses analyses that compare Disney, IMDB, and Netflix catalogs through revenue trends, rating distributions, content breakdowns, and cross-platform comparisons. Insights are presented via charts, summary tables, and narrative commentary.

---

## 2. Exploratory Visuals

- Revenue trend line charts for each platform  
- Distribution histograms of ratings  
- Bar plots of genre counts per platform  
- Heatmaps comparing cross-platform rating overlaps  

---

## 3. Project Results and Insights

- Disney blockbuster revenue peaked in the 2010s, with a notable surge post-2015.  
- IMDB ratings follow a long-tail distribution, skewed towards 6–8 stars.  
- Netflix has a 60:40 split between TV shows and movies in its catalog.  
- Cross-platform titles show a 15% overlap in top-ranked releases.

### `Results`


<img width="689" height="391" alt="DisneyInflation" src="https://github.com/user-attachments/assets/9140c9af-af02-41f2-b1f0-9eaa2ea1d7d4" />

### 🏰 Disney Movie Trends

  Line plot of inflation-adjusted gross over the years.

<img width="678" height="391" alt="IMDBRating" src="https://github.com/user-attachments/assets/9071da22-4c32-44db-bed4-b74c85b637dc" />

### 🎥 IMDB Ratings Exploration
- Ratings vs review count correlation  
- Genre distribution and review sentiment 

<img width="580" height="433" alt="NetflixContent" src="https://github.com/user-attachments/assets/ac9c3f77-e49e-4a5f-81ff-d9ad1a091ad3" />

### 📺 Netflix Content Breakdown
- Ratio of TV Shows vs Movies over time  
- Popular genres and content growth by year

<img width="702" height="391" alt="Comparison" src="https://github.com/user-attachments/assets/1e6fc4da-e72a-48f3-91d0-9676eb7f9806" />

### 🔗 Cross-Platform Insights
- Overlapping titles across IMDB and Netflix  
- Comparative ratings and storytelling styles

<img width="610" height="425" alt="MoviesPiechart" src="https://github.com/user-attachments/assets/9c178440-8ceb-4e67-8d4f-da79a08b4874" />

### Dataset Size Pie Chart
- IMDB entries make up roughly 54% of the combined data
  - Netflix contributes about 30%
- Disney accounts for the remaining 16%
  - Netflix Content Breakdown
- TV Shows represent 62% of Netflix’s catalog in our sample
  - Movies make up 38%
  Together, these pies show that IMDB dominates our merged datasets, and that Netflix skews heavily toward series over films.
---

## 4. Methodology

- Data Cleaning  
  - Dropped duplicates and rows with missing core fields  
  - Standardized date formats and numerical columns  

- Data Integration  
  - Fuzzy matched movie titles across datasets  
  - Aligned rating scales to a uniform 0–10 range  

- Analysis Tools  
  - Python (pandas, NumPy) [Download Here](https://anaconda.org/anaconda/jupyter)  
  - Visualization (Matplotlib, Seaborn, Plotly)   

---

## 5. Data Sources

- `disney_movies.csv` — Disney  
- `imdb_movies.csv` — IMDB  
- `netflix_titles.csv` — Netflix  

Each file is loaded from the `data/` directory and described in the notebooks.

---

## 6. Contributing

Pull requests are welcome! For major changes, please:

1. Open an issue to discuss what you’d like to change.  
2. Fork the repository and create your feature branch (`git checkout -b feature/YourFeature`).  
3. Commit your changes (`git commit -m "Add new analysis"`).  
4. Push to the branch (`git push origin feature/YourFeature`).  
5. Submit a pull request.

---

## 7. Future Plans

- Sentiment analysis of user reviews across platforms  
- A recommendation engine prototype using collaborative filtering  
- Integration of box office budget vs. revenue correlations  

---

## 8. Author

Built by Thony — data whisperer, movie lover, and Python enthusiast.

---

## 9. License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
















