# hours/

`hours/` is simple and effective time tracking for workers.

## directory structure

`hours/` is a directory containing files named YYYY-MM.

example:

    $ ls hours/
    2012-03  2012-04  2012-05

## file structure

every line in a YYYY-MM file is a single shift.

example:

    $ cat hours/2012-05
    2012-05-01 1000 1045 added =6c93a1960072710c6677682a7816ba9e48b7528f to +hours.
    ...

## line structure

every line has 4 fields separated by spaces:

1. date (formatted YYYY-MM-DD)
2. time in (formatted HHMM)
3. time out (formatted HHMM)
4. description of the work completed during the shift
