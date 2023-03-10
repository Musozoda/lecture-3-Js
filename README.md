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
>> ![img](/images/%D0%A1%D0%BD%D0%B8%D0%BC%D0%BE%D0%BA%20%D1%8D%D0%BA%D1%80%D0%B0%D0%BD%D0%B0%202023-02-21%20142039.png)


#### Extracting String Parts
- slice(start, end)
- substring(start, end)
- substr(start, length)

#### JavaScript String slice()

> slice() extracts a part of a string and returns the extracted part in a new string.
The method takes 2 parameters: start position, and end position (end not included).
>> ![img](/images/%D0%A1%D0%BD%D0%B8%D0%BC%D0%BE%D0%BA%20%D1%8D%D0%BA%D1%80%D0%B0%D0%BD%D0%B0%202023-02-21%20142731.png)



#### JavaScript String substring()

> substring() is similar to slice().
The difference is that start and end values less than 0 are treated as 0 in substring().
>> ![img](/images/%D0%A1%D0%BD%D0%B8%D0%BC%D0%BE%D0%BA%20%D1%8D%D0%BA%D1%80%D0%B0%D0%BD%D0%B0%202023-02-21%20142929.png)

#### JavaScript String substr()

> substr() is similar to slice().
The difference is that the second parameter specifies the length of the extracted part.
>> ![img](/images/%D0%A1%D0%BD%D0%B8%D0%BC%D0%BE%D0%BA%20%D1%8D%D0%BA%D1%80%D0%B0%D0%BD%D0%B0%202023-02-21%20143032.png)



#### Replacing String Content

> The replace() method replaces a specified value with another value in a string:
>> ![img](/images/%D0%A1%D0%BD%D0%B8%D0%BC%D0%BE%D0%BA%20%D1%8D%D0%BA%D1%80%D0%B0%D0%BD%D0%B0%202023-02-21%20143138.png)



#### JavaScript String ReplaceAll()

> The replaceAll() method allows you to specify a regular expression instead of a string to be replaced.
If the parameter is a regular expression, the global flag (g) must be set set, otherwise a TypeError is thrown.
>> ![img](/images/%D0%A1%D0%BD%D0%B8%D0%BC%D0%BE%D0%BA%20%D1%8D%D0%BA%D1%80%D0%B0%D0%BD%D0%B0%202023-02-21%20143324.png)



### Converting to Upper and Lower Case

- A string is converted to upper case with toUpperCase():
- A string is converted to lower case with toLowerCase():

#### JavaScript String toUpperCase()
>> ![img](/images/%D0%A1%D0%BD%D0%B8%D0%BC%D0%BE%D0%BA%20%D1%8D%D0%BA%D1%80%D0%B0%D0%BD%D0%B0%202023-02-21%20143617.png)


#### JavaScript String toLowerCase()
>> ![img](/images/%D0%A1%D0%BD%D0%B8%D0%BC%D0%BE%D0%BA%20%D1%8D%D0%BA%D1%80%D0%B0%D0%BD%D0%B0%202023-02-21%20143655.png)




#### JavaScript String concat()
> concat() joins two or more strings:
>> ![img](/images/%D0%A1%D0%BD%D0%B8%D0%BC%D0%BE%D0%BA%20%D1%8D%D0%BA%D1%80%D0%B0%D0%BD%D0%B0%202023-02-21%20143741.png)



#### JavaScript String trim()
> The trim() method removes whitespace from both sides of a string:
>> ![img](/images/%D0%A1%D0%BD%D0%B8%D0%BC%D0%BE%D0%BA%20%D1%8D%D0%BA%D1%80%D0%B0%D0%BD%D0%B0%202023-02-21%20143823.png)



#### JavaScript String split()
> A string can be converted to an array with the split() method:
>> ![img](/images/%D0%A1%D0%BD%D0%B8%D0%BC%D0%BE%D0%BA%20%D1%8D%D0%BA%D1%80%D0%B0%D0%BD%D0%B0%202023-02-21%20143947.png)

# 2.JavaScript Number methods 

#### JavaScript Number methods Math.round(),ceil(),floor()

The Math.floor() function rounds down a number to the next smallest integer.

![img](/images/1.png)

The Math.round() function returns the number rounded to the nearest integer

![img](/images/2.png)

The ceil() method rounds a decimal number up to the next largest integer and returns it

![img](/images/3.png)

#### JavaScript Number methods Math.max() and Math.min()

The max() method finds the maximum value among the specified values and returns it.

![img](/images/4.png)

The min() method finds the minimum value among the specified values and returns it

![img](/images/5.png)

#### JavaScript Number methods Math.pow() and Math.sqrt()

The pow() method computes the power of a number by raising the second argument
to the power of the first argument.

![img](/images/6.png)

The sqrt() method computes the square root of a specified number and returns it

![img](/images/7.png)

#### JavaScript String method Math.abs() and Math.random()

The abs() method finds the absolute value of the specified number (without any sign) and returns it.

![img](/images/8.png)

The Math.random() function returns a floating-point, pseudo-random number between 0 (inclusive) 
and 1 (exclusive). 

![img](/images/9.png)

#### JavaScript Number method isNaN()

The isNaN() function checks if a value is NaN (Not-a-Number) or not.

![img](/images/10.png)



