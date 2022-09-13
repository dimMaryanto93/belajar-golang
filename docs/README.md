# How to install [Go](https://go.dev/doc/install)

Cara meng-install Go-Lang untuk Windows, Linux dan MacOs

## Install on MacOs

Untuk menginstall Go-Lang di MacOs basicly kita bisa menggunakan beberapa cara yaitu

1. Install from binary
2. Install from package manager
3. Install from source

Untuk saya sendiri lebih suka menggunakan package manager seperti [homebrew](https://formulae.brew.sh) dengan perintah berikut:

```bash
brew install go
```

Setelah itu saya biasanya membuat environment variables untuk menyimpan semua library seperti berikut:

```bash
mkdir -p .go/ && \
echo "export GOPATH=~/.go" >> ~/.zshrc
```

Kemudian kita coba test `go version`, jika outputnya seperti berikut maka sudah OK:

```bash
examples/go-programming [basic/installation●] » go version
go version go1.19.1 darwin/amd64
```