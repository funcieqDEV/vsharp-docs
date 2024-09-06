# `set name = <expr>`

## Description
we use `set` for declaring local and global variables, we can then use the declared variables in `<expr>`

## Syntax
```plaintext
set name = <expr>
```

## Simple example
```plaintext
set x = 15.1
```

## Changing value of existing variable
```plaintext
set x = "hello, world"
println(x)
set x = x + " my name is ..."
println(x)
```

**Output:**<br>
```plaintext
hello, world
hello, world my name is ...
```

*as you can see, changing the value of an existing variable is done in the same way as its declaration, <br>except that it can still use its current value *