<!-- Start SDK Example Usage -->
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
    res, err := s.GetUsers(ctx)
    if err != nil {
        log.Fatal(err)
    }

    if res.GetUsers200ApplicationJSONStrings != nil {
        // handle response
    }
}
```
<!-- End SDK Example Usage -->