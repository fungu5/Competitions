<h3> Buffer Overflow </h3>
<b>Background:</b>
-Buffer overflows are memory exploits typically found with C/C++ based language. Abusing the memory leak found with changing your player's name, use ASCII id to gain items coins
![[Pasted image 20231219171915.png]]

![[Pasted image 20231219171934.png]]

Question:
-If the coins variable had the in-memory value in the image below, how many coins would you have in the game? Answer: 1397772111
![[Pasted image 20231219172024.png]]
	1. Put '53504f4f' in hex to demical convertor https://www.rapidtables.com/convert/number/hex-to-decimal.html 

-What is the value of the final flag? Answer: THM{mchoneybell_is_the_real_star}