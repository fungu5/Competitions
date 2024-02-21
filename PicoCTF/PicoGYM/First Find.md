<h3>Prompt</h3>
Unzip this archive and find the file named 'uber-secret.txt'

- [Download zip file](https://artifacts.picoctf.net/c/501/files.zip)

<h3>Solution</h3>
- Using find command led me to secret directories and text.file
```
find files
```
![[Pasted image 20240217160154.png]]
- cd to secret text file and cat the uber-secret.txt to find flag
- picoCTF{f1nd_15_f457_ab443fd1}