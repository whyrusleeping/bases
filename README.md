# bases
A tool for converting data between different encodings

## Installation
```
go get github.com/whyrusleeping/bases
```

## Usage
```
$ printf hello | bases bin hex
68656c6c6f
$ printf "ff2c3ed5" | bases hex base64
/yw+3w
```

The first argument is the input format, the second argument is the output format.
Supported formats are currently:

- hex
- base64
- base32
- base58
- bin 

## License
MIT
