# VNC Library for Go (FIX THIS SHIT VERSION)
```
const maxNameLength = 1024 * 1024 // 1 MB
if nameLength > maxNameLength {
		return fmt.Errorf("name length %d exceeds maximum allowed length %d", nameLength, maxNameLength)
}
```

## Usage & Installation

The library is installable via standard `go get`. The package name is `vnc`.

```
$ go get github.com/nor1su/go-vnc
```

Documentation is available on GoDoc: http://godoc.org/github.com/mitchellh/go-vnc
