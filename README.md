# Module_3_Challenge
Arbitrage Opportunities in Bitcoin
---
## Technologies
This project leverages python 3.8.8 in jupyter lab 3.0.14 with the following packages:
- [Anaconda](https://www.anaconda.com/products/individual) - Pandas is included in Anaconda distribution and Conda package manager to manage Python environments.
- [Jupyter Lab](https://jupyter.org/) - web-based user interface designed for data analysis. It lets you write, run, and review the results in Python programs (all in a single integrated development environment (IDE).
---
## Installation Guide
- [pandas](https://pandas.pydata.org/) - open source data analysis and manipulation tool, built on top of python programming language.
- [Path](https://docs.python.org/3/library/pathlib.html) - is a function from pathlib module 
- [matplotlib](https://matplotlib.org/) - Matplotlib is a comprehensive library for creating static, animated, and interactive visualizations in Python.
---
## Usage
```
# Read in the CSV file called "bitstamp.csv" using the Path module. 
# The CSV file is located in the Resources folder.
# Set the index to the column "Date"
# Set the parse_dates and infer_datetime_format parameters
bitstamp = pd.read_csv(Path('Resources/bitstamp.csv'),index_col="Timestamp",parse_dates=True,infer_datetime_format=True)
bitstamp.head()

```


---
## Contributors
Presented by Bina Jariwala 

---
## License
none

---
