# Setup

```
$ brew install forego
$ brew install dynamodb-local
```

Confirm that `dynamodb-local` should work:

```
$ dynamodb-local
$ open http://localhost:8000/shell/
$ [Ctrl-C]
```

# Running

```
$ sbt assembly
$ forego start
```

# Development

```
sbt> ~re-start --- -Dconfig.resource=/frontend.conf
```
