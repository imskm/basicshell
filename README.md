# Shell Scripting

* Outputing to stdout
This will output the text followed by new line
```
echo <Text>
```

This will not output new line at the end
```
echo -n <Text>
```

Output some text with spaces
```
echo -n "<Text goes here>"
```

* **Variable in shell scripting**
variable name should not contain any spaces
allowed chars in variable name are letter, underscore, and digit
while assigning value in variable, don't give space around `=` operator

String variable
```
myvar="this is a string"
```

Int variable
```
ivar=20
```

Double variable
```
dvar=20.505
```

Using variable: use `$` sign before variable name
```
a=10
echo $a
```


* **Reading from stdin**
```
read "Prompt"
```

* **Arithmetic operations**
* Basic arithmetic operation
```
`expr 2 + 4`
`expr 2 - 4`
`expr 2 \* 4`
`expr 4 / 2`
`expr 12 % 4`   # % (modulo operator) = finds remainder
`expr a=4`      # = (assignment)

```

* Arithmetic operation with variable
```
a=20
b=10
ans=`expr $a + $b`
```
