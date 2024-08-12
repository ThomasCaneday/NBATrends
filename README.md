# NBA Data Analysis Project

This project provides an in-depth analysis of NBA game data, focusing on comparisons between teams' performances across different seasons. The analysis utilizes various Python libraries, including `numpy`, `pandas`, `matplotlib`, `scipy`, and `seaborn`, to explore key metrics such as points scored, win probabilities, point differentials, and more.

## Project Structure

The Jupyter notebook in this repository is structured as follows:

### 1. Libraries and Data Import
- **Libraries:** `numpy`, `pandas`, `matplotlib`, `scipy`, and `seaborn` are imported for data manipulation, statistical analysis, and visualization.
- **Data Import:** The NBA game data is read into a pandas DataFrame from a CSV file.

### 2. Data Subsetting
- **2010 and 2014 Seasons:** The data is filtered to focus on the 2010 and 2014 NBA seasons for a detailed comparison of team performances.

### 3. Mean Points Difference
- **Knicks vs. Nets (2010):** The difference in mean points scored between the Knicks and Nets during the 2010 season is calculated.
- **Visualization:** Histograms are plotted to visualize the distribution of points for both teams.

### 4. Visualizations
- **Layered Histograms (2014):** Visual comparison of Knicks and Nets point distributions during the 2014 season.
- **Boxplot (2010):** A boxplot is created to compare the points scored by different teams in the 2010 season.

### 5. Statistical Analysis
- **Chi-Square Test:** A chi-square test is conducted on the relationship between game results and game locations in the 2010 season.
- **Covariance and Correlation:** The covariance and Pearson correlation between forecasted win probabilities and point differentials are calculated.
- **Scatter Plot:** A scatter plot is created to visualize the relationship between forecasted win probabilities and point differentials for the 2010 season.


## How to Run the Project

1. **Clone the repository:**
   ```bash
   git clone https://github.com/yourusername/nba-data-analysis.git
   ```
2. **Install the required packages:**
   ```bash
   pip install numpy pandas matplotlib seaborn scipy
   ```
3. **Run the Jupyter notebook:**
   ```bash
   jupyter notebook script.ipynb
   ```

## Results and Insights

- The analysis reveals key differences in team performances between seasons and provides insights into how forecasted win probabilities correlate with actual game outcomes.
