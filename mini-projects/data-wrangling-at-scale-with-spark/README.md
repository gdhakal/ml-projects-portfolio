# Setup

### Data
1) Download 
- [NASA access log Jul95](ftp://ita.ee.lbl.gov/traces/NASA_access_log_Jul95.gz)
- [NASA access log Aug95](ftp://ita.ee.lbl.gov/traces/NASA_access_log_Aug95.gz) 

2) Create folder structure as follows at [location](https://github.com/gdhakal/ml-projects-portfolio/tree/master/mini-projects/data-wrangling-at-scale-with-spark)
- `data`/: Read `NASA access log Jul95` and `NASA access log Aug95` data from this location.
- `outputcsv`/: Output csv file at this location.
- `outputjson`/: Output json file at this location.

### Dependencies
 - [JDK](https://www.oracle.com/java/technologies/javase-downloads.html#JDK14)

### Install
```
pip install pyspark
```

Check the installation with the command `pyspark`

### Configuration

- add the following $PATH variables in your bash profile

```
vi .bash_profile 
```

```
export PYSPARK_DRIVER_PYTHON="jupyter"
export PYSPARK_DRIVER_PYTHON_OPTS="notebook"
export PYSPARK_PYTHON=python3
```

# Spark DataFrames

### Peek DataFrame

```python
df.show(10, truncate=False)
```

# Reference
- [How to wrangle log data with Python and Apache Spark](https://opensource.com/article/19/5/log-data-apache-spark)