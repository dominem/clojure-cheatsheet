# clojure-cheatsheet

### Create a new Clojure project

```bash
lein new app project-name
```

### Run the project

```bash
lein run
```

### Build a standalone Clojure project

Build a standalone file that you can execute with Java.

```bash
lein uberjar
```

This command creates a file `target/uberjar/project-name-0.1.0-SNAPSHOT-standalone.jar`

### Run the standalone file built from a Clojure project

```bash
java -jar target/uberjar/project-name-0.1.0-SNAPSHOT-standalone.jar
```

### Run REPL

```bash
lein repl
```

### Built-in functions

#### Add

```clojure
(+ 1 2 3)
; => 6
```

#### Subtract

```clojure
(- 32 2)
; => 30
```

#### Divide

```clojure
(/ 8 3)
; => 8/3
```

#### Multiply

```clojure
(* 9 -4)
; => -36
```

#### Return first item in the collection

```clojure
(first [3 6 9])
; => 3
```

### Concatenate strings

```clojure
(str "abc" "QWE" "123")
; => "abcQWE123"
```
