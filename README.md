# **Book-Recommendation-System**

<img src="Images\book3.png" alt="books" width="750" height="400">

#### **Authors**: 
[Alice Wamuyu](alice.wamuyu@student.moringaschool.com),
[Eva Moisasi](ava.moisasi@student.moringaschool.com),
[Fridah Kimathi](mailto:fridahnkirotekimathi@gmail.com) and
[Nicholus Magak](nicholus.magak@student.moringaschool.com).

## Overview
****
The goal of this project is to develop a machine learning model that can provide personalized book recommendations to users based on their reading history and interests. The model will analyze various factors, such as author, publication year, and user ratings, to identify books that the user is likely to enjoy but has not read yet.

## Business Problem
***
<p>As a rapidly growing online retailer, Jumia has a vast collection of books. Most self-published authors sell 250 books or less, regardless of how many different books they write. Traditionally published books sell around 3,000 copies on average, with only 250 of those sales in the first year. It's rare that books sell over 100,000 copies and even rarer to sell more than a million</p>
<p>An attributing factor to the poor sales of potentially good books in the public’s eye is that there are too many books that major recommenders can read which can also be fueled by people sticking to specific authors rather than exploring due to the fear of reading a potentially different genre than what their tastes are accustomed to.</p>
<p>To address this issue, Jumia can implement an A.I model that uses a collaborative filtering technique. By doing so, they will not only recommend books based on the customers’ ratings but also suggest books that are similar to the ones that the customer has shown an interest in</p>

## Data
***
# **Data Understanding**

The Book Recommendation Data used in this project is from <a href='https://www.kaggle.com/datasets/rxsraghavagrawal/book-recommender-system'> Kaggle.</a>. The data contained three files: 

* **_Users.csv_**

Contained the users. Some of the features in this file include user IDs (User-ID) which have been anonymized and map to integers. Demographic data such as (Location, Age)  was also provided where it was available. Otherwise, these fields contained null values.

* **_Books.csv_**

Contained books. Books were identified by their respective International Standard Book Number(ISBN).Some content-based information given (Book-Title, Book-Author, Year-Of-Publication, Publisher), was obtained from Amazon Web Services. In the case of several authors, only the first was provided. URLs linking to cover images were also given, appearing in three different flavors (Image-URL-S, Image-URL-M, Image-URL-L), i.e., small, medium, large. These URLs point to the Amazon web site.

* **_Ratings.csv_**

Contains the book rating information. Ratings (Book-Rating) are either explicit, expressed on a scale from 1-10 (higher values denoting higher appreciation), or implicit, expressed by 0.

                    Visualizations:

                 i. Ratings
 <img src="Images\ratings.png"  width="650" height="400"> 

                 ii. Years vs. Number of books made
<img src="Images\years.png"  width="650" height="400">

                 iii. Average age of readers per country
 <img src="Images\newplot.png"  width="650" height="400"> 
 
                 iii. Top 10 Authors
 <img src="Images\authors.png"  width="650" height="400"> 
 
                 iii. Top 10 books
 <img src="Images\top10books.png"  width="650" height="400"> 
 
                 iii. Top 10 publishers
 <img src="Images\top10publishers.png"  width="650" height="400"> 
 
                 iii. Average Rating per Country
 <img src="Images\newplot1.png"  width="650" height="400"> 
 

## Modelling
***
 

## Evaluation
***


## Limitations
***


## Conclusion
***


## Recommendations
***


## For More Information
***
See the full analysis in the [Jupyter Notebook]() or review this [presentation]().

## Repository Structure
***

```
├── Data
├── Images
├── jumia Book Recommendation System.docx
├── PPT
├── README.md
└── index.ipynb
```
