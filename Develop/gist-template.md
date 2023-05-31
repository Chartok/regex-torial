# Demystification of Regex

Regular Expressions, commonly known as regex, is a powerful tool used across many programming languages to match patterns extract data. Regex can initially seem esoteric and difficult to understand, but once we understand their components and how they work, we can use them like you've never thought you could.

## Summary

In this tutorial we will focus on the regex `/^<([a-z]+)([^<]+)*(?:>(.*)<\/\1>|\s+\/>)$/` that is a common expression used to parse and validate simple HTML & XML-like tags. We will break down and go over each component of the regex, and explain what it does in conjunction with demonstrating how it works.

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
Anchors don't match characters, but positions of characters that are before, after, or in between them. The anchors in the regex we're deconstructing are `^` and `$`. The `^` anchor marks the start of the string, and `$`marks the end of the string. This ensures that the regex will only match strings that start and end with the pattern we're looking for.





### Quantifiers
Quantifires define the quanitiy of characters that are matched. In the regex we've picked, the quantifiers are `+` and `*`. The `+` signifies that the character before it can appear more than once, but at least once. The `*` signifies that the character before it can appear zero or more times.

Example: `/^<([a-z]+)...$/` de
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
