_Summary_: in this tutorial, we will introduce you to a PostgreSQL sample database that you can use for learning and practice PostgreSQL.

We will use the DVD rental database for demonstrating the features of PostgreSQL.

The DVD rental database was ported from the sakila sample database for PostgreSQL with some adjustments. The DVD rental database represents business processes of a DVD rental store. The DVD rental database has many objects including:

+ 15 tables
+ 1 trigger
+ 7 views
+ 8 functions
+ 1 domain
+ 13 sequences

![alt text](http://www.postgresqltutorial.com/wp-content/uploads/2018/03/dvd-rental-sample-database-diagram.png)

PostgreSQL Sample Database Tables
There are 15 tables in the DVD Rental database:

+ actor – stores actors data including first name and last name.
+ film – stores films data such as title, release year, length, rating, etc.
+ film_actor – stores the relationships between films and actors.
+ category – stores film’s categories data.
+ film_category- stores the relationships between films and categories.
+ store – contains the store data including manager staff and address.
+ inventory – stores inventory data.
+ rental – stores rental data.
+ payment – stores customer’s payments.
+ staff – stores staff data.
+ customer – stores customers data.
+ address – stores address data for staff and customers
+ city – stores the city names.
+ country – stores the country names.



*References:*

- http://www.postgresqltutorial.com
