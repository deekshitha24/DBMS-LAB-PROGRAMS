
LAB PROGRAM - 01
Consider the following schema for a Library Database: BOOK(Book_id, Title, Publisher_Name, Pub_Year) BOOK_AUTHORS(Book_id, Author_Name) PUBLISHER(Name, Address, Phone) BOOK_COPIES(Book_id, Programme_id, No-of_Copies) BOOK_LENDING(Book_id, Programme_id, Card_No, Date_Out, Due_Date) LIBRARY_PROGRAMME(Programme_id, Programme_Name, Address) Write SQL queries to

1.Retrieve details of all books in the library – id, title, name of publisher, authors, number of copies in each Programme, etc.

2.Get the particulars of borrowers who have borrowed more than 3 books, but from Jan 2017 to Jun 2017.

3.Delete a book in BOOK table. Update the contents of other tables to reflect this data manipulation operation.

4.Partition the BOOK table based on year of publication. Demonstrate its working with a simple query.

5.Create a view of all books and its number of copies that are currently available in the Library.

####################################################################################

LAB PROGRAM - 02
Consider the following schema for Order Database: SALESMAN(Salesman_id, Name, City, Commission) CUSTOMER(Customer_id, Cust_Name, City, Grade, Salesman_id) ORDERS(Ord_No, Purchase_Amt, Ord_Date, Customer_id, Salesman_id) Write SQL queries to

1.Count the customers with grades above Bangalore’s average.

2.Find the name and numbers of all salesman who had more than one customer.

3.List all the salesman and indicate those who have and do not have customers in their cities (Use UNION operation.)

4.Create a view that finds the salesman who has the customer with the highest order of a day.

5.Demonstrate the DELETE operation by removing salesman with id 1000. All his orders must also be deleted.

####################################################################################

LAB PROGRAM - 03
Consider the schema for Movie Database: ACTOR(Act_id, Act_Name, Act_Gender) DIRECTOR(Dir_id, Dir_Name, Dir_Phone) MOVIES(Mov_id, Mov_Title, Mov_Year, Mov_Lang, Dir_id) MOVIE_CAST(Act_id, Mov_id, Role) RATING(Mov_id, Rev_Stars) Write SQL queries to

1.List the titles of all movies directed by ‘Hitchcock’.

2.Find the movie names where one or more actors acted in two or more movies.

3.List all actors who acted in a movie before 2000 and in a movie after 2015 (use JOIN operation).

4.Find the title of movies and number of stars for each movie that has at least one rating and find the highest number of stars that movie received. Sort the result by movie title.

5.Update rating of all movies directed by ‘Steven Spielberg’ to 5
