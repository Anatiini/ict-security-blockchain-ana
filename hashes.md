#h3 Hash

## Summarize

x) € Schneier 2015: Applied Cryptography: Chapter 2 - Protocol Building Blocks
  - One-way functions are a fundamental building block in applied cryptography.
  - These are easy to compute, hard to reverse.
  - Hash function takes a variable-length input string and changes it into a fixed-length output string. (Pre-image -> Hash value)
  - Changing a single bit in the pre-image results in approximately half of the bit values changing in the hash value, it is practically impossible to determine the pre-image given only the hash value.
  - Good one-way hash functions are collision-free, no same hash values from different pre-images.
  - Message Authentication Code is a one-way hash function with a secret key. So only the person with both the hash value and the key can verify it.

    Karvinen 2022: Cracking Passwords with Hashcat
  - Goes through the process of using hashcat, and giving an example hash to be cracked with all of the needed command prompts.

    Karvinen 2020: Command Line Basics Revisited
  - Gives all the basic commands needed to use Linux through the command prompt, very helpful for a Windows-man. Also installs nethack at the end. Only pushups were missing.

    Santos et al 2017: Security Penetration Testing - The Art of Hacking Series LiveLessons
  - Walked through on the basics of password cracking.
  - Demonstrated cracking with John the Ripper and Hashcat.
  - Consumers should always use 2FA.
  - Also recommended VPN usage in public networks and hotspots due to the traffic usually being open in those establishments.

##  Billion dollar busywork and others
a)
![image](https://github.com/user-attachments/assets/5017c785-0b5c-4792-bcbe-751a04b4f2e8)
I got the 0 start hash by using "hello31311". It is related to bitcoin via the proof-of-work.

b)
![image](https://github.com/user-attachments/assets/29e998a9-a592-45b0-a898-bb2812901320)
Both start with a number, can't find any other overlaps.

c)
![Capture](https://github.com/user-attachments/assets/9580a93e-9974-4692-9f01-b5e493494db8)
![hashtype id](https://github.com/user-attachments/assets/896a1e6a-682d-4047-a6f6-3e5c3e322332)
![solved password](https://github.com/user-attachments/assets/c8538a54-0918-425c-9a58-a262e47b9731)








  
# References
Schneier 2015: Applied Cryptography.
Santos et al 2017: Security Penetration Testing - The Art of Hacking Series LiveLessons
Karvinen 2022: Cracking Passwords with Hashcat
Karvinen 2020: Command Line Basics Revisited
