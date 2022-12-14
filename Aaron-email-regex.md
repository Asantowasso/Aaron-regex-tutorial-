# Matching an email 
When gathering information one users an email address is an important piece. It allows you to inform that user about your application and service and hopefully keeps them engaged with what they registered for. 

## Summary

This regex creates a set of parameters which determine what the user can enter as their email address. It ensures that users can only enter address that are valid as dictated by the regular expression or regex created by the developer.

### Example: 
/^([a-zA-Z\d\.-]+)@([a-zA-Z])\.([a-z]{2,8})$/

## Table of Contents

- [Anchors](#anchors)   
- [Quantifiers](#quantifiers)
- [Character Classes](#character-classes)
- [Grouping and Capturing](#grouping-and-capturing)
- [Bracket Expressions](#bracket-expressions)


## Regex Components

    An email regular expression or Regex pattern can have four components. The first is the name of the owner of the address. It can be comprised of letters, numbers, dots or hyphens. After this is an "@" sign. Next, is the domain. You can use letters numbers or hyphens. This is followed by a dot ".". The next two portions are optional. Third is the extension you can use any letters. Finally can come another extension which which is made up of a dot then letters.


### Anchors

    The matching email regex utilizes the "^" or exact string match anchor. This anchor is placed at the start of the string before the first character. The other anchor we are using is "$". This marks the end of a string.
    
    Ex. start of a string "/^", or end of a string "$"
    
### Quantifiers

    A quantifier is used to determine the number of times a specific character, group of characters or character class must be included in an entry. In the case of an email regex this would likely be found on the extension as few would exceed more than a few characters. The example shows {2,8} which means the entry can be as few as two characters or as many as eight. 

    Ex. {2,8} for .com or .co

### Character Classes

    This dictates what characters can be used. This is represented by what is defined within the brackets "[]" or parentheses "()". These should appear in each portion of the expression. An example would be ([a-z]) allowing any lowercase letter between a and z.

    Ex. [a-z] allows for any lowercase letter in the alphabet

### Grouping and Capturing

    Grouping simply places letters, numbers or characters together. This can be accomplished with either brackets "[]" curly braces "{}" or parentheses "()". In addition to this adding a "+" allows you to add as many characters as you need.

    Ex. [A-Z \.] This string allows for any upper case letter in the alphabet and escapes the "." character

### Bracket Expressions

    Brackets are how letters, numbers and characters are grouped together. Rules are defined within these brackets and they inform what is acceptable to be entered by the user. 

    Ex. ([a-z\d\.]) within these brackets we can use any lowercase letter any digit with the "\d" and a "." because it is escaped

## Author

This tutorial was created by Aaron Santowasso. You can find his github profile here-
https://github.com/Asantowasso