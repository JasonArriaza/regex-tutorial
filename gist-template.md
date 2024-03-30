# The very best email regex tutorial that I can make at the moment (Through the eyes of a junior developer)

This will be a brief explanation on how a regex works. More specifically and email regex. If you don't know what a regex is, it is short for 'regular expression'. It is a system that can check inputs and make sure that they are valid according to our specifications without writing the most robust and comprehensive code to verify it. Very useful when we need to work on more important and cooler stuff.

## Summary

The regex that we will be looking into is the email regex. This specific regex validates emails to make sure that they have all the requirements that makes up an email. The followiing is an example of a email regex.
/^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})$/

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
The anchors that are available to have are '^' and '$', they signify the start and end of the characters that follow it and precede it. The ^ as the beginning and $ marking the end of the expression. With these two anchors, you can add string regular expressions.

### Quantifiers
Quantifiers sets the limits to the string that your regex will be looking for. The limits are found in brackets at the end of the regex, normally with the minimum and maximun for the matches. (example: {3, 16}).

### OR Operator
The OR ('|') operator is the same as the or operator in javascript except it only uses one line instead of two. You also have the ability to add mutiple OR statements in a single regex. For example, you could use (a|b|c) as way to say to either use 'a' or 'b' or 'c' in the expression. 

### Character Classes
Characters classes is a way to accept groups of characters within an input. For example, [0-9] would signify that any character between 0 and 9 can be accepted in the strinf and will be valid. [A-Z] signifies that any character between capital A to Z can ba accepted. Take note that there is a difference between uppercase A and a lowercase a. They are not conisered the same.

### Flags
Flags will not covered due to the selected regex.

### Grouping and Capturing
Grouping and capturing is the ability to grab portion of a regex so that you can define parameters on that section of the input. This is deifned using wrapping a portion of a regeex is using (). You have the ability to use multiple parantheses to define different parameters. For example, like classes like in the provided email regex, /^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})$/, you can see that the first portion of the regex it is saying that it can accept any string that uses characters between lowercase a to z as wel as any character 0 to 9.

### Bracket Expressions
Bracket expressions, also known as character classes, are denoted by square brackets [] in regex patterns. They allow you to specify a set of characters from which the regex engine can match any single character.

### Greedy and Lazy Match
N/A

### Boundaries
N/A

### Back-references
N/A
### Look-ahead and Look-behind
N/A
## Author
Author: Jason Arriaza
Github: https://github.com/JasonArriaza
