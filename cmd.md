### Show the size of derectory

```
du -sh ./
```

### Verify the file existence

```
test -f PATH TO FILE
```

### Verify the directory existence

```
test -d PATH TO DIR
```


### Verify the file existence and echo the result(Boolean value)

```
test -f PATH TO FILE && echo 'TRUE' || echo 'FALSE'
```

### Verify the directory existence andecho the result(Boolean value)

```
test -d PATH TO DIR && echo 'TRUE' || echo 'FALSE'
```
### Find the file (directory) permission

```
stat PATH -c '%a'

644
```

### Find the file name which has specified word

```
grep -ril "SOMETHING WORD" [dir]


    ex.) grep -ril "foo" .

```


### Find the file name which has specified word and output results to a file.

```
grep -ril "SOMETHING WORD" [DIR] > [FILE]


ex.) grep -ril "foo" . > hogehoge.txt

```

### Output results to a file. (Overwrite mode)

```
[something cmd] > [FILE]



echo Hello World! > foo.txt

cat foo.txt

Hello World!


echo Oh shit! > foo.txt

cat foo.txt

Oh shit!

```
