# ztructurizr

A batteries-included (though currently incomplete) library for working
with the Structurizr DSL in ZIO applications.

## Getting it

```
    resolvers += "jitpack" at "https://jitpack.io"
```

```
	libraryDependencies += "com.github.caesarsdigital.ztructurizr" %% "ztructurizr-zworkspace" % "0.4.2"
```

## Examples

See the tests for examples of how to use the library.

You can run the examples from sbt with `zworkspace/test:runMain org.caesars.ztructurizr.ExampleRunner`.

## Related Projects

- [structurizr](https://github.com/structurizr): Java libraries (which we build on) for working with c4 models using the Structurizr DSL
- [c4-model](https://github.com/puffnfresh/c4-model): Haskell implementation of C4 model
