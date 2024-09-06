## Goal
The goal of this exercise is to develop code using TDD and paired programming skills.

## Task
Write a method, that replaces every _**n**th_ occurrence found of **_oldChar_** with char **_newChar_**.  

## Inputs
**_n_**: change the target letter (**_oldChar_**) every nth occurrence  
**_oldChar_**: the targeted character  
**_newChar_**: the character to use as the replacement  
**_text_**: the string to modify  

## Business Rules
* Your method has to be case sensitive!  
* If n is 0 or negative or if it is larger than the count of the **_oldChar_**, return the original text without a change.

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
          1     2    3  4    5        6  7     -> 3rd and 6th occurrences of 's' are replaced with 't'  
RESULT:  "sally sold teashells by the teashore"  
```
