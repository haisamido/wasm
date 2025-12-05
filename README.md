# Web Assembly: wasm

Inspired by https://www.youtube.com/watch?v=JFzpd1-6a3E 

## 1:

```bash
make install-taskfile

```

## 2

```bash
task

```

yields

```bash
task: Available tasks for this project:
* default:                 Shows this help message
* compile:emcc:html:       Compile C to WebAssembly using Emscripten (HTML)
* compile:emcc:js:         Compile C to WebAssembly using Emscripten (JS)
* compile:gcc:             Compile C to WebAssembly using GCC
* docker:build:            Build Docker image with GCC
* docker:down:             Bring down Docker container
* docker:up:               Bring up Docker container
* run:local:               run the generated HTML file in the default web browser
```

## 3

```bash
task docker:up

```

## 4

```bash
open http://localhost:6931/helloword.html

```