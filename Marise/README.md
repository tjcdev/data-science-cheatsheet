# Marise's Cheatsheet

### Pandas

In these examples we'll use this example dataframe.

| index | name | dob |
| --- | --- | --- |
| 134 | Billy Bob | 01-02-1990 |
| 542 | Charlie Chen | 13-06-1987 |
| 864 | Danny Dyer | 13-09-1989 |

| Description | Command |
| --- | --- |
| Get the `name` column from the dataframe | `df['name']` or `df.name`. |
| Get the second row from the dataframe | This gets the row by using the "pure" row index `df.iloc[1]`. But you can also get the same row by using the dataframe's indices e.g. `df.loc[542]` |
