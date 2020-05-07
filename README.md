# Covid-19 Star Schema

To analyze the Covid-19 data from CSSE at Johns Hopkins University, I created an easy-to-use star schema. This is generated as CSV files as well as a MySQL database.

![Covid-19 Star Schema](https://raw.githubusercontent.com/Martin-Boehler/covid19-star-schema/master/images/covid-19-star-schema.png "Covid-19 Star Schema")

In addition, the original datasets for confirmed, recovered and deaths, as well as for global and U.S. states, have been combined into one single staging file.

I have expanded all country data by latitude, longitude and continent.

To compare the spread of the virus for different countries, I created a dimension for 'days since 1000 cases'.

Total cases, cases per day and average cases per day are provided as a datatype dimension.

For direct local installation, all components run in Docker containers (MySQL, PhpMyAdmin and Jupyter).

I have also created some exemplary reports in Power BI.

___

Data source:

[COVID-19 Data Repository by the Center for Systems Science and Engineering (CSSE) at Johns Hopkins University](https://github.com/CSSEGISandData/COVID-19)

List of African countries: [Wikipedia](https://en.wikipedia.org/wiki/Africa)

List of American countries: [Wikipedia](https://en.wikipedia.org/wiki/Americas)

List of Asian countries: [Wikipedia](https://en.wikipedia.org/wiki/Asia)

List of European countries: [Wikipedia](https://en.wikipedia.org/wiki/Europe)

List of Oceanic countries: [Wikipedia](https://en.wikipedia.org/wiki/Oceania)

List of Eurasian countries: only the countries listed as European as well as Asian countries.

List of Asia-Pacific countries: all Asian and Oceanic countries.

___

If it is helpful for you, please give me a star on GitHub :)

If you find a problem, feel free to open an issue.

Contributers are welcome!