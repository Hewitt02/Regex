# Email Regex

This is a Regex tutorial for the Email Regex: /^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})$/

## Summary

In this tutorial, I will go over each part of this regex code and describe its functionality.
/^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})$/

## Table of Contents

- [Anchors](#anchors)
- [Quantifiers](#quantifiers)
- [OR Operator](#or-operator)
- [Character Classes](#character-classes)
- [Grouping and Capturing](#grouping-and-capturing)
- [Bracket Expressions](#bracket-expressions)
- [Tutorial Video](#tutorial-video)

## Regex Components
A regex is a literal, defined by this symbol /. This means every regex must have fixed values usuing / to start it.
### Anchors
The ^ is an anchor. This symbol represents the string that follows it next in the sequence. For this regex, it contains brackets, which will be the string that follows the ^. The other anchor in this regex is the $ symbol. This symbol represents the ending of a string. 
### Quantifiers
Quantifiers in this regex {2,6}. Here we see that 2 is the minimum amount of characters and 6 is the maximum amount of characters that this string is looking for. 

### Character Classes
a character class defines a set of characters, for instance /da-z. This means any digit plus and lower case letter can be this string.
### Grouping and Capturing
grouping will be used by () parenthesis. These group strings can br grouped to make sure they fufill a requirement that could only be wanted for that string. (abc):(xyz) in abc, the grouping of these lettes means its looking for a string that fulfills the letters abc in the parenthesis.

### Bracket Expressions
The bracket symbols [] represent the range of characters our regex is looking for. In our regex, [a-z0-9_\.-] this would mean that the string were looking for can have any lettes in lower case from a to z and also can have any number 0-9. For example, hewitt1203@gmail.com, this email has all lower case letters followed by numbers only 0-9. 
### Greedy and Lazy Match
A greedy and lazy match will tell you how many times an expression should be repeated.


## Author

Will Hewitt - Full stack Javascript Web Developer 
https://github.com/Hewitt02

## Tutorial Video
https://drive.google.com/file/d/1QMh32WqWc3HbW_x4QSsrS4CvtpQ-fO4Q/view