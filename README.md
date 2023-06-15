# Querying a SQL database of home sales (*Challenge 22*)

This repository contains a mini-project in which I queried a database that contained several observations about different home sales.

## Author

Daniel R. Murillo Antuna: [@dan-murillo](https://github.com/dan-murillo)

## Overview of the Analysis

The mini-project in this repository contains a series of queries about a home sales database. I used *PySpark* and *SparkSQL* to get information about the average price of properties and their 'view' rating with different characteristics. For example, I generated a table with two columns, one of which contained the average price, rounded to 2 decimal places, of only the 4-bedrooms in the database and the other one which contained the grouped years when each property was sold. I also compared the runtimes between running queries on an uncached temporary table, a cached temporary table, and a cached and partitioned with *Parquet* temporary table.

The queries were ran on Google Colab, and all the code in this repository was optimised and thoroughly commented to make it easier to understand and work with.

## Contents of the repository

### The *Home_Sales.ipynb* Jupyter Notebook:

It contains the *Python* code used to run the queries.

## Data Reference

The dataset was generated by [edX Boot Camps LLC](https://www.edx.org/boot-camps).

```#Thank you for reading me!```

## Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.
Please make sure to update tests as appropriate.

## License

[MIT](https://choosealicense.com/licenses/mit/)
