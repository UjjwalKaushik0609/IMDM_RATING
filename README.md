
# 🎬 IMDb Top 250 Movies – Web Scraping & Analysis
![Image](https://github.com/user-attachments/assets/b739e84b-a946-4c2d-b59d-5695bb26fdd2)
## 📌 About

This notebook demonstrates **web scraping and exploratory analysis** of IMDb’s Top 250
movies. Using Python, we collect data from IMDb and visualize key trends and rankings
among the top movies.

We leverage:

```
 pandas for data wrangling and analysis
 matplotlib for data visualization
```
## 🎯 Analysis Includes

```
 Ratings over time: How have Top 250 ratings changed across years?
 Most-voted movies: Which films collected the most user votes?
 Duration vs rating: Is there a relation between movie length and its IMDb score?
 Average rating per decade: What trends emerge if we group movies by decade?
```
## 🗂️ Data Sources

```
 IMDb Top 250 movies page (scraped live using Python)
```
⚙️ Workflow

1. **Web Scraping**
     Fetches the IMDb Top 250 list HTML (with requests)
     Parses movie titles, years, ratings, number of votes, and runtime
       (via BeautifulSoup)
2. **Data Cleaning & Structuring**
     Cleans and organizes into a pandas.DataFrame
3. **Data Analysis & Visualization**
     Plots and insights addressing the questions above

## 📊 Visualizations

```
 Line plot: Average ratings across years
 Bar chart: Movies with the highest user votes
 Scatter plot: Duration vs rating relationship
```

```
 Decade-wise charts: Trends in average ratings
```
## 🧑💻 Key Learnings

```
 Web scraping with requests and BeautifulSoup
 Extracting and cleaning tabular data
 Exploratory data analysis with pandas
 Effective plotting using matplotlib
 Finding insights from real-world entertainment data
```
## ✔️ Conclusion

This project shows how to collect, process, and interpret movie data from the web. The
workflow is **reproducible** and a great showcase for your data analysis and visualization skills.


## Color Reference

| Color             | Hex                                                                |
| ----------------- | ------------------------------------------------------------------ |
| Example Color | ![#0a192f](https://via.placeholder.com/10/0a192f?text=+) #000000f |
| Example Color | ![#f8f8f8](https://via.placeholder.com/10/f8f8f8?text=+) #f8f8f8 |
| Example Color | ![#00b48a](https://via.placeholder.com/10/00b48a?text=+) #00b48a |
| Example Color | ![#00d1a0](https://via.placeholder.com/10/00b48a?text=+) #00d1a0 |

