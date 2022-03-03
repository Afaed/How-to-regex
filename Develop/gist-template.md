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
- [Quantifiers Application](#quantifiers-application)
- [OR Operator](#or-operator)
- [OR Operator Application](#or-operator-application)
- [Character Classes](#character-classes)
- [Chatacter Classes Application](#character-classes-application)
- [Flags](#flags)
- [Flags](#flags-application)
- [Grouping and Capturing](#grouping-and-capturing)
- [Grouping and Capturing Application](#grouping-and-capturing-application)
- [Bracket Expressions](#bracket-expressions)
- [Bracket Expressions Application](#back-references-application)
- [Greedy and Lazy Match](#greedy-and-lazy-match)
- [Greedy and Lazy Match Application](#greedy-and-lazy-match-application)
- [Boundaries](#boundaries)
- [Boundaries Application](#boundary-application)
- [Back-references](#back-references)
- [Back-references Application](#back-references-application)
- [Look-ahead and Look-behind](#look-ahead-and-look-behind)
- [Look-ahead and Look-behind Application](#look-ahead-and-look-behind-application)

## Regex Components
At its core, Regex is made out of Anchors, Quantifiers, OR Operators, Character Classes, and Flags to identify characters. 

Then from there it builds onto intermediate techniques to help you extract or expand specific bits of infromation. This is done with Grouping and Capturing, bracket expressions, ending with Greedy and Lazy Match. 

Finally, we have advanced techniques that make it possible to search for entire words and character orders. These techniques are Boudnaries, Back-refrencs, and Look-ahead and Look-behind.

By the end of this guide you will be able to understand and use the HTML Tag regex to search for an HTML code. As featured below:

## Example

 ```/^<([a-z]+)([^<]+)*(?:>(.*)<\/\1>|\s+\/>)$/```

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

```/^<([a-z]+)([^<]+)*(?:>(.*)<\/\1>|\s+\/>)$/```

In the Example, we have the `^` and the `$` which will signify where the start and end of the string will go. Did you see where the Text is? 

If you don't don't fret! The text is the `\/` within the code. Text can be symbols like `\/` as long as they end with a symbol or text.

### Quantifiers
|Syntax   | Description |
|:---          |:-- |
|   fdc*       |This matches a string where `fd` is followed by `0` or more `c`            |
|    cdc+    | matches a string that has `cd` followed by `0` or one more `c`           |
|     apc?     | matches a string that has `ap` followed by `0` or one `c`           |
|     aed{2}     | this matches a string that has ae followed by `2 D`           |
| aed {2,}| this matches a string that has ``ae`` followed by `2` or more `d`|
| adf{2,5}| This matches a string that has ``ad`` followed by 2 up to 5 f|
| a(bd)| This matches a string that has a followedd by zero or more copies of the sequence ```bd``` |
| a(bc){2,5}| matches a string that has ```a``` followed by `2 up to 5` copies of the sequence ```bc```|

# Quantifiers Application

```/^<([a-z]+)([^<]+)*(?:>(.*)<\/\1>|\s+\/>)$/```

In the example shown above, we have `[a-z]+` which tells the code to match a string that follows the character set a-z, giving back what is neccessary.

You may ask yourself, "What is a character string?" Don't worry about that for now-that will be covered later.

We also have a Quantifier with `*` in between `/^<([a-z]+)([^<]+)` and `(?:>(.*)<\/\1>|\s+\/>)$/`. What the quantifier here does that it matches any string of the first followed by the second

### OR Operator
Syntax   | Description |
|:---          |:-- |
| a(b|c) |    matches a string that has a followed by b or c (and captures b or c) |
| | |
| | |
| | |
| | |
| | |
# OR Operator Application

```/^<([a-z]+)([^<]+)*(?:>(.*)<\/\1>|\s+\/>)$/```

### Character Classes
Syntax   | Description |
|:---          |:-- |
| | |
| | |
| | |
| | |
| | |
| | |
# Character Classes Application

```/^<([a-z]+)([^<]+)*(?:>(.*)<\/\1>|\s+\/>)$/```

### Flags
Syntax   | Description |
|:---          |:-- |
| | |
| | |
| | |
| | |
| | |
| | |

# Flags Application

```/^<([a-z]+)([^<]+)*(?:>(.*)<\/\1>|\s+\/>)$/```


### Grouping and Capturing
Syntax   | Description |
|:---          |:-- |
| | |
| | |
| | |
| | |
| | |
| | |
# Grouping and Capturing Application

```/^<([a-z]+)([^<]+)*(?:>(.*)<\/\1>|\s+\/>)$/```


### Bracket Expressions
Syntax   | Description |
|:---          |:-- |
| | |
| | |
| | |
| | |
| | |
| | |


# Bracket Expressions Application

```/^<([a-z]+)([^<]+)*(?:>(.*)<\/\1>|\s+\/>)$/```

### Greedy and Lazy Match
Syntax   | Description |
|:---          |:-- |
| | |
| | |
| | |
| | |
| | |
| | |


# Greedy and Lazy Match Application

```/^<([a-z]+)([^<]+)*(?:>(.*)<\/\1>|\s+\/>)$/```

### Boundaries
Syntax   | Description |
|:---          |:-- |
| | |
| | |
| | |
| | |
| | |
| | |
# Boundary Application

```/^<([a-z]+)([^<]+)*(?:>(.*)<\/\1>|\s+\/>)$/```

### Back-references
Syntax   | Description |
|:---          |:-- |
| | |
| | |
| | |
| | |
| | |
| | |
# Back-references Application

```/^<([a-z]+)([^<]+)*(?:>(.*)<\/\1>|\s+\/>)$/```

### Look-ahead and Look-behind
Syntax   | Description |
|:---          |:-- |
| | |
| | |
| | |
| | |
| | |
| | |
# Look-ahead and Look-behind application

```/^<([a-z]+)([^<]+)*(?:>(.*)<\/\1>|\s+\/>)$/```

## Author
Profile: https://github.com/Afaed

Afaed (real Name Justin Choy) is a programmer (by accident!) based in California. His hobbies are playing games, reading books about politics, and dunking on internet libertarians. He studies programming to become a game dev and make the game of his dreams!
