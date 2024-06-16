# Title (replace with your titddle)

Introductory paragraph (replace this with your text)

## Summary

Briefly summarize the regex you will be describing and what you will explain. Include a code snippet of the regex. Replace this text with your summary.

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

### Quantifiers

Quantifiers are used to specify a minimum or maximum that a pattern must be repeated for. They can be used to see how many times a character or group repeats. `*` next to the character being searched for to test if it appears zero or more times. `{n,m}` allows the user to search for a character that repeats from `n`, the minimum and `m`, the maximum.

### OR Operator

OR Operators are just another expression for `|` or pipe. This expression is used to match one pattern or another such as in the expression `/run|jump/` will search for the word run OR jump. This component can be used to check case sensitivity, email domains, and alternative spelling.

### Character Classes

`[xyz][a-c]` are character classes, meaning they are components that can specify a range of characters by using a hyphen. This regex expression will search for the characters `xyz` or `a`,`b`,`c`.

### Flags

Flags are components that serve as special options or modifiers, they are placed along other components to change how they behave. `i` is used for ignoring case sensitivity specifically so any character set will match regardless of case. `g` matches any instance of the pattern and `m` matches the beginning and end of each line.  

### Grouping and Capturing

This regex component uses `()` to group characters and search for anytime they may appear such as the expression `(\d{3})` will search for a group of three digits, often used in seacrhing for a phone number. 

### Bracket Expressions

Bracket Expressions are another form of character classes in which they allow you to specify the characters you want to match. This includes `[]` or square brackets, `-` or character ranges and `^` or a negotiation.

### Greedy and Lazy Match

Greedy and Lazy matches refer to the quantifiers that control how much of text is matched by the pattern. Greedy is the base behavior of quantifiers meaning they'll match as much text as possible. These include `*`,`+`,`{n,m}`. Lazy is the descriptor of quantifiers that match as little text as possible. This would be quantifiers that include `?` such as `*?`,`+?`,`{n,m}?`.

### Boundaries

Boundaries are used to specifiy the position in which the pattern or character should match within the string. They can be used to locate patterns without matching each character. `\b` or a word boundary, matches where a word character is not next to another word character. `\B` or non-word boundary, is the opposite, it matches where the word character is next to another. `^` or `$` are anchors, they match the start `^` or end `$` of a string.  

### Back-references

Back- references alloww you to reuse or manipulate parts of text dynamically. They often are used in regex expressions for replacements or advanced pattern matching situations. These would include the use of `\1` to match repeated word or `\1 \2` to swap the order of words.

### Look-ahead and Look-behind

Look-ahead and Look-behind are terms to reference advanced features in regex that match patterns only if it is or isn't followed or preceded by another without actually matches the characters in the string. These include `(?=...)` to match the preceding pattern only if it is followed by the pattern inside the parentheses and `(?!...)` to match the preceding pattern only if it is not followed by the pattern inside the parentheses. These are refered to as look-ahead assertations while, `(?<=...)` and `(?<!...)` are look-behind. `(?<=...)` matches the following pattern only if it is preceded by the pattern inside the parentheses and `(?<!...)` matches the following pattern only if it is not preceded by the pattern inside the parentheses.

## Author

My name is Nathan Lane, I am a futurre fullstack developer that loves videos games and fashion. Originally from Buffalo,NY I moved to Charlotte, NC in 2010 and since then I've loved the city of Charlotte. For more info about me and more of my coding projects click on the link below.

![Static Badge](https://img.shields.io/badge/Github-blue?style=flat&logo=GitHub)
[Github link](https://github.com/LaneNathan)