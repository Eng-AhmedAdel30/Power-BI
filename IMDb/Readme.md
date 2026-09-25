# 🎬 IMDb Movies Dashboard — Power BI

A Power BI dashboard providing an analytical overview of the top 250 IMDb-rated movies, covering ratings, vote counts, release decade trends, certifications, and director statistics.

---

## 📊 Overview

| Metric | Value |
| --- | --- |
| Total Votes | 162 Million |
| Average Rating | 8.31 |
| Number of Movies | 250 |
| Average Duration | 129.13 min |

---

## 📈 Visualizations

### 1. Rating by Movie Title

Horizontal bar chart ranking movies by their IMDb score. Top entries include:

- **The Shawshank Redemption** — 9.30
- **The Godfather** — 9.20
- **12 Angry Men / Schindler's List / The Dark Knight** — 9.00

### 2. # Movies by Decade

Line chart showing the distribution of top-rated movies across decades (1920s–2020s). The 2000s saw the highest concentration with **46 movies**, followed by the 1990s (42) and 2010s (43).

### 3. # Movies by Certificate

Donut chart breaking down films by content rating/certificate category, with the largest segment at **38.8%**.

### 4. No. of Votes vs. Rating

Scatter plot exploring the relationship between a movie's vote count (popularity) and its IMDb rating, ranging from \~1M to 3M+ votes.

### 5. # Movies by Director

Bar chart highlighting the most represented directors among the top 250, including: Akira Kurosawa · Christopher Nolan · Martin Scorsese · Stanley Kubrick · Steven Spielberg

---

## 🛠️ Tools & Data

- **Tool:** Microsoft Power BI Desktop
- **Data Source:** IMDb Top 250 Movies dataset
- **Theme:** Custom dark gold/charcoal IMDb-inspired color scheme

---

## 🚀 Getting Started

1. Open `lab1.pbix` in **Power BI Desktop**.
2. Refresh the data source if connected to a live dataset.
3. Use the **Filters** pane (right panel) to slice by certificate, decade, or director.
4. Navigate the **Overview** page tab at the bottom for the full report view.

---

## 📁 File

| File | Description |
| --- | --- |
| `lab1.pbix` | Main Power BI report file |
