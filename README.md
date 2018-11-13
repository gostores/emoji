# Emoji
Emoji is a simple golang package.

```
go get github.com/govenue/emoji
```

Import it:

```
import (
	"github.com/govenue/emoji"
)
```

## Usage

```go
package main

import (
	"fmt"

	"github.com/govenue/emoji"
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
