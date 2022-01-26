## First line shout start with a shabag and the path to be used as a interpreter to execute the shell script.

```
#!/path/to/interpreter
```
  
#### Example: 
```
#!/bin/bash   OR    #!/bin/csh   OR   #!/bin/zsh
```

<br />
<br /> 

## Assigning variable
```
VARIABLE_NAME="Value"
```

#### Note: No space around = sing

<br />
<br />

## Using a variable

```
$VARIABLE_NAME   OR   ${VARIABLE_NAME}
```
<br />
<br />

## Assigning a command output to a variable 
```
VARIABLE_NAME=$(hostname)    # here "hostname" is the command to be executed.
```
<br />
<br />


## Tests

<br />

### If Conditions

```
if [ condition-is-true ]
then
    commands
elif [ contdition-is-true ]
then
    commands
else
    commands
fi
```

<br />

### For Loop

```
for VARIABLE_NAME IN ITEM_1 ITEM_N
do
    command 1
    command 2
    command N
done
```


## Positional Parameters: 

```
$0, $1, $2, ...  $9
$@
```
<br />
<br />

### Comments start with **#**

<br />

### Use **Read** command to accept input.
