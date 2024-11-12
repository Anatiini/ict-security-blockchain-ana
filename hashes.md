#h3 Hash

## Summarize

x)  ## Schneier 2015: Applied Cryptography: Chapter 2 - Protocol Building Blocks
  - One-way functions are a fundamental building block in applied cryptography.
  - These are easy to compute, hard to reverse.
  - Hash function takes a variable-length input string and changes it into a fixed-length output string. (Pre-image -> Hash value)
  - Changing a single bit in the pre-image results in approximately half of the bit values changing in the hash value, it is practically impossible to determine the pre-image given only the hash value.
  - Good one-way hash functions are collision-free, no same hash values from different pre-images.
  - Message Authentication Code is a one-way hash function with a secret key. So only the person with both the hash value and the key can verify it.

    ## Karvinen 2022: Cracking Passwords with Hashcat
  - Goes through the process of using hashcat, and giving an example hash to be cracked with all of the needed command prompts.

    ## Karvinen 2020: Command Line Basics Revisited
  - Gives all the basic commands needed to use Linux through the command prompt, very helpful for a Windows-man. Also installs nethack at the end. Only pushups were missing.
  - Did an extra here by installing a nostalgic game which I found in the library, Battle for Wesnoth. Here's a screenshot for you.
  - ![Battle for wesnoth linuxilla!](https://github.com/user-attachments/assets/a9f5a505-8fbb-4f93-830c-ffd68e054c81)


    ## Santos et al 2017: Security Penetration Testing - The Art of Hacking Series LiveLessons
  - Walked through on the basics of password cracking.
  - Demonstrated cracking with John the Ripper and Hashcat.
  - Consumers should always use 2FA.
  - Also recommended VPN usage in public networks and hotspots due to the traffic usually being open in those establishments.

##  Billion dollar busywork and others
a) I got the 0 start hash by using "hello31311". It is related to bitcoin via the proof-of-work.
![image](https://github.com/user-attachments/assets/5017c785-0b5c-4792-bcbe-751a04b4f2e8)


b) Both start with a number, can't find any other overlaps.
![image](https://github.com/user-attachments/assets/29e998a9-a592-45b0-a898-bb2812901320)


c)
![Capture](https://github.com/user-attachments/assets/9580a93e-9974-4692-9f01-b5e493494db8)
![hashtype id](https://github.com/user-attachments/assets/896a1e6a-682d-4047-a6f6-3e5c3e322332)
![solved password](https://github.com/user-attachments/assets/c8538a54-0918-425c-9a58-a262e47b9731)

d) The cracked password is admin.
![image](https://github.com/user-attachments/assets/d0669096-4cec-417c-abd7-7b14a9109b33)

e) Best ways would be to use either some gibberish so the dictionaries don't have the words, use long lists of words, since longer passwords are much more secure, since the program needs to try exponentially more matches.
Also a password manager would be excellent, since the passwords they create are usually gibberish, and  therefore immune to dictionary attacks.

f) Hash rate in cracking this was 2432.7kH/s. I think it was slower than the ones before? Is the hash algorithm harder for the software than MD5?

g) The password was monkey in this.

i) Made a few own passwords with MD5 hash generator (https://www.md5hashgenerator.com/)
Tried the password guttercruiser, didn't crack it. Demonic and doglover worked.
![image](https://github.com/user-attachments/assets/0f11231e-a82d-4d30-bd55-d5ce24d0ff98)

j) installed John by compiling the package, success!
![John not working initially but fixed](https://github.com/user-attachments/assets/f85582d8-422e-48f8-9f70-e2bd2ad23f28)

k) the password was butterfly!
![Cracked](https://github.com/user-attachments/assets/0c340fb9-10a1-45e7-a383-78986a336dd1)
















  
# References
Schneier 2015: Applied Cryptography. https://www.oreilly.com/library/view/applied-cryptography-protocols/9781119096726/10_chap02.html#chap02-sec003

Santos et al 2017: Security Penetration Testing - The Art of Hacking Series LiveLessons.  https://www.oreilly.com/videos/security-penetration-testing/9780134833989/9780134833989-sptt_00_06_00_00/

Karvinen 2022: Cracking Passwords with Hashcat. https://terokarvinen.com/2022/cracking-passwords-with-hashcat/

Karvinen 2020: Command Line Basics Revisited. https://terokarvinen.com/2020/command-line-basics-revisited/

Karvinen 2023 Crack File Password With John. https://terokarvinen.com/2023/crack-file-password-with-john/

MD5 Hash Generator. https://www.md5hashgenerator.com/
