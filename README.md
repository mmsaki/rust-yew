# rust-yew

## Requirements

1. Make sure you have install [rust](https://www.rust-lang.org/tools/install)
1. Update rustc to latest version e.g for macos
    ```sh
    rustup default stable-x86_64-apple-darwin
    ```

1. Install `trunk` 
    ```sh
    cargo install --locked trunk
    ```

1. Install `wasm-bindgen-cli`
    ```sh
    cargo install --locked wasm-bindgen-cli
    ```

1. Install WebAssembly target
    ```sh
    rustup target add wasm32-unknown-unknown
    ```

## Getting started

1. Edit the app in [src/app.rs](./src/app.rs)
1. Run the app:

    ```sh
    trunk serve --open
    ```
> The app will run on 127.0.0.1/8080/
