# EDA-Project-Foreign-exchange
In this repository I did exploratory data analysis of foreign exchange rates

Github link to repository: https://github.com/MadoDoctor/EDA-Project-Foreign-exchange

# Importing

There are used libraries like NumPy, Pandas, Matplotlib, Seaborn, CSV and Datetime:

![Importing](https://user-images.githubusercontent.com/74544370/115556080-112e2200-a2d2-11eb-9909-4315587655f9.png)

# Data pre-processing

![Data](https://user-images.githubusercontent.com/74544370/115555954-ec39af00-a2d1-11eb-87ca-8aa5d4a8c5db.png)

We removed the first column as it is repeating the index, then taked general info as shape and columns type

# We did a training session with Euro column

We divided the "Time Serie" column into days, months, years and days of the week to find out on which day of the week the data is most absent:

![Euro with time serie](https://user-images.githubusercontent.com/74544370/115555909-e04ded00-a2d1-11eb-863f-19c385823e63.png)

We calculated on which day of the week the data are most absent, dropped all rows with no data and checked in which day of the week was the maximum and minimum value of Euro and the maximum and minimum values for each year.

# Working with all columns

Firstly we dropped all rows with no data. Then changed the column names to make them understandable. We taked mean value for each currency:

![Mean](https://user-images.githubusercontent.com/74544370/115555804-c3191e80-a2d1-11eb-8096-9f76fe3adbc3.png)

![Mean](https://sun9-8.userapi.com/impg/LmESwn1rSfwMYcDmGGGr8GVI8KWggDjeUrh7kA/1_Le6kRPTDo.jpg?size=279x479&quality=96&sign=6fedc3c7121675e3c1e351839b86e018&type=album)
