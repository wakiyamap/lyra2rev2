[![Build and Test](https://github.com/wakiyamap/lyra2rev2/workflows/Build%20and%20Test/badge.svg?branch=master)](https://github.com/wakiyamap/lyra2rev2/actions?query=workflow%3A%22Build+and+Test%22)
[![go.dev reference](https://img.shields.io/badge/go.dev-reference-007d9c?logo=go&logoColor=white)](https://pkg.go.dev/github.com/wakiyamap/lyra2rev2)
[![GitHub license](https://img.shields.io/badge/license-MIT-blue.svg)](https://raw.githubusercontent.com/bitgoin/lyra2rev2/LICENSE)


# lyra2rev2 with bmw,cubuhash, and lyra2 

## Overview

This  is Lyra2REv2 library used in Monacoin and some other altcoins.
Lyra2Rev2 uses [bmw hash](https://www.mathematik.hu-berlin.de/~schliebn/dl/Blue-Midnight-Wish.pdf),
[cubehash](https://en.wikipedia.org/wiki/CubeHash),[lyra2](https://en.wikipedia.org/wiki/Lyra2),
which are also included in this library.

## Requirements

This requires

* git
* go 1.13+


## Installation

     $ go get github.com/wakiyamap/lyra2rev2


## Example
(This example omits error handlings for simplicity.)

```go

import "github.com/wakiyamap/lyra2rev2"

func main(){
    data := []byte{0x01,0x02}
	result, err := lyra2rev2.Sum(data)
...
}
```


# Contribution
Improvements to the codebase and pull requests are encouraged.


