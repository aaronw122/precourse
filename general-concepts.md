### What is the difference between synchronous and asynchronous processing?
- synchronous processing means operations block. the current call must finish before the next starts.
- asynchronous processing means operations don't block. you schedule work and continue. 
### What is a Promise in JS? 
- a promise is an object that represents the completion or failure of an async operation.
  - pending
  - fulfilled
  - rejected
### How are promises handled in JS?
- handled using: 
  - .then for fullfillment
  - .catch for rejection
  - .finally for cleanup
### How do other languages (go, python, etc) handle asynchronous function calls?
- go uses goroutines and channels. 
- python uses async/await with event loop. many others use future/promises or threads
### What is recursion? When would you use it?
- recursion takes a problem and breaks it down into smaller subproblems, calling itself inside definition.
- always has a base case(n = 1 or 0) and an inductive case(n > 1 or 0)
- 
- its fit for problems with natural recursive structure. trees, divide-and-conquer. efficeincy depends on memoization 

### What is the difference between parallel and concurrent processing?
- parallel: tasks run at the exact same time - i.e. multicore processor
- concurrent: two or more tasks start during overlapping time periods. multitasking on single-core machine

### What is an anonymous or lambda function? Why would you ever use this?
- anonymous or lambda is a compact function literal defined where its needed. 
  - i.e. arrow functions like x => x * 2; 
- you use them for concise inline callbacks for API's - map, filter, reduce.
- when you don't need to reuse anywhere else. 
- improve readability

### Why would you choose one language over another? Can you give an example scenario and trade off two languages?
- Choose languages based on problem fit: ecosystem, performance, developer speed, and team context.
- 


