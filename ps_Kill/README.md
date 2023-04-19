# All about Ps & Kill Command

### how to run back ground process
```
sh test.sh &
```

### show all current process
```
ps
```

### Show all background process details with process id  and Parent process id 
```
ps -f
```

### Show all process details

```
ps -e
```

### Show all background process details

```
ps -ef
```

### Show all background process details (Hierarchical nature)

```
ps -H
```

### Show all background process details (Hierarchical nature)
```
ps -F -H
```

### Show all background process details (Hierarchical nature)
```
ps -f -H
```

### show process deatils with colouring (Using Grep command)

```
ps -f | grep 'test.sh'
```

### Kill command (PID = 2002)
```
kill 2002
```

### Multiple Process Kill 
```
kill -9 2002,2004,2006
```

