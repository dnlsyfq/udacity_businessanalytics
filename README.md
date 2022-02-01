### Data Types

Categorical vs Quantitative

Quantitative
* Continuous
* Discrete
* 4 main aspect
    1. measure of center
        * means
        * medians
        * modes
    2. measure of spread
        * range
        * interquartile range
        * standard deviation
        * variance
    3. shape of distribution
        * right skewed : use 5 no. summary
        * left skewed : use 5 no. summary
        * symmetric : use mean and std
    4. outliers

Categorical
* Ordinal
* Nominal

* Quantitative
    * Numeric values to perform mathematical operations

* Qualitative @ Categorical
    * To label a group or set of items

* Categorical Ordinal
    * Have ranked order
* Categorical Nominal
    * No ranked order

* Quantitative Continuous Data
    * Quantitative values can be split

* Quantitative Discrete Data
    * Countable values 

### Summary Statistics

* Measures of spread - boxplot , q1,q3 (how data varies)
* Measure of centre - mean,mode,median (Average)

### Analyzing quantitative data

1. measure of centre
    * mean 
    * median 
    * mode
2. measure of spread
3. shape of data
4. outliers

### Quantitative Variables

1. Center
2. Spread
3. Shape
4. Outliers

### Notation

Here P stands for probability, while the parentheses encompass the statement for which we would like to find the probability. Since X represents the amount of time spent on the website, this notation represents the probability the amount of time on the website is greater than 20.


### Function

```
=sum()
=average()
=trim()
=stdev()
=SUBSTITUTE({text}, {old_text}, {new_text})
=FIND() # EXTRACT
=LEFT()  # EXTRACT
=RIGHT() # EXTRACT
=MID(text, start_num, num_chars) # EXTRACT
=FORMULATEXT()
=concatenate()
=proper()
=upper()
```
=======

###  Statistics

```
Population - our entire group of interest.
Parameter - numeric summary about a population
Sample - a subset of the population
Statistic numeric summary about a sample
```

Descriptive Statistics
* describing collected data 
* measures discussed throughout this lesson: measures of center, measures of spread, the shape of our distribution, and outliers. 
```
population = 100,000 students
sample = 5,000 students responded
statistics = 73% said yes
parameter = proportion of all 100,000 students drink coffee
```

 
Inferential Statistics
* describing collected data to draw conclusions about larger population
* Performing inferential statistics well requires that we take a sample that accurately represents our population of interest.
```
use the sample and draw conclusions

```
    
    
### Excel Shortcut

Ctrl + Z : Undo
Ctrl + Y : Redo

Range: A group of cells selected or addressed together. It is defined by the cells in the upper left and lower right corners of the range.

### Excel IF 

```
=IF(CONDITION,VALUE IF TRUE, VALUE IF FALSE)
=IF(AND({condition1}, {condition2}), ...)
=IF(OR({condition1}, {condition2}), ...)
=IF(OR(MAX(B2:D2)>10,E2>20),"Special Order","No")
```

### Excel Conditional Aggregation Function
function that operates across a group of data with logical conditions
```
=COUNTIF(<COLUMN>,"=Pitcher")
=COUNTIF(<COLUMN>,">100000")
=SUMIF(<COLUMN>,">100000")
```

### Named Ranges
```
Formula > Define Name 
Formula > Create from Selection
```

### VLookup function
function that uses a keyword and index to look up a value in table
```
=vlookup(cell,all column , column to return,false)
=vlookup(cell,all column , column to return,false) # item not in list return error 
```