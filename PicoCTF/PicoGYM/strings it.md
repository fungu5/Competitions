<h3>Prompt</h3>
Can you find the flag in [file](https://jupiter.challenges.picoctf.org/static/5bd86036f013ac3b9c958499adf3e2e2/strings) without running it?

<h3>Solution</h3>
- The strings command creates a list of strings from the text file
- Grep helps us search for the flag
```
strings strings | grep pico
```
- picoCTF{5tRIng5_1T_827aee91}