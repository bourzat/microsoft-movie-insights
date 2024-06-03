# Microsoft Movie Insights

Author: [Ilyas Suleman Bourzat](https://www.linkedin.com/in/ilyas-bourzat-894353260/)

## Overview
This project aims to provide strategic insights to Microsoft's new movie studio through an in-depth Exploratory Data Analysis (EDA). We will be examining variuos datasets from [IMDB](https://www.imdb.com/), [Box Office Mojo](https://www.boxofficemojo.com/), [The Movie Db](https://www.themoviedb.org/) and [The Numbers](https://the-numbers.com/) - we'll be trying to identify Box Office trends and impactful movie performance metrics. This analysis will mainly be focused on what type of films are highly successful and in turn translating these findigs into actionable recommendations for Microsoft's film production strategy.

## Business Problem 
Microsoft is planning to enter the movie industry by establishing a new movie studio. However, the movie industry is highly competitive and involves significant financial risks. To ensure the success of its new venture, Microsoft needs to make data-driven decisions regarding which types of movies to produce, when to release them, and how to allocate budgets effectively. The primary business problem is to identify the factors that contribute to a movie's commercial success and use these insights to guide strategic decisions, thereby maximizing the chances of producing successful movies and achieving a strong return on investment.

## Steps
1. **Business Understanding:** Understanding the stakeholders problem and goal they want to achieve.
2. **Data Understanding:** Gathered information about the data to understand it better.
3. **Data Preparation:** Processed and cleaned the data to ensure accuracy.
4. **Exploratory Data Analysis (EDA):** Conducted EDA to uncover trends and patterns.
5. **Recommendations:** Provided strategic recommendations based on analysis.


## Data
All the data used in this project has been obtained from a various credible sources and can all be found [here](https://github.com/bourzat/microsoft-movie-insights/tree/main/zippedData).


## Methods
This projects uses exploratory data analysis to uncover trends in the data. All relevant libraries such as `pandas`, `matplotlib` and `seaborn` have been used.

## Further reading
To find out more about this project, checkout the [notebook]() or [presentation]().

## Repository Structure
```
├─ .DS_Store
├─ .gitignore
├─ .ipynb_checkpoints
│  └─ Microsoft_Movie_Insights-checkpoint.ipynb
├─ Images
│  ├─ .DS_Store
│  ├─ Boxplot.png
│  ├─ ERD.png
│  ├─ Relsease_Date_bargraph.png
│  ├─ Top_Genre_bargraph.png
│  └─ microsoft2.png
├─ Microsoft_Movie_Insights.ipynb
├─ README.md
├─ microsoft-movie-insights-presentation.pdf
└─ zippedData
   ├─ .DS_Store
   ├─ bom.movie_gross.csv.gz
   ├─ im.db.zip
   ├─ rt.movie_info.tsv.gz
   ├─ rt.reviews.tsv.gz
   ├─ tmdb.movies.csv.gz
   └─ tn.movie_budgets.csv.gz
```

## Repository Navigation
### Key Files and Directories
#### .gitignore
Lists files and directories that should be ignored by Git. This helps keep the repository clean from unnecessary files.

#### .ipynb_checkpoints/

Contains checkpoint files for Jupyter Notebooks. These are automatically created and updated by Jupyter.

#### Images/

This directory contains all the images used in the project. These images include visualizations and diagrams such as:
* **Boxplot.png**: Boxplot visualization.
* **ERD.png**: Entity-Relationship Diagram.
* **Relsease_Date_bargraph.png**: Bar graph showing release dates.
* **Top_Genre_bargraph.png**: Bar graph showing top genres.
* **microsoft2.png**: Additional relevant image.

#### Microsoft_Movie_Insights.ipynb

The main Jupyter Notebook containing the project's code, data analysis, and visualizations. Open this file to explore the project's workflow and findings.

#### README.md

The README file provides an overview of the project, including the business problem, objectives, data sources, and instructions for running the analysis.

#### microsoft-movie-insights-presentation.pdf

The presentation file summarizing the project's findings, recommendations, and business implications. Use this for a quick overview of the project and its results.

#### zippedData/

This directory contains the compressed data files used in the analysis. These include:
* **bom.movie_gross.csv.gz**: Box Office Mojo data on movie gross earnings.
* **im.db.zip**: IMDb database.
* **rt.movie_info.tsv.gz**: Rotten Tomatoes movie information.
* **rt.reviews.tsv.gz**: Rotten Tomatoes reviews.
* **tmdb.movies.csv.gz**: TMDB (The Movie Database) movies data.
* **tn.movie_budgets.csv.gz**: Data on movie budgets.
