# Matching Emails : Regex Turtorial 

## Users Story

```md
AS A web development student
I WANT a tutorial explaining a specific regex
SO THAT I can understand the search pattern the regex defines
```

## Acceptance Criteria

```md
GIVEN a regex tutorial
WHEN I open the tutorial
THEN I see a descriptive title and introductory paragraph explaining the purpose of the tutorial, a summary describing the regex featured in the tutorial, a table of contents linking to different sections that break down each component of the regex and explain what it does, and a section about the author with a link to the author’s GitHub profile
WHEN I click on the links in the table of contents
THEN I am taken to the corresponding sections of the tutorial
WHEN I read through each section of the tutorial
THEN I find a detailed explanation of what a specific component of the regex does
WHEN I reach the end of the tutorial
THEN I find a section about the author and a link to the author’s GitHub profile
```

## Summary

A Regex or regular expression is a sequence of characters that define a search pattern. Usually such patterns are used by string-searching algorithms for "find" or "find and replace" operations on strings. It also looks for input validations. It is a technique commonly developed in theoretical computer science.

We will look a a string of code using regex, this snippet will matcha nd validate an email.

Example : /^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})$/

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

Picture anchors as the bedrock of our regex journey, marking the commencement and culmination of our quest. The caret (^) symbolizes the genesis, while the dollar sign ($) signifies the resolution of our regex tale.

### Quantifiers

Quantifiers are meta characters modifying the preceding character, specifying how many instances should be matched in succession. The + sign matches one or more preceding characters, while {min, max} establishes a specific numerical quantifier range.

### OR Operator

Think of the OR operator as the decision-maker, though our example doesn't need it. In other regex adventures, it's the pipe | leading the way.

### Character Classes

Character classes are the character detectives, narrowing down the search. In our case, they include sets like [a-z0-9_.-], [\da-z.-], and [a-z.], each with a unique character range.

### Flags

Flags are the expression's mood-setters, influencing behavior. Our tutorial keeps it flag-free, but in JavaScript, i, g, m, s, u, and y play different roles.

### Grouping and Capturing

Groups (denoted by ()) are like organizers, treating multiple characters as a single unit. They highlight characters before @, before ., and after.

### Bracket Expressions

Brackets [] are like separators, creating character or group ranges. They bring flexibility to our search.

### Greedy and Lazy Match

Greedy matching, the default regex behavior, seeks to match as much of the string as possible, while lazy matching aims to match as little as possible. Greedy keeps searching until satisfied, while lazy stops once satisfied.

### Boundaries

Think of \b as a boundary guard, making sure specific characters are at the start or end of our sequence.

### Back-references

Back-references (\2) are the echo, referring to a previous part of the regex, creating a connection.

### Look-ahead and Look-behind

Look-ahead (?=foo) and look-behind (?<=foo) peek into what comes after or before a specific part of our search.

## Author

I'm Kristofer Vickers, navigating the coding world over at the University of Kansas bootcamp. I'm always on the lookout for ways to make a positive impact in tech. Currently, I'm honing my skills in different programming languages and tools. Feel free to drop me a message if you have any questions or just want to connect:

GitHub: https://github.com/KristoferVickers
Email: kristofervickers2018@gmail.com

Looking forward to hearing from you!
