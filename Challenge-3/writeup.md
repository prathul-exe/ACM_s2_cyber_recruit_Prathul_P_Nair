# HTML and its birth

## Challenge Description
Give Two .txt files one contains descriptiona and another file that was recognized as an .html file

## Analysis / Approach
At first I recognised the gib=ven file as an .html file hence renamed it as find_right_flag.html and opened it in my browser intending to find some kind of information and I foundout that there wae a Base64 fragment hidden in one of them.I first found the base64 fragments and decoded them using bash commands and found a flag in the base64 fragment **"VGhpcy1JU1QtUEFSVEE="**.It was found to be "TIM BERNERS LEE"(Person who found out world wide web-www)

## Bash Commands Used
- echo "base64 fragment" | base64 --decode

## Flag
flag{TIM_BERNERS-LEE}