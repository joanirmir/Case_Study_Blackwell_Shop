# Case_Study_Blackwell_Shop/ BI project

Goal of the project: Which component like weight/number of pages/type has an influence on the book price?
Can you predict the price looking at this components? Is there any trend to discover related to the publication_date and the category?


Description of the dataset
Source: https://www.kaggle.com/arthurio/books-from-blackwells-bookshop?select=blackwell_shop_cleaned.csv
Content: Books metadata downloaded from the official site using web scraping and API. 
In the cleaned version price names were renamed to distinguish between 
prices in pounds and euros and some columns were transformed to numbers.
Number of rows: 11573
Number of features: 27
isbn, publication_date, euro_price, discount_euro, type, category, link_book_page, name, subtitle, edition, author, gbp_price, discount_gbp, isSecondHand, publisher, published_country, imprint, language, no_of_pages, height, width, spine, weight, salesRank, short_blurb, long_blurb, blurbReview
Datatype of the columns: 
isbn                   int64
publication_date      object
euro_price           float64
discount_euro        float64
type                  object
category              object
link_book_page        object
name                  object
subtitle              object
edition               object
author                object
gbp_price            float64
discount_gbp         float64
isSecondHand            bool
publisher             object
published_country     object
imprint               object
language              object
no_of_pages           object
height               float64
width                float64
spine                float64
weight                 int64
salesRank            float64
short_blurb           object
long_blurb            object
blurbReview           object

Plan:

Day 1 - Exploring the data(discovering patterns/spotting anomalies) and start to clean the data

Day 2 - Continuaing with cleaning the data: 
- Replacing null values and drop columns if necessary
- Removing typos
Starting with Visualizing

Day 3 - Finding unexpected patterns

Day 4 - Making the presentation/ Storytelling
