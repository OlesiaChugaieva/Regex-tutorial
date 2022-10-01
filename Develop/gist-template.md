# Regex [Regular expression]
Regular Expression(Regex) is a language that helps to represent patterns when you are working with any type of textual input.
These patterns or symbols are going to allow users to match, search and replace text.
 
## Summary
In this tutorial I'm going to explain how to use Regex for email input validation. A valid email address has 4 parts:
- Username that accepts uppercase and lowercase letters (A-Z, a-z), digits from 0-9 and special characters
- @ symbol 
- Domain name
- Top-level domain
Example email address: tomhanks123@gmail.com
^([a-zA-Z0-9_\-\.]+)[@][a-z]+[\.][a-z]{2,3}$
       

## Table of Contents

- [Anchors](#anchors)
- [Quantifiers](#quantifiers)
- [Grouping Constructs](#grouping-constructs)
- [Bracket Expressions](#bracket-expressions)
- [Character Classes](#character-classes)
- [The OR Operator](#the-or-operator)
- [Flags](#flags)
- [Character Escapes](#character-escapes)

## Regex Components


### Anchors
Anchors in Regex match a position before or after. The 'caret' anchor(^) matches the beginning of the text and a dollar sign anchor($) matches the end of the text.
### Quantifiers
Quantifiers in Regex allow user to specify the number of occurrences to match against. In my example, {2,3} is a quantifier that has 2 as a minimum value and 3 as a maximum value, meaning that user cannot insert less than 2 and more than 3 characters after the dot.
### Grouping Constructs
By placing part of a regular expression inside round brackets, you can group that part of the regular expression together. Only parentheses can be used for grouping. Example: ([a-zA-Z0-9_\-\.]+).
### Bracket Expressions

### Character Classes


### The OR Operator

### Flags

### Character Escapes

## Author: Olesia Chugaieva

A short section about the author with a link to the author's GitHub profile (replace with your information and a link to your profile)
