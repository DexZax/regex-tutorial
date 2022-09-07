# Email Regex Search
we will be looking at an email search regular expression, to search for any qualifying emails in a given situation


## Summary
Matching an Email – /^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})$/

this specific regex searches for valid emails.

## Table of Contents


- [Quantifiers](#quantifiers)
- [Character Classes](#character-classes)
- [Flags](#flags)
- [Grouping and Capturing](#grouping-and-capturing)
- [Bracket Expressions](#bracket-expressions)
- [Greedy and Lazy Match](#greedy-and-lazy-match)


## Regex Components

### Quantifiers
[a-z0-9_\.-]+
this shows that we are looking for the in bracket expressions followed by one or more characters.

### Character Classes
([\da-z\.-]
here we see that "\d" matches a single character that is a digit.

### Flags
/^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})$/
a regex usually comes wrapped in "/" which determines the begining and end of the regex.

### Grouping and Capturing
([a-z0-9_\.-]+)
this indicates a capture group. we are looking for these specific expressions all together.

### Bracket Expressions
[a-z0-9_\.-]
in this case we are using bracket expressions to find any letter a-z and any number 0-9 as well as "_", "\", ".", "-"

### Greedy and Lazy Match
{2,6}
this matches the previous token between 2 and 6 times, as many times as possible, giving back as needed.

## Author

A short section about the author with a link to the author's GitHub profile (replace with your information and a link to your profile)
