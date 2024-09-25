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
