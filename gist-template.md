# Validating Hex Value

/^#?([a-f0-9]{6}|[a-f0-9]{3})$/

## Summary
A regular expression is way of validating a specific peice of text by using a sequence of characters each
possessing their own principles
Regular expressions can be used for validating, URLs, HTML, Hexvalues and emails
We are going to look at Hex values which are composed of 6 numbers or letters

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
Anchors in a regular expression string are the ^ and $, the ^ wil represent the beginning of the string and the $ represent
the end of the string
- ^#?([a-f0-9]{6}|[a-f0-9]{3})$
Everything between the ^ and $ symbols represent what the regex is searching for

### Quantifiers
The quantifiers will be the {}, ?, *
In this example, the ? symbol is showing that the # will be followed by 0 or 1 characters
- ?([a-f0-9]{6}|[a-f0-9]{3}) the quantifier is saying that after the # symbol it will be either 0 or 1 characters

### OR Operator
In this regular expression, the pipe | is acting as an OR operator.
The OR operator tells the regular expression to look for either {6} OR {3} hex character values.
-[a-f0-9]{6}|[a-f0-9]{3} the | means that it will be either be 3 or 6 characters

### Flags
In regular expressions we used flags for advcanced searching.
In the hex code value, we have a multi-line flaf by using the ^ and $ symbols at the beginning
and end of the string.
This allows the expression to cross multi-lines of code without causing it to break.
- ^#?([a-f0-9]{6}|[a-f0-9]{3})$ here, we are showing that the hex value could be wrapped into multiple lines

### Grouping and Capturing

### Bracket Expressions
They are used to display which characters will be matched with the regular expression.
In this example, we have brackets showing we are looking for two strings including characters a-f and 0-9

## Author

A short section about the author with a link to the author's GitHub profile (replace with your information and a link to your profile)
