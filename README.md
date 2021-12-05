# Just-some-kotlin-code
Some important snippets of code that I think is useful 

## Initialize kotlin list with initial value
```kotlin
val list = MutableList(10){ it } // this will initialize list with 0,1,2,3...9
val list = MutableList(10){ it + 1 } // this will initialize list with 1,2,3...10
val list = MutableList(10){ 0 }  // all elemets to zero 0,0,0...
```
## Read multiple variable from input
```kotlin
val (a,b) = readLine()!!.split(' ') //input 1 2
```
```kotlin
/**input
   1
   2
   3
*/
val (a,b,c) = List(3){readLine()!!.toInt()}
```
## Reading list from input without using loop
```kotlin
val list = MutableList(10){readLine()!!.toInt()}
```
