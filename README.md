# Comparison of Person

Person is a class which takes name and age as its parameter.

## Comparison criteria

* First, check if the name parameter of both objects is equal. If yes, then do the comparison according to age.
* If name is not equal then do the comparison based on name length.

## Commands

### Compile code

```bash
sbt compile
```
### Execute main class
Firstly, go to the root directory of the module where src and target folder is present and then run the below command:-

```bash
sbt run
```

### Delete all generated files

```bash
sbt clean
```

### Generate scalastyle config file

```bash
sbt scalastyleGenerateConfig
```

### Execute scalastyle plugin

```bash
sbt scalastyle
```