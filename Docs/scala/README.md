# scala basics

these are the topics for scala learning.. of course, all practiced programs will be under code Directory.

## topics

1. basics of scala and installation
2. data types



## basics of scala and installation

scala is pure object oriented programming language and simplified version of java. It also supports functional program just like Python.

installation is pretty straight forward. Run below command to install scala in your machine. 

Note: this will work if you have ubuntu desktop. If you are using window machine, download MSI or .exe file to install it. 

Onc everything is installed properly, we will see screen like below if you check scala version

!(scala version)[https://github.com/psanthoshkumar/BigDataLearning/blob/master/pictures/sclala_version.png]

#### pre-reqs : java has to be installed and little java knowledge is required to understand Scala programming. 


## data types

scala doesn't have primitive data types. int, float, string whatever it is, they identified as objects.

##### objects

	Sr.No 		Data Type 	Description
	1		Byte		8 bit signed value. Range from -128 to 127
	2		Short		16 bit signed value. Range -32768 to 32767
	3		Int 		32 bit signed value. Range -2147483648 to 2147483647
	4		Long 		64 bit signed value. -9223372036854775808 to 9223372036854775807
	5		Float 		32 bit IEEE 754 single-precision float
	6		Double 		64 bit IEEE 754 double-precision float
	7		Char 		16 bit unsigned Unicode character. Range from U+0000 to U+FFFF
	8		String 		A sequence of Chars
	9		Boolean		Either the literal true or the literal false
	10		Unit 		Corresponds to no value
	11		Null		null or empty reference
	12		Nothing 	The subtype of every other type; includes no values
	13		Any 		The supertype of any type; any object is of type Any
	14		AnyRef 		The supertype of any reference type


##### Escape Sequences
The following escape sequences are recognized in character and string literals.

	Escape Sequences	Unicode	Description
	\b	\u0008	backspace BS
	\t	\u0009	horizontal tab HT
	\n	\u000c	formfeed FF
	\f	\u000c	formfeed FF
	\r	\u000d	carriage return CR
	\"	\u0022	double quote "
	\'	\u0027	single quote .
	\\	\u005c	backslash \

##### Variable Declaration
Scala has a different syntax for declaring variables. They can be defined as value, i.e., constant or a variable. Here, myVar is declared using the keyword var. It is a variable that can change value and this is called "mutable variable". Following is the syntax to define a variable using var keyword −

	Syntax
	var myVar : String = "Foo"

Here, myVal is declared using the keyword val. This means that it is a variable that cannot be changed and this is called "immutable variable". Following is the syntax to define a variable using val keyword −

	Syntax
	val myVal : String = "Foo"

