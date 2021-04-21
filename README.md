# EDA-Project-Foreign-exchange
In this repository I did exploratory data analysis of foreign exchange rates

Github link to repository: https://github.com/MadoDoctor/EDA-Project-Foreign-exchange

# Installation

There are used libraries like NumPy, Pandas, Matplotlib, Seaborn, CSV and Datetime

# Data pre-processing

![Data](https://sun9-74.userapi.com/impg/kILY3jgmRfOlpIqbttDVVxQRqk_X7azutjem0Q/g-syVTl8Wng.jpg?size=1018x337&quality=96&sign=7c12d9d4be1f2171ab05cd1bbdb70078&type=album)

We removed the first column as it is repeating the index, then taked general info as shape and columns type

# We did a training session with Euro column

We divided the "Time Serie" column into days, months, years and days of the week to find out on which day of the week the data is most absent:

![Euro with time serie](https://sun9-58.userapi.com/impg/Vluy9UPmsZPYjNFEsdOF0zTw0UHgf0MW3xfNVA/rqCmHNembnI.jpg?size=167x175&quality=96&sign=d4f2b69821ff0afc813af60d3e313c9a&type=album)

We calculated on which day of the week the data are most absent, dropped all rows with no data and checked in which day of the week was the maximum and minimum value of Euro and the maximum and minimum values for each year.

# Working with all columns

Firstly we dropped all rows with no data. Then changed the column names to make them understandable. We taked mean value for each currency:

![image](https://user-images.githubusercontent.com/74544370/115555673-949b4380-a2d1-11eb-89c2-b6e9aee4e4db.png)

![Mean values](https://sun9-8.userapi.com/impg/LmESwn1rSfwMYcDmGGGr8GVI8KWggDjeUrh7kA/1_Le6kRPTDo.jpg?size=279x479&quality=96&sign=6fedc3c7121675e3c1e351839b86e018&type=album)
