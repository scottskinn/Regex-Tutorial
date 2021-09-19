# Regex Tutorial for Emails

    What is a Regex? Regex stands for Regular Expression, which is a easy way to define a pattern. The main purpose of a regex is for you to match a character or words in specific fields.


## Summary

    The Regex that I will be making this tutorial on is the:

    Matching an Email – /^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})$/

    I will talk about what all of the symbol's mean and the different sections they have.

## Table of Contents

- [Anchors](#anchors)
- [Quantifiers](#quantifiers)
- [OR Operator](#or-operator)
- [Character Classes](#character-classes)
- [Grouping and Capturing](#grouping-and-capturing)
- [Bracket Expressions](#bracket-expressions)


## Regex Components

### Anchors

    ^ Start of string, or start of line in multi-line pattern.

    /^([a-z...

    $ Used at the end of the string to check if it matches.

    ...([a-z\.]{2,6})$/

### Quantifiers

    Quantifiers, *+?{}, are use to ensure that a string matches a certain value. 
        eg: abc* this will match a string that has ab with zero or many c's
            abc+ this will match a string that has ab with one or more c's

### OR Operator

    These can be used with | or []
    a(b|c)     matches a string that has a followed by b or c (and captures b or c),
    It will then find all matches that have: (ab) or (ac) but have to be connected.

    /^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})$/
           ^----------^    ^--------^     ^-----^

### Character Classes

    ...@([\da-z\.-]...
    The Character Classes are use to match any digit (\d) or word character (\w).
    We are only using the digit (\d) class after the @ symbol so the user is able to use any numbers or letters for their web address.

### Grouping and Capturing

    These are useful when you need to extract information from strings or data using your preferred language
    /^([a-z0-9_\.-]+)@...
    ^---------------^

### Bracket Expressions

    Brackets are used to ensure that the string meets the requirement [abc]. It can also be used to match a single character NOT present in the string [^abc].

    /^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})$/
    Each [] that is used is looking for a set of letters or numbers.

## Author

A short section about the author with a link to the author's GitHub profile (replace with your information and a link to your profile)
