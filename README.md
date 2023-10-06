# gonatr

A collection of generator

```bash
go get github.com/ahmadhabibi14/gonatr
```

```go
package main

import (
	"fmt"
	"github.com/ahmadhabibi14/gonatr"
)

func main() {
	myID := gonatr.GenerateRandomID(8)
	fmt.Println("My ID is : ", myID)
}
```

#### TODO

- Random Number Generator
- Color Palette Generator