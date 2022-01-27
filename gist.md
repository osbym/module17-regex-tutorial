# Regex Tutorial - Match an Email

This Regex Tutorial will describe how to match emails using the expression `/^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})$/`. This will be helpful when you'd like to valide emails using technologies and apps such as Node (Inqurier) or MongoDB.



## Summary

A sequence of characters that defines a search pattern is a regular expression. This is used to discover patterns within a string, find or replace characters within a string or used to validate input. The following tutortial will walk through the components of a regex and how it will apply to matching an email.

## Table of Contents

- [Anchors](#anchors)
- [Quantifiers](#quantifiers)
- [Character Classes](#character-classes)
- [Grouping and Capturing](#grouping-and-capturing)
- [Bracket Expressions](#bracket-expressions)
- [Greedy and Lazy Match](#greedy-and-lazy-match)


## Regex Components

### Anchors

Anchors that will be used in this regex expression for matching an email are `^ ` , which will indicate the start of the string and `$` to indicate the string's end. (m), or multiline will not be enabled, so the regex will ultimately conclude at `$`.

### Quantifiers

The quantifiers used in this regex will include the `+` operator, that connects the user's email name + email service + `.com`. A second quantifier for the regex is `{2,6}`. This enables a match range between 2-6 characters for the character set of `[a-z\.]`.

### Character Classes

### Grouping and Capturing

### Bracket Expressions

### Greedy and Lazy Match


## Author

 Greetings! I'm an aspiring Software Developer based in Austin, TX but originally from Virginia Beach, VA. 
 Check out more of my projects at https://github.com/osbym