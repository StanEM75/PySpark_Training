# PySpark_Training

![Project Image](https://spot.io/wp-content/uploads/2023/05/Blog_Challenges-cloud-Spark-app_1_30dec20-1.jpg)

This is my first project using PySpark. I started with a table that summarizes information about international flights, loaded it into a DataFrame, and then applied various transformations and manipulations with PySpark.

---

## 📘 Data
- `data/airlines_flights_data.csv`: Static csv file containing travel information for flights, and coming from: https://www.kaggle.com/datasets/rohitgrewal/airlines-flights-data.

## 📑 Content
- `spark_exploration.ipynb`: A Python notebook where a Spark session is initated to load the airlines_flights_data csv into a dataframe and perform transformations on it.
- `.gitignore`: Files/folders to be ignored.
- `main.py`: Part of uv local virtual environment (can be ignored).
- `pyproject.toml`: Part of uv local virtual environment (can be ignored).

## 💻 Load the dataframe and write in Parquet

Files: `data/airlines_flights_data.csv` - `spark_exploration.ipynb`

- `Load the dataframe` section: Load the DataFrame in lazy mode: first display the schema, then preview the data.
- `Write the dataframe in Parquet` section: Write the DataFrame using the Overwrite mode.
- `Reload the data in Parquet` section: Use the command `read.parquet` to read the generated Parquet files.

## 🔍 Explore the data

File: `spark_exploration.ipynb`

- Test .show to print the first rows of the table.
- Test .filter functions to print rows meeting specific requirements only.
- Query the data using SQL
- Test .repartition to partition the data 

## 💼 Basic analyses

File: `spark_exploration.ipynb`

WARNING: The data has not been processed so the following results are just first assumptions.
- Print the most expensive flight in terms of source and arrival destinations.
- Print the airline that appears the most in the table.



