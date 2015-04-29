curr
=====

Current file and dir privider for Golang.

Sugar for [runtime](https://golang.org/pkg/runtime/).

```go
import "curr"

// __FILE__
f := curr.File()

// __DIR__
d := curr.Dir()

// __LINE__
l := curr.Line()

// __FUNCTION__
fn := curr.Func()

// basename(__FILE__)
b := curr.Basename()
```
