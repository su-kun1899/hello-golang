# hello-golang
My first golang

## Install

`brew install go`

## Edit bash_profile

```
export GOPATH=$HOME/go
export PATH=$PATH:$GOPATH/bin
```

## Create workspace

```
mkdir $HOME/go
mkdir -p $GOPATH/src/github.com/su-kun1899
```

## Get Started

```
cd $GOPATH/src/github.com/su-kun1899
git clone git@github.com:su-kun1899/hello-golang.git
```

```
cd $GOPATH/src/github.com/su-kun1899/hello-golang
go install
hello-golang
```
