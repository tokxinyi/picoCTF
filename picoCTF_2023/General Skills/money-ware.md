# money-ware

Author: JUNI19<br>
Points: 100

## Description
Flag format: picoCTF{Malwarename}
The first letter of the malware name should be capitalized and the rest lowercase.
Your friend just got hacked and has been asked to pay some bitcoins to 1Mz7153HMuxXTuR2R1t78mGSdzaAtNbBWX. He doesn’t seem to understand what is going on and asks you for advice. Can you identify what malware he’s being a victim of?

## Tags
picoCTF 2023, General Skills, OSINT

## Hints
1. Some crypto-currencies abuse databases exist; check them out!
2. Maybe Google might help.

## Approach
1. Google crypto-currencies databases, malware etc for hints
    - Learnt about cryptomalware and that it is usually hidden
    - Did not get anything useful
2. Search for the address provided in the description and found [this article](https://www.vsec.infinigate.co.uk/blog/worlds-most-famous-bitcoin-wallets-petya-wannacry-ransomware)

## Flag
picoCTF{Petya}