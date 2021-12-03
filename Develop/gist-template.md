# TutorIt Match an Email  

This is a tutorial of a gist doc demonstrating the process of this particular regex component. As there are many components of reg such as find matching username, phone#, url or basically any collection sequence. TutorIt will be reviewing the regex component of matching an email!
## Summary

Finding matched email is essential because emails are private information and depending where the are located they are hard to spot. To dive a bit deeper  

## Table of Contents

- [Anchors](#anchors)
- [Quantifiers](#quantifiers)
- [Grouping Constructs](#grouping-constructs)
- [Bracket Expressions](#bracket-expressions)
- [Character Classes](#character-classes)
- [The OR Operator](#the-or-operator)
- [Flags](#flags)
- [Character Escapes](#character-escapes)

## Regex Components
There are multiple components of regex the jist is a sequence of characters that defined the search pattern. To verify whether a given input string is a valid e-mail id match it with the following is the regular expression to match an e-mail id − "^[a-zA-Z0-9+_.-]+@[a-zA-Z0-9.-]+$"

### Anchors
the two anchors in regex are ^ and $.
^ manner that the following code ought to appear at the start of the string.
/$ manner that the previous code need to appear on the given string.
due to the fact our normal expression incorporates both, a given string have to fit all of the given specs precisely, or it may not be a in shape.
although this sounds limiting, you may see how quantifiers, grouping and bracket expressions allow a big variety of variation inside the given string.

### Quantifiers
Quantifiers are used to specify how commonly a given individual is predicted to appear.

Our regex uses  quantifiers, + and 2,6.

In our expression, [a-z0-9_.-]+ means that any person matching the characters within the brackets is expected to appear at least as soon as, with out a upper restrict.

The equal is genuine of [\da-z.-]+

[a-z.]2,6 way that 2 to 6 characters matching the ones in the brackets are predicted. The numbers in the curly braces specify the decrease and higher restrict of the quantity of characters anticipated.

### Grouping Constructs
Grouping is carried out with ( ) in regex.

anything within a hard and fast of parentheses is taken as a single institution, which permits all of the data internal to be handled as a single unit.

study the complete expression, paying unique interest to the parentheses.

/^([a-z0-9_.-]+)@([\da-z.-]+).([a-z.]2,6)$/

between /^ and $/, there are three awesome person agencies, ([a-z0-9_.-]+), ([\da-z.-]+), and ([a-z.]2,6).

If we dispose of the inner logic, the regex may be expressed this way: (1)@(2).(3). that is a lot simpler to examine, and corresponds to what we recognize approximately email addresses, which constantly observe the (string)@(internet site).(com/edu/and so on) template.

### Bracket Expressions
The very last piece vital to our RegEx is bracket expressions. There are 3 within our code:

[a-z0-9_.-], [\da-z.-], and [a-z.]

A bracket expression represents a single man or woman. The character may be some thing designated inside the brackets. So, as an example, in [a-z0-9_.-], this individual can be matched by way of any lowercase letters from a-z, any digit from 0-9, or a length.

combined with the quantifier +, this piece of code approach that any range of characters matching those special within the brackets will in shape.
### Character Classes
Regex has unique person instructions that suit types of characters.

In our expression, \d is used to suit any digit character.

The backslash is vital with the intention to differentiate the digit elegance from a definite letter d.

even though we simplest have one individual elegance within the expression, the behavior-changing characteristic of a backslash is useful in information any other often used a part of the expression, ".".

in contrast to the opposite person commands, \d, \w (matching a phrase man or woman) and \s (matching a whitespace individual), the individual class ".", which suits any individual, does no longer require a backslash.

due to the specific behavior of ".", the backslash must be used to negate its use as a man or woman elegance and interpret it because the person ".".
### The OR Operator
### Flags
### Character Escapes

## Author
Crystal Soto-Estrada is the Author off this gist. She lives in Irving,TX. 
https://github.com/Kristal4673

