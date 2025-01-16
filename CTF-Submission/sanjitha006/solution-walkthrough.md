<h1>SOLUTON WALKTHROUGH:</h1>
<p>Start by using the p,q,d, and e values given to decrypt the flag. 
However, if you tried to do so, you must have found that the 'n' is not equal to p*q, which it is supposed to be.<br>
So, what values in private_key are wrong?<br>
Try using the qr-data and apply <br>
xor with the given n to get a number that you will find is a prime and equal to p*q.<br>
Thus, it can be a candidate for n.<br>
So try decrypting with this set of values(replacing the n value) to get a meaningful flag.
</p>
<br>
FLAG{YOU_DID}
