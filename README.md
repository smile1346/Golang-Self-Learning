# Golang-Self-Learning

## Description
I am interested in golang language so have started to study it. and collect the knowledge that I have shared in this repo.
___
## Basic Structure
```
package main

import "fmt"

func main() {
	fmt.Println("Hello, 世界")
}
```
> The structure consists of `package`, `import` and `function main`, which is similar to C and JAVA.
> 
> `fmt` is an abbreviation for format, which is used to manage the input and output of a program.
___
## Defining variables
you can use `var` for define variable. (You can also define multiple variables at the same time.)

Example:
```
var x, y , z bool
```
> If you print x, y, z without specifying values, Go will return the default values ​​of the variables instead of an error. (In the example it shows 'false')

you can use `:=` for difine varaiable and value and no need to set type, Go will check and set the type of variable for you. 
___
## Loop
```
package main

import "fmt"

func main() {
  numOfLoop := 10
  for i:=0; < i<numOfLoop; i++ {
    code...
  }
}
```
___
## References
- [Go Playground](https://go.dev/play/p/MAohLsrz7JQ)
- [BrontoDev Channel](https://www.youtube.com/watch?v=2CzmtwDKm5Q)
___
