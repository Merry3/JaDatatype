# Data Type
# Java Variables
Variables are containers for storing data values. 
In Java, there are different types of variables, for example:
•	String - stores text, such as "Hello". String values are surrounded by double quotes
•	int - stores integers (whole numbers), without decimals, such as 123 or -123
•	float - stores floating point numbers, with decimals, such as 19.99 or -19.99
•	char - stores single characters, such as 'a' or 'B'. Char values are surrounded by single quotes
•	boolean - stores values with two states: true or false
________________________________________
Declaring (Creating) Variables
To create a variable, you must specify the type and assign it a value:
Syntax
type variableName = value; or
type variableName;
variable=value;

The general rules for naming variables are:
•	Names can contain letters, digits, underscores, and dollar signs
•	Names must begin with a letter
•	Names should start with a lowercase letter and it cannot contain whitespace
•	Names can also begin with $ and _ (but we will not use it in this tutorial)
•	Names are case sensitive ("myVar" and "myvar" are different variables)
•	Reserved words (like Java keywords, such as int or boolean) cannot be used as names
//**You can also use the + character to add a variable to another variable:

# Java Data Types
As explained in the previous chapter, a variable in Java must be a specified data type:
Example
int myNum = 5;               // Integer (whole number)
float myFloatNum = 5.99f;    // Floating point number
char myLetter = 'D';         // Character
boolean myBool = true;       // Boolean
String myText = "Hello";     // String

Data types are divided into two groups:
•	Primitive data types - includes byte, short, int, long, float, double, boolean and char
•	Non-primitive data types - such as String, Arrays and Classes (you will learn more about these in a later chapter)
________________________________________

type casting - convert the following double type (myDouble) to an int type:

double myDouble = 9.78d;
int myInt =   myDouble;
Primitive Data Types
A primitive data type specifies the size and type of variable values, and it has no additional methods.
There are eight primitive data types in Java:

# Strings
The String data type is used to store a sequence of characters (text). String values must be surrounded by double quotes:
Basically, string is a sequence of characters but it's not a primitive type. When we create a string in java, it actually creates an object of type String. String is immutable object which means that it cannot be changed once it is created. String is the only class where operator overloading is supported in java.
A string buffer is like a String , but can be modified. At any point in time it contains some particular sequence of characters, but the length and content of the sequence can be changed through certain method calls. String buffers are safe for use by multiple threads.

The String type is so much used and integrated in Java, that some call it "the special ninth type".
A String in Java is actually a non-primitive data type, because it refers to an object. The String object has methods that are used to perform certain operations on strings. Don't worry if you don't understand the term "object" just yet. We will learn more about strings and objects in a later chapter.


# Non-Primitive Data Types
Non-primitive data types are called reference types because they refer to objects.
The main difference between primitive and non-primitive data types are:
•	Primitive types are predefined (already defined) in Java. Non-primitive types are created by the programmer and is not defined by Java (except for String).
•	Non-primitive types can be used to call methods to perform certain operations, while primitive types cannot.
•	A primitive type has always a value, while non-primitive types can be null.
•	A primitive type starts with a lowercase letter, while non-primitive types starts with an uppercase letter.
•	The size of a primitive type depends on the data type, while non-primitive types have all the same size.
Examples of non-primitive types are Strings, Arrays, Classes, Interface, etc. You will learn more about these in a later chapter.
________________________________________
**coordinate
Point coordinates = new Point(x, y);

