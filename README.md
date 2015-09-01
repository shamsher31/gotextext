# gotextext

[![Godoc](http://img.shields.io/badge/godoc-reference-blue.svg?style=flat)](https://godoc.org/github.com/shamsher31/gotextext)
[![Build Status](https://travis-ci.org/shamsher31/gotextext.svg)](https://travis-ci.org/shamsher31/gotextext)

List of text file extensions for Go

### How to install
```go
go get github.com/shamsher31/gotextext
```

### How to use
```go
package main

import (
	"fmt"
	"github.com/shamsher31/gotextext"
)

func main() {
	fmt.Println(textext.Get())
}
```

### Why
This package is inspired by [text-extensions](https://www.npmjs.com/package/text-extensions) npm module.

### License
MIT © [Shamsher Ansari](https://github.com/shamsher31)
