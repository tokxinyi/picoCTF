# Permissions

Author: GEOFFREY NJOGU<br>
Points: 100

## Description
Can you read files in the root file?
Additional details will be available after launching your challenge instance.

## Tags
picoCTF 2023, General Skills, vim

## Hints
None

## Approach
1. SSH into the machine provided and login with the provided password
```bash
ssh -p 57541 picoplayer@saturn.picoctf.net
```
2. Change directory to `/challenge` and check the contents of the json file using either `vim` or `cat`.

## Flag
picoCTF{uS1ng_v1m_3dit0r_1cee9dcb}