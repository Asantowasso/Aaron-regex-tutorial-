# Matching an email 
Introductory paragraph 

## Summary

Briefly summarize the regex you will be describing and what you will explain. Include a code snippet of the regex. Replace this text with your summary.

## Table of Contents

- [Anchors](#anchors   
- [Quantifiers](#quantifiers)
- [Character Classes](#character-classes)
- [Flags](#flags)
- [Grouping and Capturing](#grouping-and-capturing)
- [Bracket Expressions](#bracket-expressions)
- [Greedy and Lazy Match](#greedy-and-lazy-match)
- [Boundaries](#boundaries)
- [Back-references](#back-references)
- [Look-ahead and Look-behind](#look-ahead-and-look-behind)

## Regex Components
    An email regular expression or Regex pattern has four components. The first is the name of the owner of the address. It can be comprised of letters, numbers, dots or hyphens. After this is an "@" sign. Next, is the domain. You can use letters numbers or hyphens. This is followed by a dot ".". The next two portions are optional. Third is the extension you can use any letters. Finally can come another extension which which is made up of a dot then letters.

### Example: 
/^([a-z\d\.-])$/
### Anchors
    The matching email regex utilizes the "^" or exact string match anchor. This anchor is placed at the start of the string before the first character. The other anchor we are using is "$". This marks the end of a string.
### Quantifiers
    A quantifier is used to determine the number of times a specific character, group of characters or character class must be included in an entry. In the case of an email regex this would likely be found on the extension as few would exceed more than a few characters. 

### Character Classes
    This dictates what characters can be used. This is represented by what is defined within the brackets "[]". These appear in each portion of the expression.
### Flags

### Grouping and Capturing

### Bracket Expressions

### Greedy and Lazy Match

### Boundaries

### Back-references

### Look-ahead and Look-behind

## Author

This tutorial was created by Aaron Santowasso. You can find his github profile here