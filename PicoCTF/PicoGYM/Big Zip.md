<h3>Prompt</h3>
Unzip this archive and find the flag.

- [Download zip file](https://artifacts.picoctf.net/c/505/big-zip-files.zip)

<h3>Solution</h3>
- Using the find command can list out all the directories in the zip
- Using grep -r (recursive) will go through all subdirectories for the flag
```
find big-zip-files | grep -r pico
```
- picoCTF{gr3p_15_m4g1c_ef8790dc}