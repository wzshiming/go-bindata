## bindata

This package converts any file into managable Go source code. Useful for
embedding binary data into a go program. The file data is optionally gzip
compressed before being converted to a raw byte slice.

It comes with a command line tool in the `go-bindata` sub directory.
This tool offers a set of command line options, used to customize the
output being generated.


### Installation

To install the library and command line program, use the following:

	go get -u github.com/wzshiming/go-bindata/cmd/...


