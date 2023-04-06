# Class Four Notes (401)

## Data Modeling

### nosql vs sql[^1]

- Relational database is suitable for the complex query intensive environment, and non-relational database is suitable for hierarchical data storage.
- SQL can be scaled by adding more rows/columns, noSQL can be scaled by adding more properties to expand the key-value pair.

### sql modeling techniques[^2][^3]

- A "One-to-Many" relationship is when a table can be related to more than one entry in another. They can be related using the primary key and foreign keys
- A primary key generally focuses on the uniqueness of the table. It assures the value in the specific column is unique. A foreign key is generally used to build a relationship between the two tables.

### Videos[^4]

- Keywords are called using `SELECT`, and parameters are called using `WHERE`
- In normalization, columns are assigned to tables in such a way that each business fact is stored only once, or in other words, a table should not contain duplicate data.[^5]
- "One-to-One" is when one record in one table is associated with one record in another table(ex. ID to Customer Name), "One-to-Many" is when one record in a table can relate to more than one entries to another table (ex. one dormatry rented to many students), "Many-to-Many" is multiple records in one table can be associated with multiple records in another table (ex. many customers can purchase many products).

 [Back to main page](https://mirandalu2020.github.io/reading-notes/)

## References

[^1]:https://www.thegeekstuff.com/2014/01/sql-vs-nosql-db/?utm_source=tuicool
[^2]:https://www.essentialsql.com/get-ready-to-learn-sql-7-simplified-data-modeling/
[^3]:https://byjus.com/gate/difference-between-primary-key-and-foreign-key/#:~:text=1-,A%20primary%20key%20generally%20focuses%20on%20the%20uniqueness%20of%20the,relationship%20between%20the%20two%20tables.
[^4]:https://www.youtube.com/watch?v=ZS_kXvOeQ5Y
[^5]:https://www.sciencedirect.com/topics/computer-science/normalized-schema#:~:text=In%20normalization%2C%20columns%20are%20assigned,should%20not%20contain%20duplicate%20data.

