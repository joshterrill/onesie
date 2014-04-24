# onesie

a shell script that takes large files and minifies them into one-liners.

### Usage
```bash
onesie -i <input> -o <output>
```

#### Example
```bash
root@nullbox:~/$ onesie -i in.txt -o out.txt
root@nullbox:~/$ ls -lh
-rw-rw-r-- 1 root root 145K Apr 24 9:13 in.txt
-rw-rw-r-- 1 root root 124K Apr 24 9:13 out.txt
```
