**Data Description** 

* The data is taken from : https://www.kaggle.com/datasets/dylanjcastillo/7k-books-with-metadata
  
* It contains 6810 rows and 12 columns each describing some details about the book

**Problem motivation**

* With the help of these data we can create a book recommender system which takes recent searches of users and recommend his/her new suggestions based on the rating and the descriptions.

**The 7k books data set contains below 12 columns:**

* isbn13 : International Standard Book Number, a unique identifier for books(After 2007).

* isbn10 :  International Standard Book Number, a unique identifier for books(Before 2007).

* title : The name of the book.

* subtitle : Additional details about the book like novel, history, etc.
 
* authors : Name of the writer who wrote the book.

* categories : The type of content the book falls into, like fiction, non-fiction, mystery, etc.

* thumbnail :  It would typically refer to a small, representative image for each book.

* description : In short summary of the content of a book.

* published_year : The year in which that particular book is published.

* average_rating :  Average rating (out of 5) based on reader reviews or a specific rating system.

* num_pages : How many pages a particular book contains.

* ratings_count : Number of the people who gave rating for the book.

**Methodology**

* Taking a clear problem statement and searching for a data in kaggle.

* Loading the data(CSV file) without using pandas.

* Creating a nonnormalized database.

* Designed entity relationship diagram(ERD).

* Creating normalized database based on ERD with 5 tables.

* Inserting data into the tables in normalized database.

* Analysis using the sql queries and displaying the plots.
