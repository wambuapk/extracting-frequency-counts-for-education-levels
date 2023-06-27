# Data Serialization Formats

This covers:

* Reading serialized CSV data from a file into a Python object
* Extracting information from nested data structures

## Task: Extracting Frequency Counts for Education Levels from a CSV

### Data Understanding

In this repository under the file path `data/salaries.csv` lies a CSV data file containing salary and demographic information. When loaded into Python as a list of dictionaries, each dictionary looks something like this:

```
{
  'Age':          '39',
  'Education':    'E - Bachelors',
  'Occupation':   'Adm-clerical',
  'Relationship': 'Not-in-family',
  'Race':         'White',
  'Sex':          'Male',
  'Target':       '<=50K'
 }
```

Most of this information is irrelevant to the current task; the one piece that needs focus is the `Education` key-value pair.

The task is to create a **frequency table** where the various education levels (values associated with the `Education` keys) are encoded as keys, and the frequencies of those education levels are encoded as values.
