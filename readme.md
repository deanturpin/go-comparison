# Gopher

- Designed as a "systems" language
- Good all-rounder
- Syntax like C but simpler
- Garbage collection
- 25-ish keywords
- Compiled
- Strongly-typed
- Functions are first class citizens
- Capitalise routines that you want to expose

# Go workspace
```
~/go/
	src
	pkg
	bin
```

# Type inference
```c++
auto a = 10;
auto b = 10.0;
```
```go
a := 10
b := 10.0
```

```c++
int main () {
}
```
```go
package main
import {
	"fmt"
	"runtime"
}

func main() {
	fmt.Println("Hello from ", runtime. GOOS);
}
```

# Compile and run
```bash
go run hello.go
```

# Variables and contants
Go passes by value not reference.

```c++
```
```go
var name string = "Ken"
```

Initialise at declaration
```c++
```
```go

// Package level declaration
var {
	first, second, age = "kenny", "key", 70.0
}

// Local declaration
func main() {

	// Use := operator when declaring, = when assigning
	a := 10
	const b = 10.0
}
```

# Environment variables
```go
```

```c++
```
```go
```

```c++
```
```go
```

```c++
```
```go
```
