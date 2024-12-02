# Web-scrapping
A look into movie statistics using data acquired via web scrapping

Movie_scraping.ipynb file contains the Python code, and Top 1000 Movies.csv is the file where the data is stored.

Objective:
The goal of this project was to answer the following questions:

1. What years had the most movies ranked in the top 1000?
2. What are the most common runtimes for the top 1000 movies?
3. What are the top 10 highest-grossing films in the top 1000 movies list?
4. What are the 10 lowest-grossing films in the top 1000 movies list?

To complete this task, two websites were used:
rinkworks.com – This site provided a list of the top 1000 IMDb movies and their hyperlinks. It was used because scraping the movie list directly from IMDb was quite challenging. The list had some flaws, including four repeated movies.
IMDb – The hyperlinks from the first site were used to scrape data from individual IMDb pages.
Due to the large volume of data (nearly 1,000 IMDb links), I cannot specify each link here. However, a list of all the links is printed in the program (Movie_scraping.ipynb). It takes 
approximately 15 minutes for the function I created to scrape all the IMDb pages.

Results:
At the end of the project, the questions were successfully answered. The most surprising discovery was how little some movies grossed. I double-checked the data with IMDb to ensure accuracy, and according to IMDb, the data was correct.

