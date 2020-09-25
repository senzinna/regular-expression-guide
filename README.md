# Regular Expression Guide

## digits
**expression**: `\d`  
*can be used to find any digit from 0 to 9*

***

## wildcard
**expression**: `.`  
*to match a period (`.`), you need to escape the dot by using a slash `\.`*

***

## matching specific characters
**expression**: `[]`  

***

## excludes specific characters
**expression**: `[^]`  

***

## sequential characters
**expression**: `-`  
**metacharacter** `\w` is equivalent to the character range `[A-Za-z0-9_]`  
*example: `[0-9]` -  will only match any single digit character from zero to nine

***

## excludes specific characters
**expression**: `[^]`  

***

## star && plus
**expression**: `\d*` - 0 or more  
**expression**: `\d+` - 1 or more

***

## optionality
**expression**: `?`  
*to escape it, use a slash \?*

***

## whitespace 
**expression**: `\s`  
**expression**: `\S`  

## starts and ends 
**expression**: `^` (hat)   
**expression**: `$` (dollar sign)


## match groups
**expression**: `^` (hat)   
**expression**: `$` (dollar sign)

***

<br>

# Index
expression | meaning
-----------|---------
abc… | Letters
123… | Digits
\d | Any Digit
\D | Any Non-digit character
. | Any Character
\. | Period
[abc] | Only a, b, or c
[^abc] | Not a, b, nor c
[a-z] | Characters a to z
[0-9] | Numbers 0 to 9
\w | Any Alphanumeric character
\W | Any Non-alphanumeric character
{m} | m Repetitions
{m,n} | m to n Repetitions
* | Zero or more repetitions
+ | One or more repetitions
? | Optional character
\s | Any Whitespace
\S | Any Non-whitespace character
^…$ | Starts and ends
(…)|  Capture Group
(a(bc)) | Capture Sub-group
(.*) | Capture all
(abc|def) | Matches abc or def

