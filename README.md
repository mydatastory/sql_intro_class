## Introduction to SQL

The episodes in this course are derived from work that is Copyrighted © by Software Carpentry.  Additional information can be
found at: http://software-carpentry.org/.  The Creative Commons license which governs this work is located at:
https://creativecommons.org/licenses/by/4.0/.  The original Software Carpentry episodes have been modified and/or extended to meet the specific learning goals of this class.  Instructions for installing SQLite can be found at this [location](http://johnatten.com/2014/12/07/installing-and-using-sqlite-on-windows/).
  
## Original Software Carpentry Course

[sql-novice-survey](https://github.com/swcarpentry/sql-novice-survey) 

## SQLite Notes

All SQLite date columns must be in a YYYY-MM-DD HH:MM:SS format.  Date range subsetting does not work with the datetime() function if the values in a date column use backslashes as delimiters (YYYY/MM/DD).  

Click [here](https://www.sqlite.org/lang_datefunc.html) to view the SQLite datetime documentation.

Click [here](https://stackoverflow.com/questions/43893128/blank-values-returns-when-using-greater-than-operator-in-sqlite) for documentation about how SQLite handles null values.
