# if文について
- ### Kotlinのifは文ではなく、式として使用可能
例では、xがyより大きい場合にはresultにx is greaterを、そうでない場合はy is greaterを入れる。  
例）  
```Kotlin
val result = if (x > y) "x is greater" else "y is greater"
```
- ### NULLセーフなif文
Kotlinでは、if文の条件式内でセーフコール演算子（?.）を使用できる。  
例では、strがNULLだった場合には0を、そうでない場合はstrのlengthをlengthに入れる。  
例）  
```Kotlin
val length = str?.length ?: 0
```
