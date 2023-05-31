# Demystification of Regex

Regular Expressions, commonly known as regex, is a powerful tool used across many programming languages to match patterns extract data. Regex can initially seem esoteric and difficult to understand, but once we understand their components and how they work, we can use them like you've never thought you could.

## Summary

This tutorial will dissect the regex `/^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})$/` and explain each component. We will also go over the flags that can be used with regex and how they can change the behavior of the regex. Lastly, we will go over some common use cases for regex and how to use them in JavaScript.

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
Anchors in regex don't match characters, but positions of characters that are before, after, or in between. The anchors in the regex we're deconstructing are `^` and `$`. The `^` anchor marks the start of the string, and `$`marks the end of the string. This ensures that the regex will only match strings that start and end with the pattern we're looking for.

'/^.....$/'

Example: `/^hello$/` will match the string 'hello', but not 'hello world'.

### Quantifiers

### OR Operator

### Character Classes

### Flags

### Grouping and Capturing

### Bracket Expressions

### Greedy and Lazy Match

### Boundaries

### Back-references

### Look-ahead and Look-behind

## Author

A short section about the author with a link to the author's GitHub profile (replace with your information and a link to your profile)
