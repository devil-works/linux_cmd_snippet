### Show the size of derectory

```
du -sh ./
```

### Verifying the file existence

```
test -f PATH TO FILE
```

### Verifying the directory existence

```
test -d PATH TO DIR
```


### Verifying the file existence and echo the result(Boolean value)

```
test -f PATH TO FILE && echo 'TRUE' || echo 'FALSE'
```

### Verifying the directory existence andecho the result(Boolean value)

```
test -d PATH TO DIR && echo 'TRUE' || echo 'FALSE'
```
### Finding the file (directory) permission

```
stat PATH -c '%a'

644
```


