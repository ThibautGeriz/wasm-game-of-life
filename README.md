# Game of life

Create a game of life in wasm following [this tutorial](https://rustwasm.github.io/book/game-of-life/introduction.html)

## Requirements

[Install RUST](https://www.rust-lang.org/en-US/install.html):
[Install Node](https://nodejs.org/en/download/)
[Install wasm-pack](https://rustwasm.github.io/wasm-pack/installer/)

```bash
curl https://sh.rustup.rs -sSf | sh
rustup component add clippy # install linter
rustup component add rustfmt # install formatter
curl https://rustwasm.github.io/wasm-pack/installer/init.sh -sSf | sh
brew install node
```

## Commands

```bash
wasm-pack build # build
wasm-pack build --release # build for release
cargo test # run the tests
wasm-pack test --firefox --headless # run brower tests
cargo fmt # format the code
cargo clippy # run the linter
cd www; npm run serve # run the local HTTP server
cd www; npm run build # build the site
```
