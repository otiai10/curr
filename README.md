curr
=====

[![CircleCI](https://circleci.com/gh/otiai10/curr.svg?style=svg)](https://circleci.com/gh/otiai10/curr)
[![codecov](https://codecov.io/gh/otiai10/curr/branch/master/graph/badge.svg)](https://codecov.io/gh/otiai10/curr)
[![Go Report Card](https://goreportcard.com/badge/github.com/otiai10/curr)](https://goreportcard.com/report/github.com/otiai10/curr)
[![GoDoc](https://godoc.org/github.com/otiai10/curr?status.svg)](https://godoc.org/github.com/otiai10/curr)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

Current file and dir privider for Golang.

Just a sugar for [runtime](https://golang.org/pkg/runtime/).

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
