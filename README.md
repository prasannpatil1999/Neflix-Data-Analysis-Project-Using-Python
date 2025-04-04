# Netflix Data Analysis Project 

## Tables of Contents: 
- [Project Overview](#project-overview)  
- [Tools Used](#tools-used)  
- [Data Sources](#data-sources)  
- [Data Cleaning/Preparation](#data-cleaningpreparation)  
- [Key Business Questions Answered](#key-business-questions-answered)  
- [Project Files](#project-files)  
- [How to Use](#how-to-use)
- [Project PDF File](#project-pdf-file)
- [Insights & Findings](#insights--findings)  
- [Recommendations](#recommendations)  
- [Conclusion](#conclusion)
  
### Project Overview
This project analyzes Netflix's content library, user preferences, and streaming trends using exploratory data analysis (EDA). It uncovers insights into popular genres, top-rated content, release trends, and regional distribution. The findings help understand content consumption patterns and audience engagement, providing data-driven recommendations for better content strategy. 

### Tools Used
- Python
- Numpy
- Pandas
- Matplotlib
- Seaborn


### Data Sources
The mymoviedb.csv dataset contains information about movies and TV shows, including titles, genres, release years, ratings, duration, and user reviews. It serves as a valuable resource for analyzing content trends, audience preferences, and streaming patterns on digital platforms.

### Data Cleaning/Preparation
- In the initial data preparation phase, we performed the following tasks:

1. Data importing and inspection.
2. Assigned appropriate data types to columns (e.g.,Release_Date, Vote_Count, etc.).
3. Handled duplicates, handled null values, Created new columns from existing.
4. Corrected spelling errors, typos, and inconsistencies.
5. Created new columns for insights (e.g., Day, Month, Year).
6. Dropped unncessary columns (e.g., 'Overview', 'Original_Language', 'Poster_Url',)
  
### Key Business Questions Answered
 Q1: What is the most frequent genre in the dataset?
 Q2: What genres has highest votes ?
 Q3: What movie got the highest popularity ? what's its genre ?¶
 Q4: What movie got the lowest popularity? what's its genre?
 Q5: Which year has the most filmmed movies?
 

### Project Files
- 📊 "mymoviedb.csv" (Excel CSV File) - Contains all data for analysis.
- 📝 Problem Statement (Word  File) - Outlines the business questions and objectives.

 ### How to Use
1. Open the Excel file to explore the data.
2. Review the Problem Statement Word file to understand the key objectives.
3. Use the following Python Jupyter Notebook PDF file to get a quick view of the results for questions

### Project PDF File
#### 🏷️ Project Overview


[Neflix Data Analysis Project Insights and Findings (1).pdf](https://github.com/user-attachments/files/19582729/Neflix.Data.Analysis.Project.Insights.and.Findings.1.pdf)

### Insights & Findings
 Q1: What is the most frequent genre in the dataset?

**Results**
 - Drama genre is the most frequent genre in our dataset and has appeared more than 14% of the times among 19 other genres
 
 Q2: What genres has highest votes ?
 
**Results**
 - Drama Genre has the most vote count

 Q3: What movie got the highest popularity ? what's its genre ?

**Results**
 - Spider-Man: No Way Home has the highest popularity rate in our dataset and it has genres of Action , Adventure and Sience Fiction .
 
 Q4: What movie got the lowest popularity? what's its genre?

**Results**
-  The United States vs. Billie Holiday and threads these 2 movies have lowest popularity
- Movie "The United States" has Genre of Music, Drama, History, War, Drama and Science Fiction

Q5: Which year has the most filmmed movies?


**Results**
 - In year 2021 6.35% of movies out of total were released highest ever in a year
 

### Recommendations
- Prioritize Drama Content: Highlight Drama movies/shows in personalized recommendations and featured sections.

- Enhance Popular Movie Visibility: Promote Action, Adventure, and Sci-Fi movies like Spider-Man: No Way Home in watchlists.

- Improve Discoverability of Low-Popularity Films: Create "Hidden Gems" or "Underrated Movies" sections for lesser-known films.

- Highlight Movies from 2020: Curate year-based collections to showcase trending movies from 2020.

- Boost Personalization for Popular Genres: Fine-tune recommendations to emphasize highly rated and user-preferred genres.

### Conclusion
The Netflix Data Analysis Project provides valuable insights into genre popularity, audience preferences, and content trends. Drama emerges as the most frequent and highest-rated genre, while blockbusters like Spider-Man: No Way Home dominate popularity. The findings highlight the importance of genre-based recommendations, improved discoverability for underrated films, and enhanced personalization to optimize the Netflix browsing experience. 

### Author
- Prasannagoud Patil

### Email
- Prasannpatil31@gmail.com
