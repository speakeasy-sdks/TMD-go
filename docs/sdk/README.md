# SDK

## Overview

Optional multiline or single-line description in [CommonMark](http://commonmark.org/help/) or HTML.

### Available Operations

* [GetUsers](#getusers) - Returns a list of users.

## GetUsers

Optional extended description in CommonMark or HTML.

### Example Usage

```go
package main

import(
	"context"
	"log"
	"example"
)

func main() {
    s := sdk.New()

    ctx := context.Background()
    res, err := s.SDK.GetUsers(ctx)
    if err != nil {
        log.Fatal(err)
    }

    if res.GetUsers200ApplicationJSONStrings != nil {
        // handle response
    }
}
```
