# Gin Default Server

This is API experiment for Gin.

```go
package main

import (
	"e.coding.net/fireorange/customize/gin"
	"e.coding.net/fireorange/customize/gin/ginS"
)

func main() {
	ginS.GET("/", func(c *gin.Context) { c.String(200, "Hello World") })
	ginS.Run()
}
```
