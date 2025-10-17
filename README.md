# Netflix-Analysis
Exploratory Data Analysis of Netflix Dataset using Python, Pandas, Seaborn, and Plotly. Includes trends of movies vs TV shows, top genres, country-wise content distribution, and interactive visualizations.

## Dataset
- **File:** `Netflix Dataset.csv`
- **Columns:** 
  - `Title` – Name of the movie or TV show  
  - `Category` – Movie or TV Show  
  - `Type` – Genre(s) of the content  
  - `Release_Date` – Date of release  
  - `Director` – Director of the content  
  - `Cast` – Main cast  
  - `Country` – Country of production  
  - `Rating` – Content rating  

## Features & Cleaning
- Converted `Release_Date` to datetime and extracted `Year`.  
- Filled missing values for `Director`, `Cast`, `Country`, and `Rating`.  
- Extracted `Main_Genre` from `Type`.  

## Analysis & Visualizations
1. **Movies vs TV Shows released per year** – Line chart showing content trends over time.  
2. **Top 10 Genres** – Bar chart of most common genres on Netflix.  
3. **Movies vs TV Shows per Country** – Stacked bar chart of top 10 countries.  
4. **Country-wise Content** – Interactive choropleth map showing global distribution.  
5. **Growth of Popular Genres** – Trend lines for top 5 genres over years.  

## Libraries Used
- `pandas` – Data manipulation  
- `numpy` – Numerical operations  
- `matplotlib` & `seaborn` – Static visualizations  
- `plotly` – Interactive visualizations  

