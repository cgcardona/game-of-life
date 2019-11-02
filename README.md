# Conway's Game of Life

This is a demo app of Conway's Game of Life written in Rust and running as a web app in the browser via wasm and web assembly.

## Setup

Install [wasm-pack](https://rustwasm.github.io/wasm-pack/book/)

```
curl https://rustwasm.github.io/wasm-pack/installer/init.sh -sSf | sh
```

Install [cargo-generate](https://github.com/ashleygwilliams/cargo-generate)

```
cargo install cargo-generate
```

## Installation

First clone the repo

```
git clone https://github.com/cgcardona/game-of-life.git
```

Next change directories

```
cd game-of-life
```

Now build the app and deps

```
cargo build
```

Build web assets

```
wasm-pack build
```

Change directories, install web deps and run the app

```
cd www
npm install
npm run start
```

Open the browser to [http://localhost:8080/](http://localhost:8080/) and have your mind blown!

[Example gif](https://i.imgur.com/94uQuHT.mp4)
