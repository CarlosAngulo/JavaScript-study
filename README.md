# JavaScript-study

## How does JavaScript work?

In the same way that any program, JavaScript does a couple of things:
- Allocate memory
- Parse and execute (read and runs)

Memory Heap
- When you declare variables and functions
- You can cause a memory leak

Call Stack
- When you execute the instructions, they are going to be stored in a stack (the last in store is the first one to be executed).
- You can cause a stack overflow with a recursion e.g

## Environment

  Javascript Engine
  - Memory Heap
  - Call Stack

  Ouside
  - Web API
    - DOM
    - AJAX (XMLHttpRequest)
    - Timeout
    - Fetch
  - Callback Queue
  - Event Loop

# Promises
A promise is an object that may produce a single value some time in the future, either a resolved value, or a reason that it's not resolved (rejected).

Maybe in one of three possible states: fulfilled, rejected or pending.
