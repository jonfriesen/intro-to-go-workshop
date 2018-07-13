# Installing Go

## Installation

#### Change Directory

    cd ${HOME}

### Install a binary distribution
 
#### Download the Windows binary

    https://golang.org/doc/install

## Setup the Workspace

### GOPATH

#### Edit

Set your GOPATH env variable and add the bin folder to your PATH

-

    SET GOPATH="<HOME DIR?>\go"
    SET PATH="\usr\local\go\bin,%GOPATH%\bin,%PATH%" // this might be wrong

### Workspace Directories

#### Create the directories on Unix

    mkdir -p %GOPATH%\src
    mkdir -p %GOPATH%\pkg
    mkdir -p %GOPATH%\bin
    mkdir -p %GOPATH%\src\github.com\%username%

### Check the Go Environment

    go env

-

	GOARCH="amd64"
	GOBIN=""
	GOCHAR="6"
	GOEXE=""
	GOHOSTARCH="amd64"
	GOHOSTOS="darwin"
	GOOS="darwin"
	GOPATH="/Users/kelseyhightower/go"
	GORACE=""
	GOROOT="/usr/local/go"
	GOTOOLDIR="/usr/local/go/pkg/tool/darwin_amd64"
	TERM="dumb"
	CC="clang"
	GOGCCFLAGS="-g -O2 -fPIC -m64 -pthread -fno-caret-diagnostics -Qunused-arguments -fno-common"
	CXX="clang++"
	CGO_ENABLED="1"
