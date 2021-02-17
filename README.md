# details_generator
Used to scrape data from https://www.fakenamegenerator.com/

To check the arguments needed :

```
python details_generator.py -h
```

To run the script:
```
python -nr <number of records> -f <csv filepath> -a

Example: 
      python -nr 50 -f "C:\details\data.csv" -a
      python -nr 20 -a
      python -f "C:\details\data.csv" -a
      python -nr 10 -f "C:\details\data.csv"

usage: details_generator.py [-h] [-nr NUMRECORDS] [-f FILENAME] [-a]

Get random names with details and save in CSV!

optional arguments:
  -h, --help            show this help message and exit
  -nr NUMRECORDS, --numrecords NUMRECORDS
                        number of records to fetch
  -f FILENAME, --filename FILENAME
                        the path to store csv file
  -a                    Append to file, Overwrite is default

Enjoy the program! :)

```

Default number of records: 100

Default file path: .\details.csv

Default mode: Overwrite mode


Thank you. Have a good day.
