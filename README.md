# **Table of Contents**
### *1. What is a Method in js?*
### *2. String*
### *3. Number*
___ 
___
| What is a Method in js? |
| - |
| A method is a block of code which only runs when it is called. You can pass data, known as parameters, into a method. Methods are used to perform certain actions, and they are
also known as functions. |

| JAVA SCRIPT STRING METHODS |
| - |
| String length. String slice(). String substring(). String substr(). String replace(). String replaceAll(). String toUpperCase(). String toLowerCase(). String concat(). String trim(). String charAt(). String split() |

#### JavaScript String Length
>The length property returns the length of a string:

[1](/images/Снимок экрана 2023-02-21 142039.png)

#### Extracting String Parts
- slice(start, end)
- substring(start, end)
- substr(start, length)

#### JavaScript String slice()

> slice() extracts a part of a string and returns the extracted part in a new string.
The method takes 2 parameters: start position, and end position (end not included).

[2](/images/Снимок экрана 2023-02-21 142731.png)



#### JavaScript String substring()

> substring() is similar to slice().
The difference is that start and end values less than 0 are treated as 0 in substring().

[3](/images/Снимок экрана 2023-02-21 142929.png)

#### JavaScript String substr()

> substr() is similar to slice().
The difference is that the second parameter specifies the length of the extracted part.

[4](/images/Снимок экрана 2023-02-21 143032.png)



#### Replacing String Content

> The replace() method replaces a specified value with another value in a string:

[5](/images/Снимок экрана 2023-02-21 143138.png)



#### JavaScript String ReplaceAll()

> The replaceAll() method allows you to specify a regular expression instead of a string to be replaced.
If the parameter is a regular expression, the global flag (g) must be set set, otherwise a TypeError is thrown.

[6](/images/Снимок экрана 2023-02-21 143324.png)



### Converting to Upper and Lower Case

- A string is converted to upper case with toUpperCase():
- A string is converted to lower case with toLowerCase():

#### JavaScript String toUpperCase()

[7](/images/Снимок экрана 2023-02-21 143617.png)


#### JavaScript String toLowerCase()

[8](/images/Снимок экрана 2023-02-21 143655.png)




#### JavaScript String concat()
> concat() joins two or more strings:

[9](/images/Снимок экрана 2023-02-21 143741.png)



#### JavaScript String trim()
> The trim() method removes whitespace from both sides of a string:

[10](/images/Снимок экрана 2023-02-21 143823.png)



#### JavaScript String split()
> A string can be converted to an array with the split() method:

[11](/images/Снимок экрана 2023-02-21 143947.png)
