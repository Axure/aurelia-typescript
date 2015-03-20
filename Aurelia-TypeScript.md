# Aurelia-TypeScript

## Table of Contents

1. [TODO](https://github.com/cmichaelgraham/aurelia-typescript/blob/master/Aurelia-TypeScript.md#todo)
2. [Coverage](https://github.com/cmichaelgraham/aurelia-typescript/blob/master/Aurelia-TypeScript.md#coverage)
  1. [aurelia-dependency-injection](https://github.com/cmichaelgraham/aurelia-typescript/blob/master/Aurelia-TypeScript.md#dependency-injection)
  2. [aurelia-router](https://github.com/cmichaelgraham/aurelia-typescript/blob/master/Aurelia-TypeScript.md#router)
  3. [Behaviors (Decorators)]()
  4. [aurelia-http-client]()
  5. [aurelia-metadata](https://github.com/cmichaelgraham/aurelia-typescript/blob/master/Aurelia-TypeScript.md#Metadata)
  6. [aurelia-framework]()
3. [Plan]()
  1. `.d.ts` files
  2. `aurelia-framework.d.ts` file
  3. `aurelia.d.ts` file
  4. code comments (class, method, parameter type info)
4. [Issues]()
  1. Tooling and Explicit References

## TODO

1. :white_check_mark: Pull Request for [exception in TODO sample](https://github.com/aurelia/templating/issues/34)
1. Create Aurelia TypeScript Plan
2. Document Current Coverage
3. Document Missing Coverage in DI, Router, Behaviors (Decorators), and HTTP Client
4. Create `.d.ts` files
5. Create `aurelia-framework.d.ts` aggregator
6. Create `aurelia.d.ts` aggregator

## Coverage

### Dependency-Injection

| Class | Member | .d.ts | unit test | sample | working | deployed |
| --- | :---: | :---: | :---: | :---: | :---: | :---: |
| container | get | :memo: | :memo: | :memo: | :memo: | :memo: |
|  | registerSingleton | :memo: | :memo: | :memo: | :memo: | :memo: |
|  | registerTransient | :memo: | :memo: | :memo: | :memo: | :memo: |
|  | registerInstance | :memo: | :memo: | :memo: | :memo: | :memo: |
|  | registerHandler | :memo: | :memo: | :memo: | :memo: | :memo: |
|  | supportAtScript | :memo: | :memo: | :memo: | :memo: | :memo: |
|  | createChild | :memo: | :memo: | :memo: | :memo: | :memo: |
| Transient |  | :white_check_mark: | :memo: | :memo: | :memo: | :memo: |
| Singleton |  | :memo: | :memo: | :memo: | :memo: | :memo: |
| Resolver | base | :heavy_multiplication_x: | :heavy_multiplication_x: | :heavy_multiplication_x: | :heavy_multiplication_x: | :heavy_multiplication_x: |
| Lazy | constructor | :memo: | :memo: | :memo: | :memo: | :memo: |
|  | static of | :memo: | :memo: | :memo: | :memo: | :memo: |
| All | constructor | :memo: | :memo: | :memo: | :memo: | :memo: |
|  | static of | :memo: | :memo: | :memo: | :memo: | :memo: |
| Optional | constructor | :memo: | :memo: | :memo: | :memo: | :memo: |
|  | static of | :memo: | :memo: | :memo: | :memo: | :memo: |
| Parent | constructor | :memo: | :memo: | :memo: | :memo: | :memo: |
|  | get | :memo: | :memo: | :memo: | :memo: | :memo: |
|  | static of | :memo: | :memo: | :memo: | :memo: | :memo: |

### Router

### Behaviors

### Decorators

## Plan

### `.d.ts` files
1. `<lib>.d.ts` in each repo
2. `aurelia.d.ts` aggregate of each repo

## Issues

### Tooling and Explicit References
