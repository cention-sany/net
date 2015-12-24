# textproto [![GoDoc](https://godoc.org/github.com/cention-sany/net/textproto?status.png)](https://godoc.org/github.com/cention-sany/net/textproto)
Forked version of Go stdlib net/textproto.
This version allows ReadMIMEHeader read all data before return error (previously it return right after encounter any error).
It also return any useful readable data even encountered error.
