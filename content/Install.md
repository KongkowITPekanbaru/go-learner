# [Install On Linux](#example)
# Install In Windows
----
## How to Install Go in Linux Mint 19.1 or ubuntu 18.04
source : [here](https://golang.org/doc/install#install)

## example

### Download GO Binary
`https://golang.org/dl/`

### create folder go on `/usr/local/` and extract downloaded Go in /usr/local/ 
`sudo tar -C /usr/local -xzf go1.12.6.linux-amd64.tar.gz`

### edit your `.bashrc` and add this
```
export GOROOT=/usr/local/go
export GOPATH=$HOME/go
export PATH="$PATH:$GOPATH/bin:$GOROOT/bin:$PATH"
```

### check your go Installation 
`go version` 

### and check your go env
`go env`
