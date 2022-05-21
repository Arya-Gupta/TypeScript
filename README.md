## About <a href="https://www.typescriptlang.org/docs/">TypeScript</a>

TypeScript is an open source language and is a superset of JavaScript

- Offers additional features to JavaScript including static types
- Using types is completely optional
- Compiles down to regular JS
- Can be used for frontend JS as well as backend with Node.js
- Includes most features from ES6, ES7 (classes, arrow functions, etc)
- Types from 3rd party libraries can be added with type definitions

## Dynamic vs Static Typing

In dynamically typed languages, the types are associated with run-time values and not named explicitly in your code
In statically typed languages, you explicitly assign types to variables, function parameters, return values, etc <br/>
Static examples - Java, C, C++, Rust, Go <br/>
Dynamic examples - JavaScript, Python, Ruby, PHP <br/>

## Pros and Cons

Pros:
- More robust
- Easily spot bugs
- Readability
- Popular

Cons:
- More code to write
- More to learn
- Required compilation
- Not true static typing 

## Compiling TypeScript

- TypeScript uses .ts and .tsx extensions
- TSC(TypeScript Compiler) is used to compile .ts files down to JS
- Can watch files and report errors at compile time
- Many tools include TS compilation by default
- Most IDEs have great support for TS
- The tsconfig.json file is used to configure how TypeScript works
