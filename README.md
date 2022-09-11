# gcad-webview

This package provides the underlying webview for the VSCode extension gcad-extension's toolpath preview functionality.  It's written in Rust and compiled to WebAssembly.


## Building (Development)

During development, `npm start` will build the Rust code and start a local webserver with some test gcad fed into it.


## Building (Packaging)

`wasm-pack build` will build the Rust code and package it up for publishing to npm.
`wasm-pack publish` will publish the package to npm.

