# Title regex-rexpress

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
Anchors are part of a group of Regex tokens referred to as "Meta" characters, distinct from "Literals" that match specific characters. Anchors serve to indicate specific positions within a string, such as the beginning, end of a line, or a specified location in between. These anchor tokens include "Boundaries" and "Delimiters." In the given snippet, we observe the utilization of the "^Caret" anchor, which signifies the starting point as well as the beginning of a string. Additionally, we encounter the "$Dollar" anchor, which denotes the end of the string.

    ^ -- $
### Quantifiers
Quantifiers play a pivotal role in pinpointing a specific occurrence of a group or class of characters in a string, with {n} exemplifying the most basic type of quantifier. In the provided example, the application of quantifiers takes the form of +Plus. In this context, +Plus dictates a match that occurs at least once, thereby enabling the user to enter multiple characters.

    ([a-z0-9_\.-]+)

### OR Operator
The Or Operator is a token that is usually employed with Boolean values and can also yield a Boolean result. However, this operator differs as it returns a specified operand, even when used without a Boolean value, resulting in a non-boolean value. In the given Regex example, the Or Operator is not utilized.

### Character Classes
Character Classes serve the purpose of defining a set of specific characters, such as A, B, C, or indicating a range like a-z for lowercase letters and 0-9 for numbers. In the given example, classes are used to specify user input, allowing lowercase letters from "a" to "z" and numbers from "0" to "9". Additionally, a \Backslash, ".", and "-" are included in the class to allow for periods and hyphens.

    a-z0-9_\.-

### Flags
In the given context, flags serve as an optional token utilized to search for either the "g" Global or "i" Ignore parameter. When the "g"-flag is included, we can evaluate against all potential matches within a string, whereas excluding it allows us to solely test the first possible match. These flags alter our search behavior and can introduce additional parameters like case sensitivity. However, in the current example, the usage of flags is not demonstrated.

### Grouping and Capturing
The contents matched by a group within parentheses can be captured and referenced later in the regex pattern or in the result of a regex match. Capturing groups are created by placing parentheses around the desired subpattern.

### Bracket Expressions
There are two types of Bracket Expressions: the Matching List Expression and the Non-Matching List Expression. They contain at least one expression, which can include ordinary characters, collating elements, symbols, and even classes. In this case, we are using brackets ([]), along with the caret (^) at the beginning, to match any single character.

    ^([-----]--)

### Greedy and Lazy Match
By default, regular expressions are greedy. This means that they will match as much of the string as possible while still allowing the overall pattern to match. A lazy match, also known as a non-greedy or reluctant match, will match as little of the string as possible while still allowing the overall pattern to match.

### Boundaries
Boundaries are metacharacters that specify positions in the input string where matches can occur. They don't match actual characters, but instead match positions.

### Back-references
Backreferences in regular expressions are a way to refer back to groups that have been matched earlier in the same pattern.

### Look-ahead and Look-behind
Lookahead and lookbehind are types of assertions in regular expressions that let you match a pattern only if it is followed by another pattern (lookahead) or preceded by another pattern (lookbehind) without including the second pattern in the match. These are known as "zero-width assertions" because they don't consume characters in the string, but only assert whether a match is possible or not.

## Author
<br>

### <span style="color:green">**Matt Fleming**</span>

GitHub Link:
<br>
https://github.com/chartpro-com

Email:
<br>
mjf@chartpro.com