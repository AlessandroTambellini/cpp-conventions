#C++ Conventions

## Naming conventions

### 1. class
  1.1 A noun\
  1.2 First letter is uppercase\
  1.3 Uppercase as word separator, lowercase for the rest of the word\
  1.4 No underscore *(‘_’)*\
  1.5 **Private attribute** : Prepended with the character *‘m’* and follows the all the rules listed above
        
### 2. function/method
  2.1 Begins with a verb\
  2.2 First letter is lowercase\
  2.3 First letter of each word is uppercase

### 3. variable
  3.1 First char of the name is a letter\
  3.2 The only special symbol accepted is the underscore *(‘_’)*, numbers are allowed\
  3.3 **Pointer** : preceded by *‘p’* and places the asterisk ‘*’ next to the variable name instead of the pointer type\
  3.4 **Reference** : prepended with *‘r’*\
  3.5 **Static** : prepended with *‘s’*\
  3.6 **Global** : all capital letters separated with *‘_’*
 
### 4. filename
  4.1 No special character is allowed except for underscore *(‘_’)* and dash *(‘-‘)*, numbers are allowed\
  4.2 Ends with the .cc or .cpp extension\
  4.3 Do not use filenames that already exist in */user/include or* any predefined header file name
    
    
## Brackets position 

1. Round brackets detached from the **if** word and curly brakets on a new line
```
if (integer % i == 0)
{
    *body *
}
```

2. Curly brakets on a new line 
``` 
class Example
{
    *body *
}
```

3. Round brackets attached to the name of the function/method and curly brakets on a new line 
``` 
void getExample(int value)
{
    *body *
}
```

##Other conventions

|      ✔️                          |        ❌ |
| : -- -- :                        | : -- -- : |
|`if (var1)`                       |`if ( var1 )` |
|`if (var1 == var2)`               |`if (var1==var2)` |
|`if (n == m + 1)`                 |`if (n == m+1)` |
|`enum Color { red, green, blue }` |`enum Color {red, green, blue}` |
|`i += 4`                          |`i +=4` |
