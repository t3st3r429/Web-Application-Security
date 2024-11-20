# Basic 2

## Challenge Text

> A slightly more difficult challenge, involving an incomplete password script. Requirements: Common sense. 

> Level 2

> Network Security Sam set up a password protection script. He made it load the real password from an unencrypted text file and compare it to the password the user enters. However, he neglected to upload the password file...

---

## Writeup

The challenge description tells us that the password protection script compares the password from a text file to the input provided. But since the text file wasn’t uploaded, the script is actually comparing nothing to the password we provide. So, if we submit an empty password and hit the submit button, we’ll solve the challenge, because comparing nothing to nothing results in true.
