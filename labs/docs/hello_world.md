# Hello World

#### Create

Linux/Mac

    mkdir ${GOPATH}/src/hello

Windows

    mkdir %GOPATH%\src\hello

#### Change Directory

Linux/Mac

    cd ${GOPATH}/src/hello

Windows

    cd %GOPATH%\src\hello

#### Edit

    main.go

-

	package main

	import (
		"fmt"
	)

	func main() {
		fmt.Println("Hello World")
	}

#### Build

    go build -o hello .

#### Run

    ./hello
