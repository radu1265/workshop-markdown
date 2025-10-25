# Helloworld Programs

![Hello, World!](https://github.com/radu1265/workshop-markdown/blob/helloworld/helloworld.png)


We list below Helloworld programs for diﬀerent programming languages, i.e. programs that print "Hello, World!"
. The
specified compiler or interpreter is required for each programming languages.
The table below summarizes the programs:
| Language | Language (Spec / Home) | Site Section | Build / Run Toolchain | Debian / Ubuntu Packages |
|-----------|------------------------|---------------|----------------------|---------------------------|
| C | [The Standard - C](https://www.open-std.org/jtc1/sc22/wg14/) | C | GCC | ⁠ build-essential ⁠ |
| C++ | [The Standard - C++](https://isocpp.org/) | C++ | GCC / G++ | ⁠ build-essential, g++ ⁠ |
| Dlang | [D Programming Language: Home](https://dlang.org/) | Dlang | GCC / GDC | ⁠ build-essential, gdc ⁠ |
| Go | [The Go Programming Language](https://golang.org/) | Go | Go | ⁠ golang ⁠ |
| Rust | [Rust Programming Language](https://www.rust-lang.org/) | Rust | Rust (Crate) | ⁠ rustlang ⁠ |
| Java | [Java Programming Language](https://www.java.com/) | Java | JDK | ⁠ openjdk-17-jdk ⁠ |
| x86_64 Assembly | [x86 and amd64 Instruction Set Reference](https://www.felixcloutier.com/x86/) | Assembly | GCC / GAS | ⁠ build-essential ⁠ |
| ARM64 Assembly | [Arm A64 Instruction Set (AArch64)](https://developer.arm.com/documentation/ddi0602/2024-03/Base-Instructions?lang=en) | Assembly | GCC / GAS | ⁠ build-essential ⁠ |
| Bash | [Bash Reference Manual](https://www.gnu.org/software/bash/manual/) | Bash | Bash | ⁠ bash ⁠ |
| Python | [Welcome to Python.org](https://www.python.org/) | Python | Python | ⁠ python ⁠ |
| Ruby | [Ruby Programming Language](https://www.ruby-lang.org/) | Ruby | Ruby | ⁠ ruby ⁠ |
| PHP | [PHP: Hypertext Preprocessor](https://www.php.net/) | PHP | PHP | ⁠ php ⁠ |
| Perl | [The Perl Programming Language](https://www.perl.org/) | Perl | Perl | ⁠ perl ⁠ |
| Lua | [The Programming Language Lua](https://www.lua.org/) | Lua | Lua | ⁠ lua ⁠ |

# C

```C
#include <stdio.h>
int main(void)
{
puts("Hello, World!");
return 0;
}
Build with:
gcc -Wall -o helloworld helloworld.c
Run with:
./helloworld
```
# C++

```C++
#include <iostream>
int main()
{
std::cout << "Hello, World!" << std::endl;
return 0;
}

g++ -Wall -o helloworld helloworld.cpp
Run with:
./helloworld
```
# Dlang

```D
import std.stdio;
void main()
{
writeln("Hello, World!");
}
Build with:
gdc -Wall -o helloworld helloworld.cpp
Run with:
./helloworld
```
# Go

```Go
package main
import "fmt"
func main() {
fmt.Println("Hello, World!")
}
Build and run with:
go run helloworld.go

# Rust

```Rust
fn main() {
println!("Hello, World");
}
Build with:
rustc hello.rs
Run with:
./helloworld
```
# Java

```Java
public class HelloWorld {
public static void main(String[] args) {
System.out.println("Hello, World!");
}
}
Build with:
javac HelloWorld.java
Run with:
java HelloWorld
```
# x86_64 Assembly

```x86_64 Assembly
Build with:
  TODO
Run with:
  TODO
```
# ARM64 Assembly

```
Build with:
TODO
Run with:
./helloworld
```
# Bash

```Bash
echo "Hello, World!"
Run with:

bash helloworld.sh
```

# Python

```Python
print("Hello, World!")
Run with:
python helloworld.py
```
# Ruby

```Ruby
puts "Hello, World!"
Run with:
ruby helloworld.rb
```
# Php

```Php
<?php
echo "Hello, World!"
?>
Run with:
./helloworld

```
# Perl

```Perl
print("Hello, World!\n")
Run with:
perl helloworld.pl
```

# Lua

```Lua
print("Hello, World!")
Run with:
lua helloworld.lua
```


