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