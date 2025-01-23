**Advancing  Project Gutenberg**

In rdf I extract all the summaries of books in the Gutenberg Database.
I identify the ebooks lacking summary.
I create a google books API and search for their respective summaries in Google Books.
Google books returns me many different descriptions for different editions.
In few_shot I train a few shot model to only pick the best, most general description of books.
