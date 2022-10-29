# Tutorial Guide for Regex

This is a tutorial explaining Regex also known as Regular Expressions and how they work.

## Summary

Regex is useful for getting information from text by searching for one or more matches of a specific search pattern.

- Example: /^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})$/

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

Anchors are positioned before or after characters. Anchors can be used to put in place the regex match at a certain position.

### Quantifiers

Quantifiers indicate the number of characters or expressions to match. Also, a quantifier can be written after to specify how many times it should be repeated.

### OR Operator

An OR operator are used to match one of multiple patterns. In a current sequence, the operator represents those characters that fall in between the two elements.

### Character Classes

A character class help spot out different kinds of characters such as distinguishing between letters and digits.

### Flags

A flag changes the search behavior. There are six different flags each with a unique purpose, the flags are represented by lowercase letter. 

The, i, makes the search case-insensitive. 
The, g, makes the search for all occurrences. 
The, s,	makes the wild character and can also match newlines as well.
The, m, makes the boundary characters ^ and $ match the beginning and ending of every single line instead of the beginning and ending of the whole string.
The, y, makes the start search from the index indicated in its lastIndex property.
The, u, makes the individual characters as code points, not code units.

### Grouping and Capturing

Grouping is putting together groups a sequence of patterns into one single unit. To group a pattern, a pair of parentheses () is needed, and between them the desired group. Also quantifying a whole sequence one or more times is called a capturing group.

### Bracket Expressions

Bracket expressions differentiates a character class where expressions using parentheses are a capturing group.

### Greedy and Lazy Match

Greedy means to match the longest string in the expression while lazy means to match the shortest string in the expression.

### Boundaries

There are 3 different boundary positions; before the first character in a string, after the last character in a string and between two characters in a string.

### Back-references

Back references are commands that refer to a previous part of a match regular expression. Back references are indicated with a backslash and a single digit.

### Look-ahead and Look-behind

## Author

A short section about the author with a link to the author's GitHub profile (replace with your information and a link to your profile)
