# Makefile Note

## some useful websites

1. [makefiletutorial](https://makefiletutorial.com)

## basic syntax

1. Makefile looks like this:

```makefile
target1: prerequisites
    command 1
    command 2
    command 3

target1: prerequisites
    command 1
    command 2
    command 3
```

2. There is a <tab> before each command.
3. 'clean' is usually used as a target for clean the output of other targets. use **make clean**
4. If there are multiple targes need to run. Make an **all** target and list all other targets you wanna run.
