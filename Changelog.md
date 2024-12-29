build x64

windows
```sh

rustup target add x86_64-pc-windows-gnu

sudo apt install mingw-w64

cargo build --release --target x86_64-pc-windows-gnu

```

arm mac

```sh
rustup target add aarch64-apple-darwin

rustup toolchain install stable-aarch64-apple-darwin

cargo build --release --target aarch64-apple-darwin


```