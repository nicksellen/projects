Values
* number (e.g. 7, 156432, 0.00044)
* string (e.g. "kite", "I have 5 dogs")
	* ```.charAt(i)``` returns the character at index i
	* ```.toUpperCase()``` returns the string in block-caps
	* ```.length``` returns the total number of characters
	* ```.indexOf(x)``` returns the index of x from start
	* ```.trim()``` removes all whitespace from start and end
* Boolean (i.e. true, false)
* function (e.g.
* object
	* ```in``` logical operator for objects. true = 1, false = -1
	* array []
		* ```.push(x)``` add x to end
		* ```.pop()``` remove and return last item
		* ```.unshift(x)``` add x to start
		* ```.shift()``` remove and return first item
		* ```.indexOf(x)``` returns the index of x from start
		* ```.lastIndexOf(x)``` returns the index of x from end
		* ```.join(x)``` concatenate array elements with x inbetween
		* ```.slice(x,y)``` return elements from x (inc.) to y (exc.)
		* 
	* ```arguments```
	* ```window``` (global object in browsers)
* undefined (i.e. null, undefined)

Math
* ```.min```
* ```.max```
* ```.random``` generate random number between 0 (inc.) and 1 (exc.)
* ```.sqrt```
* ```.cos```
* ```.sin```
* ```.tan```
* ```.PI```
* ```.acos```
* ```.asin```
* ```.atan```
* ```.floor``` rounds down to nearest whole number
* ```.ceil``` rounds up to nearest whole number
* ```.round``` rounds to nearest whole number



Arithmetic operators
```/```	divide
```*```	multiply
```+``` add
```-```	subtract
```%``` remainder (a.k.a. 'modulo')

Incremental operators
Abbreviations for updating variables.
```frog += 5```	frog = frog + 5
```frog ++```	frog = frog + 1
```frog -= 7```	frog = frog - 7
```frog --```	frog = frog - 1
```frog *= 8```	frog = frog * 8
```frog /= 3```	frog = frog / 3

Comparison operators
```x >= y```	x greater than or equal to y
```x <= y```	x less than or equal to y
```x == y```	x equivalent to y
```x != y```	x not equivalent to y
```x === y```	x precisely equivalent to y
```x !== y```	x precisely not equivalent to y

Logical operators
```a && b```	a AND b
```a || b```	a OR b(lowest precedence operator)
```!a```	NOT a (unary operator)
```a ? c : d``` IF a THEN c ELSE d (a.k.a. 'ternery' or 'conditional' operator)
		
Defining a variable
```
var variable1 = 5;
var variable2 = true;
var variable3 = "a small sentence.";
```

if/else if/else
```
if (condition1)
	expression1;
else if (condition2)
	expression2;
else if (conditionX)
	expressionX;
else
	expressionDefault;
```

while loop
```
while(condition) {
	expression;
}
```

for loop
```
for(initiation; condition; update) {
	body;
}
```
	
