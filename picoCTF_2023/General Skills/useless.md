# useless

Author: LOIC SHEMA<br>
Points: 100

## Description
There's an interesting script in the user's home directory
The work computer is running SSH. We've been given a script which performs some basic calculations, explore the script and find a flag.

## Tags
picoCTF 2023, General Skills, man

## Hints
1. None

## Approach
1. SSH into the instance provided

```bash
ssh picoplayer@saturn.picoctf.net -p <port number>
```

2. Check out the contents of the script
```bash
cat useless
```

3. Since the tag includes `man`, run `man useless` to see the manual for the script.

## Flag
picoCTF{us3l3ss_ch4ll3ng3_3xpl0it3d_3555}