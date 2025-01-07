# Netflix Content Analysis

## Overview
This project is an exploratory data analysis (EDA) of Netflix’s content library. The aim is to uncover key trends, patterns, and insights about the movies and TV shows available on Netflix. This project demonstrates data cleaning, visualization, and storytelling skills, making it a valuable addition to any data science portfolio.

## Key Questions Answered
1. **How has Netflix’s content evolved over the years?**
   - Trends in the number of movies and TV shows added each year.
   - Total content additions and changes in strategy.

2. **Which countries contribute the most content to Netflix?**
   - Country-wise distribution of content.
   - Dominance of certain regions, such as the United States and India.

3. **What insights can we gain about Netflix’s content diversity?**
   - Content type distribution (Movies vs. TV Shows).
   - Analysis of genres, ratings, and durations.

## Dataset
- **Source**: Netflix data containing information about movies and TV shows.
- **Size**: 7,787 entries.
- **Key Columns**:
  - `type`: Movie or TV Show.
  - `title`: Name of the content.
  - `director` and `cast`: Key contributors.
  - `country`: Origin of the content.
  - `date_added`: When the content was added to Netflix.
  - `rating`, `release_year`, `duration`: Content characteristics.

## Steps Taken
### 1. Data Exploration
- Reviewed dataset structure and summary statistics.
- Visualized missing data using heatmaps.
- Identified significant missing values in `director`, `cast`, and `country` columns.

### 2. Data Cleaning
- Imputed missing values for `rating` with the mode.
- Converted `date_added` column to a datetime format.
- Addressed other inconsistencies in data types.

### 3. Data Analysis and Visualization
#### Content Trends
- Visualized the number of movies, TV shows, and total content added over the years.
- Observed a sharp rise in content additions from 2016 to 2019, with a peak in 2018-2019 and a decline post-2020.

#### Country Contributions
- Created a pie chart showing the percentage of content contributions by country.
- Found that the United States contributes 48.1% of all content, followed by India at 17.4%.

#### Diversity Analysis
- Examined content distribution by type (movies vs. TV shows).
- Analyzed the most frequent genres and ratings.
- Highlighted patterns in content duration.

### 4. Insights and Interpretations
- Netflix’s content addition strategy shows a focus on aggressive expansion during the mid-2010s, followed by a potential shift post-2020.
- The dominance of U.S. content reflects Netflix’s home market strategy, while significant contributions from India showcase its growing focus on international markets.
- Content diversity in terms of genres and ratings indicates an effort to cater to varied audiences.

## Tools and Technologies Used
- **Python**: For data cleaning and analysis.
- **Libraries**:
  - `pandas`, `numpy`: Data manipulation.
  - `matplotlib`, `seaborn`: Static visualizations.
  - `plotly`: Interactive visualizations.
- **Jupyter Notebook**: For creating the analysis.

## How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/daniyaljunjua/Data-Analysis-Projects.git
   ```
2. Navigate to the folder:
   ```bash
   cd Data-Analysis-Projects/netflix-analysis
   ```
3. Install the required libraries:
   ```bash
   pip install -r requirements.txt
   ```
4. Open the Jupyter Notebook:
   ```bash
   jupyter notebook netflix_analysis.ipynb
   ```
5. Run all cells to reproduce the analysis.

## Conclusion
This analysis of Netflix’s content library highlights:
- Significant growth in content additions up to 2019, followed by a decline.
- Strong dominance of U.S. content, with India emerging as a key contributor.
- A diverse catalog catering to a wide range of audience preferences.

While the analysis provides valuable insights, some limitations include missing data for key columns and potential biases in the dataset. Future work could include predictive modeling to forecast content trends or genre-based analysis for deeper insights.

## Future Scope
- Build a predictive model to forecast future content additions.
- Perform a genre-specific analysis to uncover audience preferences.
- Extend the analysis to include external datasets, such as user ratings or reviews.

## Acknowledgments
This project was made possible using publicly available Netflix data and open-source libraries. Special thanks to the data science community for their resources and tools.

