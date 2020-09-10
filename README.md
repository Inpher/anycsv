# anycsv
This is a robust CSV parser for Python 3 (Python 2 is NOT supported), based on the
default csv Python module. It can automatically detect delimiters of CSV files.

## Requirements

Requests library:

```
pip install requests
```

## Run Test
A test is included that reads a csv, changes its delimiter to '|', and writes it
to "out.csv".
Run `python3 test.py` to run the test. (no installation required)
