# Web-scrapping-using-python

Best Movie of All Time 

Using lxml in Python, select a movie of your choice on IMDB and scrape the following:

Title, genre (all individually, and then as a group and print via a loop), and overall rating of the movie 

All plot keywords (not just those on the front page, but those right below Storyline; you will have to use a separate url; 

Box Office information including the following

Budget

Opening Weekend USA

Gross USA

Cumulative Worldwide Gross

An important note here. Avoid using the tag attribute data-testid="" that IMDB uses. This will result in problems with xpath.

Wikipedia Tables 


I will scrape data from a Wikipedia page on the United States COVID-19 situation. In particular, this webpage contains a table towards the middle that presents the number of cases, deaths, recoveries, and hospitalizations by state. See the table (https://github.com/zannatus-saba/Web-scrapping-using-python/blob/main/img01.png)

Will scrape the data from this table and create a data frame. The data frame will contain the following five columns:

state_territory_name: the name of the state or territory


cases: the total number of cases for a state or territory

deaths: the total number of deaths per state or territory

recovery: the total number of recoveries per state or territory

hospitalization: the total number of hospitalizations per state or territory

I will come up with one XPath selector path per column of the <table>. Each completed column in the data frame and each XPath selector used to identify the <td> in the <table> for that column.
