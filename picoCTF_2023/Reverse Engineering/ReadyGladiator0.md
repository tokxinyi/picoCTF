# Ready Gladiator 0 

Author: LT 'SYREAL' JONES<br>
Points: 100

## Description
Can you make a CoreWars warrior that always loses, no ties?
Additional details will be available after launching your challenge instance.

After launching the challenge instance:

Can you make a CoreWars warrior that always loses, no ties?
Your opponent is the Imp. The source is available here. If you wanted to pit the Imp against himself, you could download the Imp and connect to the CoreWars server like this:
`nc saturn.picoctf.net 57174 < imp.red`

## Tags
picoCTF 2023, Reverse Engineering, CoreWars

## Hints
None

## Approach
1. Download the file provided and check the contents.
    - Looks like it will have a value of (0,1)

2. Run `nc saturn.picoctf.net 57174` and make sure that the warrior will have a value larger than (0,1).

## Flag
picoCTF{h3r0_t0_z3r0_4m1r1gh7_7c030e56}