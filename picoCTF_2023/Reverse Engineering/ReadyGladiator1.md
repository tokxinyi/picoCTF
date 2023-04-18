# Ready Gladiator 1
Author: LT 'SYREAL' JONES
Points: 200

# Tags
picoCTF2023, Reverse Engineering, CoreWars

# Description
Can you make a CoreWars warrior that wins? Additional details will be available after launching your challenge instance.

# Approach
Contents of imp.red file
```
;redcode
;name Imp Ex
;assert 1
mov 0, 1
end
```
Tried mov 1,1 and lost
Tried add 1,1 and lost
Tried to google corewars picoCTF to try to understand the corewars concept, and stumbled upon this post
Tried JMP 0, <-5 and the flag appears
Have no idea how it works.
# Flag
picoCTF{1mp_1n_7h3_cr055h41r5_b182a3f1}<br>
picoCTF{d3m0n_3xpung3r_ed173f56} - ready gladiator 2