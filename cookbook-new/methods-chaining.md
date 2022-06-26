# Methods Chaining

Need parentheses after the =

example:
```Python
df_mc_break_parens = (pd.read_csv('data/src/sample_pandas_normal.csv', index_col=0).assign(point_ratio=df['point'] / 100).drop(columns='state').sort_values('age').head(3))
```

- Newer methods:  query(), assign(), pivot_table(),  pipe() (user-defined methods)

Methods
- query:   .query('Embarked == "S"')


tables;

The pipes on either end of the table are optional.  at least three hyphens in each column of the header row.

|Command | Description |
|--- | :--- |
| pivot_table |  .pivot_table(values='Survived', columns='Pclass', index='ageGroup', aggfunc='mean') |


test 2:

 Command | Description |
| --- | :--- |
| git status | List all new or modified files |
| git diff | Show file differences that
| test | here we go <br/> test line |


line breaks:

Fruit         | Price         | Advantages         |
+===============+===============+====================+
| Bananas       | first line\   | first line\        |
|               | next line     | next line          |
+---------------+---------------+--------------------+
| Bananas       | first line\   | first line\        |
|               | next line     | next line        





## Qs

Using map w conditional values?  eg, contains 


