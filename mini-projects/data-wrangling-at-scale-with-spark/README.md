# Setup

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