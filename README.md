# php-code-style

## Control Structures

- Use brackets even for one line if statement blocks
- Opening bracket on same line, closing bracket on new line
```
if($abc) {
  echo "Hello world" . PHP_EOL;
}
```

- Statement contents go on separate lines. Only exceptions are ternery expressions.

 ``` 
 // BAD
 if($xyz) {runSomeCode()}
 ```
 
 ``` 
 // Good
 if($xyz) {
  runSomeCode();
 }
```

## Constants
```
define("SOME_CONSTANT_NAME", "my value");
```

## Variables
```
$someValueGoesHere = 5;
```


