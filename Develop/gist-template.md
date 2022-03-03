# Regex Guide

Welcome! This is the regex tutorial-designed and purposed to help YOU YOU become a CODING GOD of REGEX! But before we can do that, what is Regex and how does one write Regex?

## Summary

Regex is a shortening of "Regular expression" which si a sequence of characters that defines a specific search pattern for text. It is used in search algortihms and code to find patterns of characters within a strin. Another use of Regex is to find and replace characters or sequences of characters within a string. They are also frequently used to validate and verify inputs.

There are issues: sometimes it looks a little crazy (see example #1)

An application of Regex is used to verify a valid email addresses so you don't send it to some random person or to no one.

## Table of Contents

- [Anchors](#anchors)
- [Anchors Application](#anchors-application)
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
At its core, Regex is made out of Anchors, Quantifiers, OR Operators, Character Classes, and Flags to identify characters. 

Then from there it builds onto intermediate techniques to help you extract or expand specific bits of infromation. This is done with Grouping and Capturing, bracket expressions, ending with Greedy and Lazy Match. 

Finally, we have advanced techniques that make it possible to search for entire words and character orders. These techniques are Boudnaries, Back-refrencs, and Look-ahead and Look-behind.

By the end of this guide you will be able to understand and use the HTML Tag regex to search for an HTML code. As featured below:

## Example

 /^<([a-z]+)([^<]+)*(?:>(.*)<\/\1>|\s+\/>)$/

But before we can do this, we need to start with the basics!

### Anchors
Anchors are used to find a specific first word of a string, a specific last word of the string, the specific beginning and end of the string match, and any charater string with a specific text.

Generally, you want to start and end your 
Regex search with these.

|Syntax   | Description |
|:---          |:-- |
| ^The | matches any string that starts with the word "The". |
|end$ | matches a string that ends with "end".|
|^The end$ | searches for and exact string match (starts and ends with The end). |
|Hello | matches any string that has the text hello in it.|

# Anchors Application:

/ ==^== <([a-z]+)([^<]+)*(?:>(.*)<\/\1>|\s+\/>)$/

In the Example, we have the ^ and the $ which will signify where the start and end of the string will go. 


### Quantifiers
|Syntax   | Description |
|:---          |:-- |
|   fdc*       |This matches a string where fd is followed by 0 or more c            |
|    cdc+    | matches a string that has cd followed bby zero or one more C           |
|     apc?     | matches a string that has ap followed by zero or one C           |
|     aed{2}     | this matches a string that has ae followed by 2 D           |
| aed {2,}| this matches a string that has ae followed by 2 or more d|
| |
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
Profile https://github.com/Afaed

Afaed (real Name Justin Choy) is a programmer (by accident!) based in California. His hobbies are playing games, reading books about politics, and dunking on internet libertarians. He studies programming to become a game dev and make the game of his dreams!
