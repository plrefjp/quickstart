+++
title = "プログラムの実行開始位置(Entry point)"
date = 2024-02-14T01:14:39+09:00
draft = false
tags = ['programming']
+++

```console
Hello, World!
```

`main`関数を実行開始点とする言語

```c {name="hello.c"}
#include <stdio.h>
int main(void){
  printf("Hello, World!\n");
}
```

```c++ {name="hello.cpp"}
#include <iostream>
int main() {
  std::cout << "Hello, World!" << std::endl;
}
```

```dart {name="hello.dart"}
void main() {
  print('Hello, World!');
}
```

```go {name="hello.go"}
package main
import "fmt"
func main() {
    fmt.Println("Hello, World!")
}
```

```kotlin {name="hello.kt"}
fun main() {
  println("Hello, World!")
}
```

```haskell {name="hello.hs"}
main = putStrLn "Hello, World!"
```

```rust {name="hello.rs"}
fn main() {
  println!("Hello, World!");
}
```

オブジェクトの`main`メソッドを実行開始点とする言語

```c# {name="hello.cs"}
class Hello {
  static void Main() {
    System.Console.WriteLine("Hello, World!");
  }
}
```

```java {name="hello.java"}
public class Hello {
  public static void main(String... args) {
    System.out.println("Hello, World!");
  }
}
```

```scala {name="hello.scala"}
object Hello {
  def main(args:Array[String]) {
    println("Hello, World!")
  }
}
```

最初から順に実行していく言語

```shell {name="hello.sh"}
#!/bin/sh
echo "Hello, World!"
```

```swift {name="hello.swift"}
print("Hello, World!")
```

```php {name="hello.php"}
<?php
  echo "Hello, World!";
?>
```

```javascript {name="hello.js"}
console.log("Hello, World!");
```

```python {name="hello.py"}
print("Hello, World!")
```

```ruby {name="hello.rb"}
puts "Hello, World!"
```