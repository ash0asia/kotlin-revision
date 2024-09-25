What is Kotlin?
Kotlin is a modern, trending programming language that was released in 2016 by JetBrains.
use if we use kt extension
        fun main() {
          println("Hello World")
        }   
.kt — normal source files, .kts — script files

You don't need the main function in a .kts file, It will be executed line by line just like a bash/python script.

println() and print()
There is also a print() function, which is similar to println(). The only difference is that it does not insert a new line at the end of the output:

Single-line Comments //
Multi-line Comments /* and */

The difference between var and val is that variables declared with the var keyword can be changed/modified, while val variables cannot.

var name: String
name = "John"
println(name)   //empty declare of variable 

var name: String = "John" // String
val birthyear: Int = 1975 // Int
println(name)
println(birthyear)   //declare of type of variable

// use + to add to string
val myNum = 5             // Int 
val myDoubleNum = 5.99    // Double
val myLetter = 'D'        // Char
val myBoolean = true      // Boolean
val myText = "Hello"      // String

The Byte data type can store whole numbers from -128 to 127
The Short data type can store whole numbers from -32768 to 32767
The Int data type can store whole numbers from -2147483648 to 2147483647
The Long data type can store whole numbers from -9223372036854775808 to 9223372036854775807
The precision of a floating point value indicates how many digits the value can have after the decimal point. The precision of Float is only six or seven decimal digits, while Double variables have a precision of about 15 digits. Therefore it is safer to use Double for most calculations. Also note that you should end the value of a Float type with an "F".
The Boolean data type and can only take the values true or false
The Char data type is used to store a single character. A char value must be surrounded by single quotes, like 'A' or 'c'
The String data type is used to store a sequence of characters (text). String values must be surrounded by double quotes

//  Type Conversion 
val x: Int = 5
val y: Long = x.toLong()
println(y)
oerator 
fffffffffffffffffffffffffffffffffffffffffffffffffffffffffffffffffffffffffffffffffff

String Templates/Interpolation  - $name to insert name value

if else ladder -- 
if (condition1) {
  // block of code to be executed if condition1 is true
} else if (condition2) {
  // block of code to be executed if the condition1 is false and condition2 is true
} else {
  // block of code to be executed if the condition1 is false and condition2 is false

when i place of if else for use multiple time- condition branches
val day = 4

val result = when (day) {
  1 -> "Monday"
  2 -> "Tuesday"
  3 -> "Wednesday"
  4 -> "Thursday"
  5 -> "Friday"
  6 -> "Saturday"
  7 -> "Sunday"
  else -> "Invalid day."
}
println(result)
// Outputs "Thursday" (day 4)

while (condition) {
  // code block to be executed
}

do {
  // code block to be executed
}
while (condition);
do while run atleast one run 

To create an array, use the arrayOf() function, and place the values in a comma-separated list inside it


val cars = arrayOf("Volvo", "BMW", "Ford", "Mazda")

With the for loop, you can also create ranges of values with ".."
You can also use the in operator to check if a value exists in a range


A function is a block of code which only runs when it is called.
You can pass data, known as parameters, into a function.
Functions are used to perform certain actions, and they are also known as methods.

In the following example, myFunction() will print some text (the action), when it is called
To create your own function, use the fun keyword, and write the name of the function, followed by parantheses ()

There is also a shorter syntax for returning values. You can use the = operator instead of return without specifying the return type

To create a class, use the class keyword, and specify the name of the class {} this bracket use 

In Kotlin, there's a faster way of doing this, by using a constructor.
A constructor is like a special function, and it is defined by using two parantheses () after the class name. You can specify the properties inside of the parantheses (like passing parameters into a regular function) () this braket use
You can also use functions inside a class, to perfom certain actions

