# Chrono
Author: MUBARAK MIKAIL<br>
Points: 100

## Description
How to automate tasks to run at intervals on linux servers?
Additional details will be available after launching your challenge instance.

## Tags
picoCTF 2023, General Skills, Linux

## Hints
None

## Approach
1. SSH into the provided server and enter the provided password

```bash
ssh picoplayer@saturn.picoctf.net -p 63393
```

2. Go to the root directory `cd /` and list the directory `ls -l`
3. Change directory to the challenge folder `cd challenge`
4. Display the content of the file and you will find the flag.

## Flag
picoCTF{Sch3DUL7NG_T45K3_L1NUX_1b4d8744}