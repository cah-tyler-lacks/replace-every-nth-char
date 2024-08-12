## Task
Write a method, that replaces every nth occurrence found of oldChar with char newChar.  

## Inputs
**_n_**: change the target letter (oldChar) every nth occurrence  
**_oldChar_**: the targetted character  
**_newChar_**: the character to use as replacement  
**_text_**: the string to modify  

## Business Rules
* Your method has to be case sensitive!  
* If n is 0 or negative or if it is larger than the count of the oldChar, return the original text without a change.

## Example 1:
```
INPUTS  
n:       2  
oldChar: 'a'  
newChar: 'b'  
text:    "aaaaaa"
          123456 -> 2nd 4th and 6th occurrences of 'a' are replaced with 'b'  
RESULT:  "ababab"  
```

## Example 2:
```
INPUTS  
n:       3  
oldChar: 's'  
newChar: 't'  
text:    "sally sold seashells by the seashore"  
          1     2    3  4    5        6  7     -> 3rd and 6th occurrences of 's' are replaced with '7'  
RESULT:  "sally sold teashells by the teashore"  
```
