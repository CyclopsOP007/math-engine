# math-engine
A math engine built from scratch in C++ that solves equations step by step and explains each step in plain English. No external AI libraries used - the tokenizer,parser,solver and neural network explainer are all hand-built.

## What it does

- Takes a math expression or equation as input (e.g. 3x+6=0)
- Solves it step by step
- Explains each step in plain English using a small neural network
- Runs in the browser via WebAssembly

## Tech

- **Language:** C++
- **FrontEnd:** Vanilla HTML / CSS / JS
- **Deployment:** WebAssembly via Emscripten
- **No external AI libraries**

## Project Phases

- Tokenizer
- Parser
- Solver Engine
- Neural Network Explainer
- C++ Web Bridge (WASM)
- Frontend
