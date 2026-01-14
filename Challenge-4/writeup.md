# Chand Baori

## Challenge Description
An image from a pre-2005 archaeological dataset shows a stone structure outdoors that casts no clear shadow. The image contains repeating stone stair geometry, with no people, water, sky, or inscriptions.

hint:

“Built to defeat heat, not enemies."

## Analysis / Approach
At first I observed the image to find any visual flags.Then since I found nothing I started going deeper into the image to find any encrpted hidden message by using linux bash commands,but I coudnt find any even after multiple attepts i used the command steginfo but failed to get the password.So I matched the given clues and got a name to confirm it I reverse searched the image and I got it as "Chand Baori" in Rajasthan.

## Tools 
- Open-source research (OSINT)
- Historical reference comparison
- Image-to-landmark correlation

## Bash Commands Used
- file image.jpeg
- exiftool image.jpeg
- binwalk image.jpeg
- jpeginfo -c image.jpeg
- steghide info image.jpeg
- steghide extract -sf image.jpeg
## Flag
flag{chand_baori|rajasthan}