# stf.py
**Description** <br />
Search for terms in files recursively and save on SQLite database. <br />

**Requirements:**
```pip install tika sql colorama tenacity```

**Features** <br />
:heavy_check_mark: Uses Apache Tika to handle binary files (the script search terms even inside of Microsoft Office document formats, PDF etc. See the full list: https://tika.apache.org/2.8.0/formats.html). <br />
:heavy_check_mark: Can be used in background. <br />

**Future Updates** <br />
:heavy_minus_sign: Support to regex. <br />
***Suggestions***

Usage:
```
usage: python3 stf.py terms_file directory [database]

Search for terms in files recursively and save on SQLite database

positional arguments:
  terms_file   Path to the file containing terms.
  directory    The directory to search recursively.
  database     SQLite database file to store the results. (default=results-db.sqlite)

options:
  -h, --help   Help
```
