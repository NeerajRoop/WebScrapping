# WebScrapping

This is a webscrapping python project that uses BeautifulSoup library to fetch top 50 movie details from IMDB, Metacritics and Rotten Tomatoes.
The movie details such as the Movie Title, Rating, Reviews and Genre information is collected and converted into CSV file and uploaded in the database.
the review style of each website is compared and similarity scores are generated.

The cosine similarity is used in this case.

similarity = cos(θ) = A.B /||A||.||B|| = (∑_(i=1)^n〖A_i B_i 〗)/(√(∑_(i=1)^n A_i^2 ) √(∑_(i=1)^n B_i^2 ))

We also find the similarity scores for the way in which the similar movies among the 3 websites are categorized based on their genre.
