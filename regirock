# Regex tutorial on checking an email address

The purpose of this tutorial is to show how to properly use a regular expression (regex) to validate a user-inputted email address. This particular tutorial will focus on the regex /^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})$/ and how it can be used to validate an email address.

## Summary

A regex uses a a predetermined line of code, in this case /^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})$/  , to verify the structure of user-inputted data (in this case their email). It can check for patterns, type of data being used, specific charactrs inputted and other components.

## Table of Contents

- [Anchors](#anchors)
- [Quantifiers](#quantifiers)
- [Character Classes](#character-classes)
- [Grouping and Capturing](#grouping-and-capturing)
- [Bracket Expressions](#bracket-expressions)
- [Greedy and Lazy Match](#greedy-and-lazy-match)

## Regex Components

### Anchors
Anchors signify the beginning and the end of the regex between two / /. In this case the ^ symbol signifies the beginning and the $ signifies the ending.  

### Quantifiers
A quantifier, or matching quantifier, tells the regex how many times something should exist that the regex can match itself to. The + in this expression specifically signifies that the expressions between should match 1 or more times and joins the different sections together. 

### Character Classes
Character classes tell the regex to find only characaters of a certain trait. The only characater class in this regex, also the most common one in general, is the /d which tells the regex to match to a digit/character between 0 and 9.

### Grouping and Capturing
Groups, or ranges, indicate where each of the three character restrictions will be placed and joined using quantifiers. In this expression the three are ([a-z0-9_\.-]+), ([\da-z\.-]+), ([a-z\.]{2,6}) and it is indicated that they will be placed in the structure an email usually would be (firstgroup@secondgroup.thirdgroup)

### Bracket Expressions
Bracket expressions indicate the allowed components of an expression such as letters or numbers that are allowed. In this example the three classes are [a-z0-9_\.-] [\da-z\.-] and [a-z\.], which respectviely tell the expression that it can have letters a-z, numbers 0-9, and hyphens/dots, that it can have letters a-z and hyphens, and that it can have letters a-z for each of the three parts of the email (before the @, after the @, and after the .)

### Greedy and Lazy Match
Greedy and lazy match refer to how long and short of a result an expression can match to. In this expression the {2,6} refers to the fact that the third group after the dot must be between 2 and 6 characters in length.

## Author

Ryan Murphy is an aspiring programmer who learned about Regex through google. His github can be found below. 
https://github.com/rynmrphy18
