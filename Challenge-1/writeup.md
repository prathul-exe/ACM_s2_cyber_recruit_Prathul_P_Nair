# Ossuary Architecture

## Challenge Description
An anonymous investigator recovered a photograph from an old archive linked to ritualistic crimes. The image shows
architecture constructed entirely from human remains.

The photograph contains:
- Chandeliers made of bones
- Skulls arranged symmetrically
- Gothic vaulting

No metadata, timestamps, coordinates, or filename clues were available.

A quote was found along with the image:

"Let conversation cease. Let laughter flee.
This is the place where death delights in helping the living."

The task was to identify the exact location where the photograph was taken.

## Analysis / Approach
At first I observed the image to find any visual flags.Then since I found nothing I started going deeper into the image to 
find any encrpted hidden message by using linux bash commands,but I coudnt find any.Then I analysed the given text file and read the quote.I rember reading this quote in one of the films I watched.The quote is usually found in places like where the cadaver is being studied.Since the image is too artistic to be kept in a disection hall I quickly realised this would be in a museum.I linked all the 3 given clues with the quote and was sucessfully able to find the intersecting point between the clues.I also reverse searched the image for the confirmation of the answer and I finally came to the conclusion that the following image was taken from "SEDLEC OSSUARY" also known as church of bones which is present in the city KUTNA HORA in Czech Republic

## Tools 
- Open-source research (OSINT)
- Historical reference comparison
- Image-to-landmark correlation

## Bash Commands Used
- file evidence.jpeg
- exiftool -a -u -g1 evidence.jpeg
- binwalk evidence.jpeg
- zsteg -a evidence.jpeg

## Flag
flag{sedlec_ossuary_kutna_hora}