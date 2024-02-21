<h3>Prompt</h3>
Sometimes you need to handle process data outside of a file. Can you find a way to keep the output from this program and search for the flag? Connect to `jupiter.challenges.picoctf.org 7480`

<h3>Solution</h3>
- Using nc command connecting to the program gives you a long list of sentences
- Piping the connection into grep allows us to search for the flag
```
nc jupiter.challenges.picoctf.org 7480 | grep pico
```
- picoCTF{digital_plumb3r_06e9d954}