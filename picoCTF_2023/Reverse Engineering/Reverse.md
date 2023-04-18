# Reverse

Author: MUBARAK MIKAIL<br>
Points: 100

## Description
Try reversing this file? Can ya?
I forgot the password to this file. Please find it for me?

## Tags
picoCTF 2023, Reverse Engineering

## Hints
None

## Approach
1. Change the permissions of the file to allow us to execute the script

```bash
chmod 754 ret
```
2. Execute the script and it will prompt for a password
3. Googled `decompile executable file in linux` and found this [link](https://www.codementor.io/@packt/reverse-engineering-a-linux-executable-hello-world-rjceryk5d)
4. Check the file type `file <filename>`
5. Use strings to get all the human-readable strings in a binary executable file
6. The output contains the flag needed

## Flag
picoCTF{3lf_r3v3r5ing_succe55ful_fa9cb3b1}