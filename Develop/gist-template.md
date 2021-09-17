# Regex Tutorial

Introductory paragraph (replace this with your text)

## Summary

The Regex that I will be making this tutorial on is the:

    Matching an Email – /^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})$/

    I will talk about what all of the symbol's mean.

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

    ^ Start of string, or start of line in multi-line pattern.
    /^([a-z...
    I just love **bold text**.

### Quantifiers

    Quantifiers are use to ensure that a string matches a certain value, eg: abc

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

### Flags

    

### Grouping and Capturing

### Bracket Expressions

### Greedy and Lazy Match

### Boundaries

### Back-references

### Look-ahead and Look-behind

## Author

A short section about the author with a link to the author's GitHub profile (replace with your information and a link to your profile)
