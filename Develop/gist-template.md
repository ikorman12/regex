# Regular expression: Email

Imagine sitting at work on a friday afternoon enjoying your final hours before a great long weekend and bam, your supervisor/manager delivers a file with hundreds of pages which need all the emails redacted or found by the end of the working day. How can one sit there for hours stairng at pages repeating the same process to make sure you dont miss a single email since your work depends on it? Instead we automate it with regex expressions. Regex expressions or regular expressions are search parameters used within a given files. This way, allowing the computer to find all the emails would reduce the risk of missing any emails, along with make your weekend that more enjoyable.

## Summary

Emails seem pretty self explanatory but are actually complex when it comes to searching for one. Many people throughout the world typically have a simple and easy to remember email and then there are the few which have fancy emails with many different words and numbers. There is no limit to how long or complex an email can be and for that we can use a regex expression as parameters to search and/or verify emails.

`/^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})$/`

This Regex begins with a beggining anchor. After the beginning achor the regex expression will begin to search for any letter `a-z`, any number `0-9` and an `_`, while also allowing `.-` within the first part of email names. Search/verify there is an `@` between the emails name and website URL.

When searching/verifying a URL the regex code searches for any letter `a-z` and `-.` followed by another possible `a-z` and `.` for 2-6 times.



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

`\`: Verify/look for exactly what digit is after this symbol

### Anchors

`^`:Beginning of statement
`$`:End of statement

### Quantifiers

`+`: Include/additionally
`{2,6}`:2-6 times

### Grouping Constructs

`(...)`: Allows for separation of grouping contructsgroups contructs to be found.

### Bracket Expressions

`[...]`: groups contructs to be found.

### Character Classes

`a-z`: Charcters a-z
`0-9`: characters 0-9
`- .`: characters - .


## Author

Igor Korman is an aspiring full stack developer interested in many logcal questions and answers. Problem solving is one of his favorite things to do. 

[Github](https://github.com/ikorman12)