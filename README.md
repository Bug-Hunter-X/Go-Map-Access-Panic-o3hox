# Go Map Access Panic

This repository demonstrates a common error in Go: panicking when accessing a nil map.  The `bug.go` file contains the erroneous code, while `bugSolution.go` shows the corrected version.

## Problem

In Go, attempting to access a map that hasn't been initialized (i.e., is `nil`) will result in a runtime panic.  This is because the program tries to dereference a null pointer.

## Solution

The solution involves checking if the map is `nil` before attempting to access it.  This can be done using the `if` statement or a conditional expression.

## Usage

1. Clone this repository.
2. Navigate to the repository's directory.
3. Run `go run bug.go` to see the panic.
4. Run `go run bugSolution.go` to see the corrected version.