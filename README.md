# WASM in Java with GraalVM

this a reduced version of [polyglot-embedding-demo](https://github.com/graalvm/polyglot-embedding-demo) focused on WASM.

## Build and run

```shell
mvn package -DskipTests
mvn exec-exec
```

It returns

```shell
Initializing wasm
Available members are: [factorial.wasm]
wasm: factorial(20) = 2432902008176640000
```