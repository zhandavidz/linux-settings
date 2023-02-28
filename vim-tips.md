# Vim Tips

## Change Indentation

To change the indentation throughout a file, enter the following commands: ([source](https://stackoverflow.com/questions/16888658/change-2-space-indent-to-4-space-in-vim))

2 --> 4
```
set ts=2 sts=2 noet | retab! | set ts=4 sts=4 et | retab
```
4 --> 2
```
set ts=4 sts=4 noet | retab! | set ts=2 sts=2 et | retab
```
x --> y
```
set ts=x sts=x noet | retab! | set ts=y sts=y et | retab
```
