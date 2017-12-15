# Emoji
Emoji is a simple golang package.

```
go get github.com/gostores/emoji
```

Import it:

```
import (
	"github.com/gostores/emoji"
)
```

## Usage

```go
package main

import (
	"fmt"

	"github.com/gostores/emoji"
)

func main() {
	fmt.Println("Hello World Emoji!")

	emoji.Println(":beer: Beer!!!")

	pizzaMessage := emoji.Sprint("I like a :pizza: and :sushi:!!")
	fmt.Println(pizzaMessage)
}
```

## License

[MIT](https://github.com/kyokomi/emoji/blob/master/LICENSE)
