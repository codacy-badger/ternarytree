# ternarytree

[![Build Status](https://travis-ci.org/mrogaski/ternarytree.svg?branch=develop)](https://travis-ci.org/mrogaski/ternarytree) 
[![codecov](https://codecov.io/gh/mrogaski/ternarytree/branch/develop/graph/badge.svg)](https://codecov.io/gh/mrogaski/ternarytree)
[![Go Report Card](https://goreportcard.com/badge/github.com/mrogaski/ternarytree)](https://goreportcard.com/report/github.com/mrogaski/ternarytree)

A Go implementation of ternary search trees as described by Jon Bentley and Robert Sedgewick.
  
Ternary search trees are interesting data structures that provide a means of storing and accessing
strings.  They combine the time efficiency of digital tries with the space efficiency of binary search trees.
Unlike a hash, they also maintain information about relative order.

## Installation

To install ternarytree package, you need to install Go and set your Go workspace first.

1. Download and install it:

```sh
$ go get -u github.com/mrogaski/ternarytree
```

2. Import it in your code:

```go
import "github.com/mrogaski/ternarytree"
```

## References

- Bentley, Jon and Sedgewick, Robert.  "Ternary Search Trees".  Dr. Dobb's
  Journal, April 1998. http://www.drdobbs.com/database/ternary-search-trees/184410528

- Bentley, Jon and Sedgewick, Robert.  "Fast Algorithms for Sorting and
  Searching Strings".  Eighth Annual ACM-SIAM Symposium on Discrete Algorithms
  New Orleans, January, 1997.  http://www.cs.princeton.edu/~rs/strings/

