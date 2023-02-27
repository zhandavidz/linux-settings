# Vim Tips

## Change Indentation

To change the indentation throughout a file, enter the following commands:

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
