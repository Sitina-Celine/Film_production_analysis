
## FILM_PRODUCTION_ANALYSIS
# Project Overview
This project involves a comprehensive analysis of the film production industry using data-driven methods. The objective is to derive meaningful insights from film-related datasets to assist stakeholders in making informed decisions regarding film investments, genre popularity, and production strategies.

# Business Problem
The company now sees all the big companies creating original video content and they want to get in on the fun. They have decided to create a new movie studio, but they don’t know anything about creating movies. I was charged with exploring what types of films are currently doing the best at the box office.Then translate those findings into actionable insights that the head of your company's new movie studio can use to help decide what type of films to create.

# The Data
In the folder `zippedData` are movie datasets from:
* [Box Office Mojo](https://www.boxofficemojo.com/)
* [IMDB](https://www.imdb.com/)
* [Rotten Tomatoes](https://www.rottentomatoes.com/)
* [TheMovieDB](https://www.themoviedb.org/)
* [The Numbers](https://www.the-numbers.com/)

Because it was collected from various locations, the different files have different formats. Some are compressed CSV (comma-separated values) or TSV (tab-separated values) files that can be opened using spreadsheet software or `pd.read_csv`, while the data from IMDB is located in a SQLite database.

![movie data erd](https://raw.githubusercontent.com/learn-co-curriculum/dsc-phase-2-project-v3/main/movie_data_erd.jpeg)

Note that the above diagram shows ONLY the IMDB data. You will need to look carefully at the features to figure out how the IMDB data relates to the other provided data files.

I worked with the following datasets.
* `im.db.zip`
  * Zipped SQLite database
  * `movie_basics` and `movie_ratings` tables are most relevant
* `tn.movies_budget.csv`

# Tools used
The project utilizes the following tools:
- Python (Pandas, Matplotlib, Seaborn, SQLite3)
- Jupyter Notebook
- Tableau for visualization
- Git and GitHub for version control
- Power point for presentations

# Description of Data:
- movie_basics: Contains title, release year, genre, and runtime.
- movie_ratings: Contains average rating and number of votes.
- merged dataset: Combines financial and production attributes for detailed analysis.

Three Key Visualizations:
1. Top genres based on average profits
2. Relationship between production cost and profits
3. Evolution of production budgets over time by genre

# Key business question:
- Which film genres generate the highest average profit?
- Is there a correlation between production cost and profit?
- How have production budgets evolved over time across genres?
- How frequently do genre trends shift across the years?
# methodology
The analysis began with data cleaning and preprocessing, followed by exploratory data analysis (EDA). Relevant insights were visualized using Tableau to provide a clear understanding of trends and patterns. Key insights were summarized to address the business questions.

# conclusion
Summary of Conclusions:
- Certain genres consistently produce higher profits (e.g., Adventure, Action).
- High budgets do not always guarantee high profits; strategic budgeting is essential.
- Genre preferences and budgeting trends have evolved significantly over the years.
- A weak correlation was found between production cost and profit, suggesting other factors influence revenue.

This project highlights the power of data analytics in understanding the film industry. It provides valuable guidance for producers, investors, and marketers seeking to optimize film production decisions.

# commit history
The Git commit history for this project shows a progressive development from data cleaning and merging, to analysis, visualization, and final reporting. Commits reflect logical milestones and development checkpoints.

# organization
Folder Structure:
- Film_production_analysis/
  - student.ipynb
  - zippedData/ (Raw data)
  - README.md
  - .gitignore
  - presentation.pptx

The final notebook runs without errors and reflects the analysis presented in the slides.

# .gitignore
The .gitignore file excludes large files.
Examples of ignored files:
- large CSVs not necessary for repo storage

# Link to:
- Linkedin:https://www.linkedin.com/in/celine-sitina-80703b379/
- Tableau:https://public.tableau.com/app/profile/celine.sitinna/viz/MOVIESanalysis/Runtime