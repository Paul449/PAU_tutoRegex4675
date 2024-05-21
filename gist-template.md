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

The following components that I will be explaining are enclosed using slash (/)
to define our string using regular expression and deciding what conditions to give
to our string to make different type of matches.

### Anchors

Anchors allow us to define how our string is going to start and end. The two main anchors are caret(^) and dollar sign($)
the caret(^) define the beginning of our string
The dollar sign($) define the ending of our string

### Quantifiers

Quantifiers allow us to set a limit of how many times we can make a character to be repeated


### Character Classes

### Flags

Flags are paramaters used if we want to alter the behavor when doing a search pattern to any kind of string we specify.
The most common flags are the following:

   \d: this flag generates indices to match substrings
   \i: this flag means if we want our search to be case-insensitive, no matter if there are uppercase or lowercase letters
   \g: stands for global search, which means the string should be tested with any match being made

### Grouping and Capturing

### Bracket Expressions

### Greedy and Lazy Match

### Boundaries

### Back-references

### Look-ahead and Look-behind

## Author

Author: Paul Bilbatua

repository link: https://github.com/Paul449/PAU_tutoRegex4675
