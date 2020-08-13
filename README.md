# consolesize-go

[![GoDoc](https://godoc.org/github.com/nathan-fiscaletti/consolesize-go?status.svg)](https://godoc.org/github.com/nathan-fiscaletti/consolesize-go)

**consolesize-go** is a library that will allow you to read the size of any console window on both **Unix** and **Windows** systems.

## Install

```sh
$ go get github.com/nathan-fiscaletti/consolesize-go
```

## Usage

```go
package main

import (
    "fmt"

    "github.com/nathan-fiscaletti/consolesize-go"
)

func main() {
    cols, rows := consolesize.GetConsoleSize()
    fmt.Printf("Rows: %v, Cols: %v\n", rows, cols)
}
```

