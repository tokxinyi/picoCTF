# Safe Opener 2

Author: MUBARAK MIKAIL<br>
Points: 100

# Tags
picoCTF2023, Reverse Engineering

# Description
What can you do with this file?
I forgot the key to my safe but this file is supposed to help me with retrieving the lost key. Can you help me unlock my safe?

# Hints
Download and try to decompile the file.

# Approach
1. Tried top open the file with `vim` and it shows a bunch of random symbols.
2. Ran `strings SafeOpener.class` to see what human-readable strings can be found in the file and the flag is in the output.

# Flag
picoCTF{SAf3_0p3n3rr_y0u_solv3d_it_198203f7}