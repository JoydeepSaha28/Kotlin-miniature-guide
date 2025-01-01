Just a Kotlin Code Snippets/Syntax guide!!!
1. const vs val
   const - Only compile time initialization.
   val - Can be runtime initialization
```kotlin
//const and val
const val name = "Hello"
fun main() {
//Cannot be initialized in runtime and connot be local variable
//const val name = getName()
  val name2 = getName()
    
  println("$name and $name2")
}

fun getName():String{
  return "World"
}
```
