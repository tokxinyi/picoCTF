# repetitions

Author: THEONESTE BYAGUTANGAZA<br>
Points: 100

## Description
Can you make sense of this file?
Download the file [here](https://artifacts.picoctf.net/c/473/enc_flag).

## Tags
picoCTF 2023, General Skills, base64

## Hints
1. Multiple decoding is always good.

## Approach
1. We use the `base64` command available in the webshell to decode the file multiple times.
2. We can output the decoded message to a file so we can decode the output file

```bash
# first decode
base64 --decode /path/to/file > output.txt

# subsequent decode
base64 --decode output.txt > output1.txt
```

## Flag
picoCTF{base64_n3st3d_dic0d!n8_d0wnl04d3d_dfe803c6}