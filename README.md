# goldman_sachs_virtual_simulation
Cracking given hashes with help of using John the ripper, Hashcat and Cain tools.

using hashcat method:
----------------------
#hashcat -m 0 -a 0 -o cracked.txt pwdump.txt rockyou.txt 

using john the ripper
----------------------
#john --wordlist=rockyou.txt --format=raw-md5 cracked.txt

using Cain:
------------
![Cain](https://github.com/nagarjunanettem3/goldman_sachs_virtual_simulation/assets/74127789/a1aa4f63-947b-4137-b8b6-1a19ab7acbee)
