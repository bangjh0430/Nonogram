Nonogram Solver
================
## Rules
> Numbers mean the number of marked squares in the accosiated row/column.
> Every group of marked squres is seperated by at least one blank.
> 
> For example, if the clue is '1 2 4' with line length 10,
> all possible patterns are:
> ```
> ■X■■X■■■■X
> ■X■■XX■■■■
> ■XX■■X■■■■
> X■X■■X■■■■
> ```

## Example
> Solve this problem:
> ```
>        | | |2| | | | | |2|
>        | | | | | | | | | |
>        | | |2| |1|1|1| |2|
>        | | | | | | | | | |
>        |0|4|2|7|6|1|6|7|2|4
> -------+--------------------
>     1 1|
>   2 1 2|
>     4 4|
> 1 2 2 1|
>     4 4|
>     3 3|
>       5|
>     3 3|
>     2 2|
>       0|
> ```
> Result:
> ```
>        | | |2| | | | | |2|
>        | | | | | | | | | |
>        | | |2| |1|1|1| |2|
>        | | | | | | | | | |
>        |0|4|2|7|6|1|6|7|2|4
> -------+--------------------
>     1 1|        ■   ■
>   2 1 2|  ■ ■     ■     ■ ■
>     4 4|  ■ ■ ■ ■   ■ ■ ■ ■
> 1 2 2 1|  ■   ■ ■   ■ ■   ■
>     4 4|  ■ ■ ■ ■   ■ ■ ■ ■
>     3 3|    ■ ■ ■   ■ ■ ■
>       5|      ■ ■ ■ ■ ■
>     3 3|    ■ ■ ■   ■ ■ ■
>     2 2|    ■ ■       ■ ■
>       0|
> ```
> 
> **Note:** There can be unsolvable problems

## Command-line Usage:
>```
>python nonogram.py [-v] [-t] interval
>```
>Print all processes with time interval ***interval*** if *v* flag set

## In-program Usage:
>```
>0: Local Problems        1: Popular Problems
>5, 10, 15, 20, 25: nxn Problems
>q: Quit
>(input)
>```
> ### Local Problems
>problemN.txt in the form:
>```
>M N
>(row hints for M lines)
>(column hints for N lines)
>```
>
> ### Popular Problems
>Popular problems from http://nemonemologic.com/
>
> ### nXn Problems
>nxn problems from http://nemonemologic.com/
