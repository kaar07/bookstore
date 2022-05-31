# Ideas for Tables/Relations in Database
Title
Author
Publication
Year of Publication
Original Year of Publication
Genre
Number of pages
Binding
Rating
----------------------------------------

The following SQL tables are required.


Author and his books
  // One table for each author
  Title
  Genre
  Rating
  Price

Publication and their books
  // One table for each publication house
  Title
  Author
  Genre
  Year of Publication
  Rating
  Price

Genre and the books
  // One table for each genre
  Title
  Author
  Publication house
  Rating
  Price

Books in general
  // Table containing all data on books

  Title
  Author
  Publication
  YOP
  Orgiginal YOP
  Genre
  Number of pages
  Binding Type
  Rating
  Price
