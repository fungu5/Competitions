Gotta brute force a flag.txt in an openme.zip

fcrackzip command
```
fcrackzip -b -v -u openme.zip -b -v -u
```

Dictionary command
```
fcrackzip -D -p /usr/share/wordlists/rockyou.txt -u openme.zip -v
```
password found: heavyrockmetal
open file and flag is there
