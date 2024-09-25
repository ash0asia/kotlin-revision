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
