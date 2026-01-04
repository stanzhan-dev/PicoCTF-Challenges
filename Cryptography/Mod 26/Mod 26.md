# Mod 26 (Easy)
- [Challenge information](#challenge-information)
- [Solution](#solution)
- [References](#references)

## Challenge information
```
Challenge Link: https://play.picoctf.org/practice/challenge/144?category=2&difficulty=1&page=1
Challenge Description: Cryptography can be easy, do you know what ROT13 is? cvpbPGS{arkg_gvzr_V'yy_gel_2_ebhaqf_bs_ebg13_45559noq}
```

## Solution
Fairly easy challenge, you can do it manually or use an online tool. Essentially ROT13 substitution cipher meaning each letter is replaced by the letter 13 positions after it in the alphabet.

So decrypting it will land us the plaintext:
```
cvpbPGS{arkg_gvzr_V'yy_gel_2_ebhaqf_bs_ebg13_45559noq} --> picoCTF{next_time_I'll_try_2_rounds_of_rot13_45559abd}
```

## References
- [ROT13 Decipher](https://rot13.com/)
- [ROT13](https://en.wikipedia.org/wiki/ROT13)
- [ROT 13 CTF](https://github.com/stanzhan-dev/PicoCTF-Challenges/blob/main/Cryptography/ROT13/13.md)
