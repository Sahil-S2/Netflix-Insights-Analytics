# Netflix-Insights-Analytics
![Netflix_front](Netflix_front.jpg)


# 🎬 Welcome to the **Netflix Content Analysis** Project!

This repository contains an end-to-end data analysis project on Netflix content. The analysis explores key attributes such as genre, ratings, content type, director, actor performance, and Netflix Originals vs third-party content. It combines robust SQL querying with powerful visual storytelling using Power BI.

---

## 📑 Table of Contents

- [📌 Project Overview](#project-overview)
- [🎯 Dataset Information](#dataset-information)
- [📝 Source](#source)
- [📊 Key Highlights](#key-highlights)
- [📂 Visualizations](#visualizations)
- [🔍 Technologies Used](#technologies-used)
- [📈 Installation and Usage](#installation-and-usage)
- [🔍 Project Structure](#project-structure)
  
---

## **Project Overview**

The objective of this project is to extract meaningful insights from Netflix's content database using SQL and present those insights through engaging Power BI dashboards.

The project explores:

- Performance of Netflix Originals vs. third-party content.
- Genre-wise trends in ratings and popularity.
- Consistently high-rated directors and versatile actors.
- The influence of runtime, certification, and content type on ratings.
- Popular countries producing top-rated content.

---

## **Dataset Information**

### Features:
- **Title**: Name of the movie or TV show.
- **Genres**: Primary and sub-genres.
- **Content Type**: Movie or TV Show.
- **IMDB / TMDB Rating**: Viewer ratings and popularity scores.
- **Runtime**: Duration in minutes.
- **Release Year**: Year the content was released.
- **Certification**: Age restriction tag.
- **Country**: Origin of the content.
- **Actors / Directors**: Cast and crew data.
- **Votes / Popularity**: Engagement metrics.

### Source:
The dataset was compiled from **Kaggle** and includes public metadata from **IMDB**, **TMDB**, and **Netflix’s API**-based content listing.

---

## **Key Highlights**

### 🎬 **1. Originals vs Third-party**
- Netflix Originals often have higher TMDB scores and receive more user votes.

### 🌍 **2. Country-wise Quality**
- UK and South Korea lead with consistently high IMDB ratings.

### 🎭 **3. Genre Trends**
- Documentaries and Biographies score the highest in viewer satisfaction.
- Action and Comedy remain the most popular in volume.

### 👥 **4. Director & Actor Performance**
- Directors like *Christopher Nolan*, *Rajkumar Hirani*, and *Martin Scorsese* consistently deliver high-rated content.
- Actors like *Helena Bonham Carter*, *Chris Pine*, and *Hiroki Yasumoto* have versatile genre footprints with good ratings.

### 🕒 **5. Runtime & Certification Impact**
- Ideal runtimes (90-120 minutes) correlate with better scores.
- Content certified "16+" or "18+" generally receives higher ratings due to mature themes.

---

## **Visualizations**

Power BI dashboards were created to bring insights to life:

- 📊 Netflix Originals vs Third-party Comparison
- 📈 Ratings & Popularity by Country
- 🎭 Genre-based Heatmaps and Score Trends
- 🎬 Director & Actor Score Rankings
- 🕒 Runtime vs Score Graphs
- 🎟️ Certification Impact on Rating

Each page uses slicers, tooltips, and custom visuals for interactive analysis.

---

## **Technologies Used**

- **Microsoft SQL Server**: Complex querying, data filtering, aggregation
- **Power BI**: Interactive visual dashboards and storytelling
- **Excel/CSV**: Data cleaning and formatting
- **GitHub**: Project version control and sharing

---

## **Installation and Usage**

### 🔧 For SQL Analysis:

1. Import the dataset into **Microsoft SQL Server**.
2. Run provided `.sql` scripts to explore each insight.
3. Export results to `.csv` for Power BI use.

### 📊 For Power BI Visualization:

1. Open `Netflix_Insights.pbix` using Power BI Desktop.
2. Connect to the cleaned `.csv` or SQL Server if live connection is preferred.
3. Explore the dashboards using filters and slicers.

---

## **Project Structure**

```
netflix-content-analysis/
│
├── data/
│   ├── netflix_titles.csv            # Original dataset
│   └── cleaned_data.csv              # Processed for Power BI
│
├── sql_queries/
│   └── netflix_analysis_queries.sql  # All 20+ SQL insights
│
├── visualizations/
│   └── Netflix_Insights.pbix         # Power BI Dashboard file
│
├── screenshots/
│   └── *.png                         # Dashboard screenshots
│
├── README.md                         # Project documentation
```




---

## **Future Work**

- Build machine learning models for predicting show ratings.
- Add time-series analysis for release trends and seasonality.
- Integrate sentiment analysis from user reviews and social media.

---

## **Contributions**

Contributions are welcome! Feel free to fork the repo, enhance visualizations, or optimize SQL queries.

---

## **License**

This project is licensed under the [MIT License](LICENSE).

---

## **Contact**

For feedback or collaboration, connect via [LinkedIn](www.linkedin.com/in/sahil-jena-067b1b301) or open an issue in this repository.

