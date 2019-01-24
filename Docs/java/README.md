### Java learning notes is here

# Basics

## features of JAVA

1.independent of - Platform, Architecture, Operating Systems, space, mars, earth
2.Open source - No need to pay note even 1 cent for it. Of course, Oracle updated their licenses for Java 11 for production Environments
3.More reliable
4.Great performance for bigger applications compared to other programming languages
5.More important : have to learn because most of Hadoop Evn depends on Java

## Environment setup

its pretty easy to setup Environment. there are two things need to do

1. Install jdk
2. Install eclipse

### 1. install jdk:

installing jdk is pretty easy if your debian configured to repository. Run following commands, if you are using ubuntu OS

	sudo apt-get install openjdk-8-jdk


### validation

	varma@varma:~/Documents/GitHub/BigDataLearning$ java --version
	openjdk 11.0.1 2018-10-16
	OpenJDK Runtime Environment (build 11.0.1+13-Ubuntu-2ubuntu1)
	OpenJDK 64-Bit Server VM (build 11.0.1+13-Ubuntu-2ubuntu1, mixed mode, sharing)
	varma@varma:~/Documents/GitHub/BigDataLearning$ 

### 2. install eclipse

It is pretty easy as ubuntu software center provides eclipse installer directly. open ubuntu software center, search for it and click on install. 

# Journey to learn JAVA

There are two main tasks have to perform in Java, not like python.

	1. write the code
	2. compile the code

once we compile the code, it will create/generate ".class" file which is real executable for our application or code.

### Note : All my practiced Java code is at "code/java_learning/" in repository


# Topic - Keywords

1. DataTypes
2. Exception
3. modifiers
4. classes & object
5. coditions & loop
6. unused
7. method
8. Asset

## 1. DataTypes:

There are 8 data types in java. They are,

	byte
	boolean
	char
	short
	int
	float
	long
	double
## 2. Exceptions

there are 5 error handlers or expcetions in java. They are,

	try
	throw
	throws
	catch
	finally

## 3.modifiers, 11 modifiers are given below
	private
	public
	protected
	
	static
	final
	native
	abstract
	transient
	sychronized
	strictfp

## 4.classes & objects (11)
	class
	interface
	enum
	extends
	implements
	this
	super
	instanceof
	package
	import
	new

## 5. conditions & loop (10)
	for
	while
	do
	continue
	break
	switch
	case
	default
	if
	else

## 6. unused(2)
	goto
	const

## 7. method(2)
	void
	return

another one - 'Asset' keyword


## Exercises

1. helloWorld example


# FAQ for now?

1. Do we have to declare class as public?
Ans : Not mandatory. it could be either public or not
2. Do we heed to have file name and class name matching?
Ans : if class is defined as public, Yes they have to be matched
3. Do we need to define the main method argument name as args?
Ans : not mandatory,but recommended
4. Do we need to have main(-) public?
Ans : yes, main method has to be public


