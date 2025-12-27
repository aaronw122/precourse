### What is data?
data is the representation of information in a form a computer can process. 
can be objects, arrays, strings, images, etc. 


### What is an algorithm?
an algorithm is any series of steps/recipe that does a job for you. transforms inputs into outputs to solve pronlem
this can be solving a rubiks cube, writing a computer program, etc. 


### What is a function?
series of instructions that does a job for you. 
an operation that takes inputs, and returns an output.

### What is function scope? What is a block scope? What is global scope?
1. function scope is the idea that any variables defined inside function will only exist inside function and cannot be referenced outside of it. 
2. block scope is created by any statement block - if/else, forwhile, etc. this means any variables declared by let or const inside these are not accesible outside. 
3. global scope is any variable that is declared in a file outside of a function. this means it can be used or referenced anywhere in the file. 
### What is a variable?
1. a data representation that points to a value and is saved on the machine
2. can be string, num, etc. all 7 primitives are variables. 

### What is a data type?
the different ways to represent data + permitted operations. 
- string
- number
- boolean
- big int
- object
- undefined
- null
### What is a data structure? What are some examples?
- the layout or representation of data being used. 
- hash tables
- can be an array of objects with restaurant reviews. 
  - properties name, comment, score
- could be an object storing votes from a presidential eleciton. 
- etc

### What is a web server?
- a web server is a backend application that the client requests with HTTP to get, create, update, delete data
- it ensures the data is consistent across multiple clients, and enables clients to update it synchronously.  

### What is an operator?
- an operator is a symbol used to express some relatinship or statement. 
- examples include
  - ternaray, &&, ||

### What is a character? A string?
- a character is one peice of a string.
- a string is any value stored as written, can contain numbers, letters and symbols. 
- cannot add values in the traditional sense with strings. 

### What is state? Why is it important?
- state is the current values that determine a systems behavior. 
- it is important because it update the UI realtime if a value on the DOM changes. 

### What is an interface?
- an interface is the part of a website that a user sees and interacts with. 
- 

### What is an API?
a contract you call that takes some inputs, and spits out an output. 
often times you don't know how it works, only what it does. can be internal or external APIs.

### What are calculations (e.g. “pure functions”)?
given the same input, it always returns the same output. 
it produces no side effects. 

you want to avoid shared state - pure function.

### what are side effects
1. when the function changes a non-local state or when its output is non-deterministic. 

### impure function
1. if it relies on time of day, random numbers. 
2. anything that depneds on i/o - user input, disk access



### redux
get a store, reducer responsible for updating state. 
action objects get passed into reducers, explaining changes we want. 

all reducer must be **pure functions** you cannot fire a network request inside a reducer. 