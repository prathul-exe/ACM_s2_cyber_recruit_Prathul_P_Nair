# Bahubali  

## Challenge Description
Was give a picture which contained the flag.A hint was also given to use command to view and analyze binary files in hexadecimal format

## Analysis / Approach
At first I observed the image to find any visual flags.I found two texts which where
- Bahubali 2
- War post look development
- Vishwanath Sundaram
Since already the hint was given I directly analysed the binary files into hexadecimal format and got a flag.
To verify the flag I used 3 commands and got the same flag "JAI MAHISMATHI"

## Bash Commands Used
- strings image.jpg
- hexdump -C image.jpg
- xxd image.jpp
## Flag
flag{jai_mahismathi}