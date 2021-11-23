# Automation
# Regular Expressions
Regular Expressions, often shortened as regex, are a sequence of characters used to check whether a pattern exists in a given text (string) or not. If you’ve ever used search engines, search and replace tools of word processors and text editors - you’ve already seen regular expressions in use. They are used at the server side to validate the format of email addresses or passwords during registration, used for parsing text data files to find, replace, or delete certain string, etc. They help in manipulating textual data, which is often a prerequisite for data science projects involving text mining.

## functions
1. search()
2. group()

**.** : Matches any single character except the newline character

**^** : Matches the start of the string.

**$** : Matches the end of string.

**[abc]** : Matches a or b or c.

**[a-zA-Z0-9]** : Matches any letter from (a to z) or (A to Z) or (0 to 9).

**\s**: have three scenarios:
- space
- if \ring it is treated as a character (\r)
- if \\string it is treated as a character (\s)

**\w** : Matches any single letter, digit, or underscore.

**\W** : Matches any character not part of \w (lowercase w).

**\s** : Matches a single whitespace character like: space, newline, tab, return.

**\S** : Matches any character not part of \s (lowercase s).

**\d** : Matches decimal digit 0-9.

**\D** : Matches any character that is not a decimal digit.

**\t** : Matches tab.

**\n** : Matches newline.

**\r** : Matches return.

**\A** : Matches only at the start of the string. Works across multiple lines as well.

**\Z** : Matches only at the end of the string.

**\b** : Matches only the beginning or end of the word.

**+** : Checks if the preceding character appears one or more times starting from that position.

**Star(*)** : Checks if the preceding character appears zero or more times starting from that position.

**?**** : Checks if the preceding character appears exactly zero or one time starting from that position.

# Shutil
> import glob
> import shutil

## Functions
1. Copying Files
2. Working With Directory Trees
3. Finding Files


