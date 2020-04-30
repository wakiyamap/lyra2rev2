[![Build Status](https://travis-ci.org/bitgoin/lyra2rev2.svg?branch=master)](https://travis-ci.org/bitgoin/lyra2rev2)
[![GoDoc](https://godoc.org/github.com/bitgoin/lyra2rev2?status.svg)](https://godoc.org/github.com/bitgoin/lyra2rev2)
[![GitHub license](https://img.shields.io/badge/license-MIT-blue.svg)](https://raw.githubusercontent.com/bitgoin/lyra2rev2/LICENSE)


# lyra2rev3

## Overview

This  is Lyra2REv3 library used in Vertcoin

## Installation

     $ go get github.com/adamcollier1/lyra2rev3


## Example
(This example omits error handlings for simplicity.)

```go

import "github.com/adamcollier1/lyra2rev3"

func main(){
    data := []byte{0x01,0x02}
	result, err := lyra2rev3.SumV3(data)
...
}
```


# Contribution
Improvements to the codebase and pull requests are encouraged.
