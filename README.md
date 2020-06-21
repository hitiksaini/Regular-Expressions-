# Regular-Expressions-
The phrase regular expressions, also called regexes, is often used to mean the specific, standard textual syntax for representing patterns for matching text, as distinct from the mathematical notation described below. 
## Defination
A regular expression (shortened as regex or regexp also referred to as rational expression) is a sequence of characters that define a search pattern. Usually such patterns are used by string searching algorithms for "find" or "find and replace" operations on strings, or for input validation. It is a technique developed in theoretical computer science and formal language theory.

The concept arose in the 1950s when the American mathematician Stephen Cole Kleene formalized the description of a regular language. The concept came into common use with Unix text-processing utilities. Different syntaxes for writing regular expressions have existed since the 1980s, one being the POSIX standard and another, widely used, being the Perl syntax.
Regular expressions are used in search engines, search and replace dialogs of word processors and text editors, in text processing utilities such as sed and AWK and in lexical analysis. Many programming languages provide regex capabilities either built-in or via libraries.

## Python RegEx
Python has a built-in package called re, which can be used to work with Regular Expressions.

## RegEx Module
Import the re module:

`import re`
When you have imported the re module, you can start using regular expressions:

## RegEx Functions
The re module offers a set of functions that allows us to search a string for a match:

`findall	- Returns a list containing all matches
search	- Returns a Match object if there is a match anywhere in the string
split	- Returns a list where the string has been split at each match
sub	- Replaces one or many matches with a string`


## Metacharacters
Metacharacters are characters with a special meaning:

[]	A set of characters	"[a-m]"	
\	Signals a special sequence (can also be used to escape special characters)	"\d"	
.	Any character (except newline character)	"he..o"	
^	Starts with	"^hello"	
$	Ends with	"world$"	
*	Zero or more occurrences	"aix*"	
+	One or more occurrences	"aix+"	
{}	Exactly the specified number of occurrences	"al{2}"	
|	Either or	"falls|stays"	
()	Capture and group

## Still confused?
Contact: [Hitik](https://hitik20.tech)
email: (hitik9045saini@gmail.com)
