# Title (replace with your title)
Matching and Validating Emails : Regex Turtorial 

## Summary

A Regex or regular expression is a sequence of characters that define a search pattern. Usually such patterns are used by string-searching algorithms for "find" or "find and replace" operations on strings. It also looks for input validations. It is a technique commonly developed in theoretical computer science.

We will look a a string of code using regex, this snippet will matcha nd validate an email.

Example : ^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})$

The content below will give a description of each section of this code. 

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

This specific expression incorporates anchors, quantifiers, meta escape characters, character classes, single character matches, grouping and capturing, and bracket expressions. In the tutorial's example, ^ and $ function as anchors, + and {2, 6} serve as quantifiers, \d denotes the meta escape character, [a-z0-9_.-], [\da-z.-], and [a-z.] define character classes, and _, ., - represent single character matches. Additionally, () signifies grouping and capturing, while [] delineates the bracket expression.

### Anchors

Within regex, anchors denote the expression's start and end points. In this case, ^ marks the beginning, and $ marks the end of the expression.

### Quantifiers

Quantifiers are meta characters modifying the preceding character, specifying how many instances should be matched in succession. The + sign matches one or more preceding characters, while {min, max} establishes a specific numerical quantifier range.

### OR Operator

Although this regex lacks OR operators, in general, they are represented by the pipe | under the alternation regex type.

### Character Classes

Character classes allow the definition of specific sets of characters in a regex pattern. The classes used here are [a-z0-9_.-], [\da-z.-], and [a-z.], each specifying different character ranges.

### Flags

### Grouping and Capturing

### Bracket Expressions

### Greedy and Lazy Match

### Boundaries

### Back-references

### Look-ahead and Look-behind


## Author

A short section about the author with a link to the author's GitHub profile (replace with your information and a link to your profile)