<h3>Prompt</h3>
In RSA, a small `e` value can be problematic, but what about `N`? Can you decrypt this? [values](https://mercury.picoctf.net/static/12d820e355a7775a2c9129b2622a7eb6/values)

<h3>Solution</h3>
- The file gives us a c, n, and e value
- Looking at google for a couple rsa crackers ended up on this one https://www.dcode.fr/rsa-cipher
- Plugging in C, E, and N gives us the flag
- picoCTF{sma11_N_n0_g0od_00264570}