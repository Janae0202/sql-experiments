# Favorite‑Books SQL Table



This repository stores the SQL schema and seed data for a small **`books`** table exported from my Khan Academy SQL project.  

The data represents five of my favorite books, each with a simple 1‑to‑5 rating.



## File layout



| File | Purpose |

|------|---------|

| **khan_table.sql** | `CREATE TABLE` statement plus five `INSERT` statements that populate the table. |



Content preview  [oai_citation:0‡khan_table.sql.txt](file-service://file-1jdJ1ZwE8uyvox3KQeTJLB)



```sql

CREATE TABLE books (

  id     INTEGER PRIMARY KEY,

  name   TEXT,

  rating INTEGER

);



INSERT INTO books VALUES

  (1, 'Catcher in the Rye', 5),

  (2, 'All About Love',     4),

  (3, 'Harry Potter',       3),

  (4, 'Hunger Games',       2),

  (5, 'Crime and Punishment', 1)

