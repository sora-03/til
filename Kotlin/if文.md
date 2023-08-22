# if文について
- ### Kotlinのifは文ではなく、式として使用可能
例）  `val result = if (x > y) "x is greater" else "y is greater"`
- ### NULLセーフなif文
Kotlinでは、if文の条件式内でセーフコール演算子（?.）を使用できる。  
例では、strがNULLだった場合は0をlengthに入れるようになる。

例）`val length = str?.length ?: 0`
