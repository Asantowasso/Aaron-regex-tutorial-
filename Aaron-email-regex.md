# Matching an email 
Introductory paragraph 

## Summary

This regex creates a set of parameters which determine what the user can enter as their email address. It ensures that users can only enter address that are valid as dictated by the regular expression or regex created by the developer.

### Example: 
/^([a-z\d\.-]+)\.([a-z]{2,8})$/

## Table of Contents

- [Anchors](#anchors)   
- [Quantifiers](#quantifiers)
- [Character Classes](#character-classes)
- [Grouping and Capturing](#grouping-and-capturing)
- [Bracket Expressions](#bracket-expressions)
- [Greedy and Lazy Match](#greedy-and-lazy-match)
- [Boundaries](#boundaries)
- [Back-references](#back-references)
- [Look-ahead and Look-behind](#look-ahead-and-look-behind)

## Regex Components
    An email regular expression or Regex pattern has four components. The first is the name of the owner of the address. It can be comprised of letters, numbers, dots or hyphens. After this is an "@" sign. Next, is the domain. You can use letters numbers or hyphens. This is followed by a dot ".". The next two portions are optional. Third is the extension you can use any letters. Finally can come another extension which which is made up of a dot then letters.


### Anchors
    The matching email regex utilizes the "^" or exact string match anchor. This anchor is placed at the start of the string before the first character. The other anchor we are using is "$". This marks the end of a string.
    
### Quantifiers
    A quantifier is used to determine the number of times a specific character, group of characters or character class must be included in an entry. In the case of an email regex this would likely be found on the extension as few would exceed more than a few characters. The example shows {2,8} which means the entry can be as few as two characters or as many as eight. 

### Character Classes
    This dictates what characters can be used. This is represented by what is defined within the brackets "[]" or parentheses "()". These should appear in each portion of the expression. An example would be ([a-z]) allowing any lowercase letter between a and z.

### Grouping and Capturing
    Grouping simply places letters, numbers or characters together. This can be accomplished with either brackets "[]" or parentheses "()". In addition to this adding a "+" allows you to add as many characters as you need.
### Bracket Expressions
    Brackets are how letters, numbers and characters are grouped together. Rules are defined within these brackets and they inform what is acceptable to be entered by the user. 
### Greedy and Lazy Match

### Boundaries

### Back-references

### Look-ahead and Look-behind

## Author

This tutorial was created by Aaron Santowasso. You can find his github profile here-
https://github.com/Asantowasso