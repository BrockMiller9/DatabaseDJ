### Conceptual Exercise

Answer the following questions below:

- What is PostgreSQL?
  PostgreSQL is software that allows people to manage databases by storing, organizing and managing large amounts of data. PostgreSQL allows you to create databases and tables within those databases storing information.

- What is the difference between SQL and PostgreSQL?
  postgreSQL is a type of database management that uses SQL. SQL is the standard language used across all databases.

- In `psql`, how do you connect to a database?
  \c database_name

- What is the difference between `HAVING` and `WHERE`?
  'WHERE' is used to filter data based on a specific condition. 'Having' is used in conjunction with 'GROUP BY' that filters data of those made by 'GROUP BY'

- What is the difference between an `INNER` and `OUTER` join?
  A 'INNER' join only returns data where there is a match in both tables being joined.
  A 'OUTER' joins all data from one table and any matching data from the other table being joined.

- What is the difference between a `LEFT OUTER` and `RIGHT OUTER` join?
  a 'LEFT OUTER' returns all the data from the left table and any matching data from the right.
  A 'RIGHT OUTER' returns all the data from the right table and any matching data from the left.
- What is an ORM? What do they do?
  An ORM is essentially a bridge between the database and the code we are writing. Instead of writing sql queiries manually we can use tools like SQLAlchemy to bridge the gap and write the queries for us.

- What are some differences between making HTTP requests using AJAX
  and from the server side using a library like `requests`?

  AJAX requests typically use JavaScript and are executed on the client-side while requests are executed from the server-side. AJAX could potentially lead to more network traffic and make the performance slower.

- What is CSRF? What is the purpose of the CSRF token?
  CSRF is a type of web attack that tricks a user into submitting information to a bad actor that they were not aware of. A CSRF token helps prevent these attacks from happening. The server generates a token and verifies that token when an http request is created. This helps prevent unauthorized requests from happening.
- What is the purpose of `form.hidden_tag()`?
  This function creates a hidden input field in a HTML form. In this input is included the hidden security token.
