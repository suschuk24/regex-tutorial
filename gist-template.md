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
- [OR Operator](#or-operator)
- [Character Classes](#character-classes)
- [Flags](#flags)
- [Grouping and Capturing](#grouping-and-capturing)
- [Bracket Expressions](#bracket-expressions)
- [Greedy and Lazy Match](#greedy-and-lazy-match)
- [Boundaries](#boundaries)
- [Back-references](#back-references)
- [Look-ahead and Look-behind](#look-ahead-and-look-behind)

## Regex Components

### Anchors
* Anchors encapulate regex components to define what search pattern to find. For example:

* ``` ^xyz$ ``` where the ```^``` character indicates the start of a string, and the ```$``` character indicates the end of a string

### Quantifiers
```+``` = Repeats the previous item one or more times (Greedy Match)
* Example: ```a+``` would return a positive match for all items where the ```a``` character occurs one or more times.  


```?``` = Makes the last item in the search parameter optional. 
* Example: ```abc?``` would retrun a positive match for ```ab``` and ```abc``` 


### OR Operator

### Character Classes
 ```.``` = Any character except newline
* When combined with the ```\``` anchor, ```\.```
### Flags

### Grouping and Capturing

### Bracket Expressions

### Greedy and Lazy Match

### Boundaries

### Back-references

### Look-ahead and Look-behind

## Author

A short section about the author with a link to the author's GitHub profile (replace with your information and a link to your profile)
