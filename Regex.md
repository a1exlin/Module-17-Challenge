# Module 17 Challenge Regex

Introductory paragraph (replace this with your text)
Test line to push code to main branch

## Summary

Regex is also know as regular expression that are used in validating and matching inputs. Email addresses are used for regex as well as passwords, and URLs An example of a regex would be: /^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})$/*\/?$/ as this is for matching a email. Below will be a table of contents and with each topic giving a brief description of how regex operates.

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

Anchors are positions that match before, after or between characters. The dollar symbol $, matches after the last character of the string. Caret ^, matches the position before the first character in the string.


### Quantifiers

Qantifiers show how many instances are in a character group or how the character class must be present in order for a match to be speicifed. This means taht in a matching email address, teh plus sign + is an operator which is also known as a greedy operator. It will match many occurances as possible. 

### OR Operator

N/A for this specific regex. 

### Character Classes
\d is looking for single digits. Because it is in a bracket followed with a plus sign, this will allow one more more digits. 


### Flags
/ are used to delimit a expression. the / comes before the caret and afer the dollar sign. Following, the m equal to multi-line search, and /g equaling to global search are some examples of flags that are used in expressions. 

### Grouping and Capturing
In grouping and capturing, parenthases are used to group off parts of the expression together. This also allows easier reading of the expression, and being able to identify the groups too. 

### Bracket Expressions
Bracket expressions are expressions that allows a regex ot match the specific characters in a set range. For example: a-z is matching through the entire alphabet a through z. 

### Greedy and Lazy Match
A greedy and lazy match are matches that will try to much as much or as little as possible. 

## Author

Alexander Lin

https://github.com/a1exlin

