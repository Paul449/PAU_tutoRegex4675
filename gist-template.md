# Regex-Matching an Email

The purpose of this tutorial is to explain how we can implement regular expressions when matching with any email depending
the name, domain, and extension defined. This will help us when creating our server-side API and we want to specify to the
client the rules needed to be used when trying to access to our server. Regular expressions can also apply for any other string examples.

## Summary

I will be explaning how we can regular expressions when it comes to specifying an email to be matched with the requirements or conditions
we are providing to the client. 

An email is divided into three parts:

1.- Username

2.- Separator

3.- Domain Name

Here is an example of how regular expressions are being used when matching with email using Github gist.

code snippet:

\`^[-A-Za-z0-9!#$%&'*+/=?^_`{|}~]+(?:\.[-A-Za-z0-9!#$%&'*+/=?^_`{|}~]+)*@(?:[A-Za-z0-9](?:[-A-Za-z0-9]*[A-Za-z0-9])?\.)+[A-Za-z0-9](?:[-A-Za-z0-9]*[A-Za-z0-9])?$\`

## Table of Contents

- [Anchors](#anchors)
- [Quantifiers](#quantifiers)
- [Character Classes](#character-classes)
- [Flags](#flags)
- [Grouping and Capturing](#grouping-and-capturing)
- [Escape Sequences](#Escape Sequences)
- [Literal Characters](#Literal Characters)

## Regex Components

The following components that I will be explaining are enclosed using slash (/)
to define our string using regular expression and deciding what conditions to give
to our string to make different type of matches.

### Anchors

Anchors allow us to define how our string is going to start and end. The two main anchors are caret(^) and dollar sign($)

1. the caret(^) define the beginning of our string

2. The dollar sign($) define the ending of our string

### Quantifiers

Quantifiers allow us to set a limit of how many times we can make a character to be repeated

1. `+`: This quantifier allow us to match one or even more than one character from our string
2. `*`: it matches zero or more characters from our string
3. `?`: it also matches zero or more characters from our string

### Character Classes

1. [-A-Za-z0-9!#$%&'*+/=?^_`{|}~`]: this specific part matches one or more characters that are alphanumeric

2. [A-Za-z0-9]: This is responsible for matching any alphanumeric characters

### Flags

Flags are paramaters used if we want to alter the behavor when doing a search pattern to any kind of string we specify.
The most common flags are the following:

  1. `\d`: this flag generates indices to match substrings
  2. `\i`: this flag means if we want our search to be case-insensitive, no matter if there are uppercase or lowercase letters
  3. `\g`: stands for global search, which means the string should be tested with any match being made

but in this case, I did not defined any flag

### Grouping and Capturing

1. `(...)`: allow us to separate grouping of characters by using parenthesis
2. `(?:...)`: we can group our characters without capturing anything
3. `[...]`: we are defining different character classes inside squared brackets
4. `('-')`: it defines a particular range between characters, for example a-z or 0-9

### Escape Sequences

1. `\`:it matches a dot character in our string
2. `\\`: used for matching for special characters

### Literal Characters

refers to characters that matches by itself without being grouped. The clear example used in my code snippet is @ and it only matches by itself

## Author

Author: Paul Bilbatua

repository link: https://github.com/Paul449/PAU_tutoRegex4675
