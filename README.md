# VNC Library for Go (FIX THIS SHIT VERSION)
```
const maxNameLength = 1024 * 1024 // 1 MB
if nameLength > maxNameLength {
		return fmt.Errorf("name length %d exceeds maximum allowed length %d", nameLength, maxNameLength)
}
```
go-vnc is a VNC library for Go, initially supporting VNC clients but
with the goal of eventually implementing a VNC server.

This library implements [RFC 6143](http://tools.ietf.org/html/rfc6143).

## Usage & Installation

The library is installable via standard `go get`. The package name is `vnc`.

```
$ go get github.com/mitchellh/go-vnc
```

Documentation is available on GoDoc: http://godoc.org/github.com/mitchellh/go-vnc
