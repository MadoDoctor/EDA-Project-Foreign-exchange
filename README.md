# EDA-Project-Foreign-exchange
In this repository I did exploratory data analysis of foreign exchange rates

Github link to repository: https://github.com/MadoDoctor/EDA-Project-Foreign-exchange

# Importing

In this exploratory data analysis we worked with packages:

* NumPy;
* Pandas;
* Matplotlib;
* Seaborn;
* CSV;
* Datetime.

![Importing](https://user-images.githubusercontent.com/74544370/115556080-112e2200-a2d2-11eb-9909-4315587655f9.png)

# Data pre-processing

![Data](https://user-images.githubusercontent.com/74544370/115555954-ec39af00-a2d1-11eb-87ca-8aa5d4a8c5db.png)

We removed the first column as it is repeating the index, then taked general info as shape and columns type.

## Training session with Euro column

We divided the "Time Serie" column into days, months, years and days of the week to find out on which day of the week the data is most absent:

![Euro with time serie](https://user-images.githubusercontent.com/74544370/115555909-e04ded00-a2d1-11eb-863f-19c385823e63.png)

We calculated on which day of the week the data are most absent, dropped all rows with no data and checked in which day of the week was the maximum and minimum value of Euro and the maximum and minimum values for each year.

## Working with all columns

Firstly we dropped all rows with no data. Then changed the column names to make them understandable. We taked mean value for each currency:

![Mean](https://user-images.githubusercontent.com/74544370/115555804-c3191e80-a2d1-11eb-8096-9f76fe3adbc3.png)

Mean value for each currency was to all years, we can take mean value for every year if we want.

# Plotting a graph by year for all columns

We moved all column names to one column and their values to another, by using matplotlib.pyplot we plotted lineplot:

![plot](https://user-images.githubusercontent.com/74544370/115556831-e8f2f300-a2d2-11eb-8440-91680d176fcc.png)

Then sorted currencies in descending order of their values:

![image](https://user-images.githubusercontent.com/74544370/115557098-30797f00-a2d3-11eb-8583-aaec35559c0a.png)

