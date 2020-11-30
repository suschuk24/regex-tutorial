# RegEx Tutorial

## Summary

Today, we will be discussing regular expressions, also known as RegEx. RegEx is a tool that may be used to define a search term parameter, and can be applied in many differnt circumstances, accross multiple coding languages. 

The RegEx we will be breaking down searches for an email address pattern within a string. Please review the following code snippit: 
```
/^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})$/
```

## Table of Contents

- [Anchors](#anchors)
- [Quantifiers](#quantifiers)
- [Character Classes](#character-classes)
- [Flags](#flags)
- [Grouping and Capturing](#grouping-and-capturing)
- [Bracket Expressions](#bracket-expressions)
- [Greedy and Lazy Match](#greedy-and-lazy-match)
- [Boundaries](#boundaries)

## Regex Components

### Anchors
* Anchors encapulate regex components to define what search pattern to find. For example:

* ``` ^xyz$ ``` where the ```^``` character indicates the start of a string, and the ```$``` character indicates the end of a string

### Quantifiers
```+``` = Repeats the previous item one or more times (Greedy Match)
* Example: ```a+``` would return a positive match for all items where the ```a``` character occurs one or more times.  


```?``` = Makes the last item in the search parameter optional. 
* Example: ```abc?``` would retrun a positive match for ```ab``` and ```abc``` 


### Character Classes
 ```.``` = Any character except newline
```[a-z]``` = Accepts any letter between ```a``` and ```z```
```[0-9]``` = Accepts any digit between ```0``` and ```9```

### Flags
Flags indicate the start and end of the regex. 
* Example: ```/^[a,b,c]$/``` where the regex ```^[a,b,c]$``` is inside of the ```/``` flags 

### Grouping and Capturing
* Example: ```([a-z0-9_\.-]+)``` where the () group together the ```[a-z0-9_\.-]``` bracket expression with the ```+``` quantifier.
* This regex matches any letter or number a-z or 0 to 9, accepts underscores, periods and dashes. Then the quantifier matches one or more of the previous token. 

### Bracket Expressions
Bracket expressions are the syntax theroy on combining character classes. Multiple character classes may be combined in a single bracket expression. 

* Example: [a-z0-9]
### Greedy and Lazy Match
```{a, }``` = Lazy match, searches number ```a``` or more
```{a,b}``` = greedy match, search BETWEEN numbers ```a``` and ```b```


## Author

Made with care by Seth Uschuk. To see more of my work, please visit my [GitHub](https://github.com/suschuk24)
