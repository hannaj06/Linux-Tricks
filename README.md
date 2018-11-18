### number of lines in a file or directory:

```
wc -l <file_name>

wc -l *
```


###available disk space:

```
df -h
````

###combining files

```
cat file_a.txt file_b.txt file_c.txt > merged.txt
```

###combining multi part s3 files:

```
cat <file_name_prexfix>*_part.txt >merged_file
```

