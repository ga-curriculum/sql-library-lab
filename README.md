# ![](https://ga-dash.s3.amazonaws.com/production/assets/logo-9f88ae6c9c3871690e33280fcf557f33.png) SQL Ladder Challengers

| Title                  | Type | Duration | Author               |
|------------------------|------|----------|----------------------|
| Library DB             | Lab  | 2:00     | Suresh Melvin Sigera |



## How to submit homework

### Setup

- Step 1. Fork the repository
- Step 2. Clone your fork
- Step 3. Open pgAdmin and find the Database Menu.
- Step 4. Right click on Database and select Create Database. Name this Database `library` and hit save.
- Step 5. Open the PSQL tool.


## Inspecting The Schema

Look critically at each line of the provided `schema.sql` file. Here's how one row breaks down...

**`id SERIAL PRIMARY KEY`**
- `id`: column name, how we will refer to this column
- `SERIAL`: the data type (similar to integer or string). It's a special datatype for unique identifier columns, which the db auto-increments.
- `PRIMARY KEY`: a special constraint which indicates a unique identifier for each row

Take a few minutes to research the other rows.

## Load The Schema

Load the schema into your database from the command line...


```bash
\i /Users/<yourname>/2023/abbottlabs/labs/sql-library-lab/schema.sql
```

## Loading A Seed File

We've provided a sql file that adds sample data into our `library` database.

Load that in so we can practice interacting with our data. Make sure to also look at its contents and see how authors and books are related.

```bash
\i /Users/<yourname>/2023/abbottlabs/labs/sql-library-lab/seed.sql
```

## Exercises

There are two exercises:

* [Basic Queries](basic_queries.sql) - SELECT, INSERT, UPDATE, DELETE
* [Advanced Queries](advanced_queries.sql) - JOINS

For each exercise, write your queries in the corresponding `.sql` file. Then run the file using the terminal:

```bash
\i /Users/<yourname>/2023/abbottlabs/labs/sql-library-lab/basic_queries.sql
```


### Submitting work

- Step 1. Create a folder for the specific homework
- Step 2. Push to your fork
- Step 3. Submit a pull request
- Step 3.1. Add first name, last name and comment

In the comment section, you must add the following:

```text
* Comfortability [0 to 5]
* Completeness [0 to 5]
* What was a win?
* What was a challenge?
* Any other comments
```
