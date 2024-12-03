# h6 Upside Down Iceberg

# x) Summarize

## Tor: The second-generation onion router. Design goals and assumptions.
  - Tor-services goals are deployability, usability, flexibility, and simple design.
  - These goals are the basis on which Tor is built upon and they also make it very easy to use.
  - The creators of the article have deferred several "non-goals" because they have been fixed elsewhere, or because they are not yet solved at all. These include not having protocol normalization, or being completetely protected
    against end-to-end attacks.

## De-anonymisation attacks on tor: A survey.
  - Increasing popularity of anonymity networks such as Tor, also increases illegal activity and misuse of the anonymity, therefore leading to bigger interest in the de-anonymisation of clients by different LEAs and governments. The survey reviews different de-anonymisation attacks and techniques.
  - Anonymous connection systems are in increased demand to be used for sensitive communication between different millitary or business organizations. Also digital anonymity is very important in totalitarian states.
  - The Onion Router (TOR) project is the most popular anonymity network. Its availability and ease-of-use transfers to it being used as an accessory in cybercrime.
  - Attacks on TOR are divided into 4 categories: Network disruption, de-anonymisation, censorship, and generic attacks.

## Phishsticks
  - The video demonstrates pentesting done via a "phishstick", which is a malignant badUSB dropper disguised to look like a regular USB stick.
  - In the video, the demonstrated payload used is a keylogger, with which the pentester obtains the password of the CEO.
  - Truly the mastermind move was the social engineering through the note which got mr. CEO to insert the phishstick in the first place.

# TOR
Downloaded TOR from its site. Tried the sudo apt-get command at first but it showed something like this, so decided to go with the browser-method.

![image](https://github.com/user-attachments/assets/9f9d9399-5e07-4403-b95e-4c09de53cecb)

Success with the browser method!

![image](https://github.com/user-attachments/assets/ea38352c-75c4-4ec8-985d-b0811459bc35)

Extracted it to a directory and now trying to launch it.

![image](https://github.com/user-attachments/assets/0ffb34d6-05e7-4866-a585-68339dd77137)

Launched it via the terminal. Had some error insinuating it is already on. Restarting the VM.

![image](https://github.com/user-attachments/assets/9558e780-543e-4b3f-b4a3-b3f78df9cfce)

Trying different ways to run it, doesn't seem to run, it either complains that "bash ./: is a directory, or it tells that it has bootstrapped and is running, but there is no window or any other sign it has turned on :(

![image](https://github.com/user-attachments/assets/a0aefb38-673a-4c21-ace5-28e88b9bb773)

Tried all sorts of solutions, and at last one of them worked which was "bash start-tor-browser" in the extracted directory.

![image](https://github.com/user-attachments/assets/0ff39471-5b6e-430d-98f3-8aceb7b16970)

And at last we are here:

![image](https://github.com/user-attachments/assets/aa71f8b0-cea9-4128-a658-011f8c20f8ed)

First up,, the search engine, went to Ahmia which was demonstrated in class, and changed to the .onion version of the site.

![image](https://github.com/user-attachments/assets/26351852-3137-4cdb-bd79-404c84c78948)

After that went to the Venus marketplace to check out the prices of illegal substances.

![image](https://github.com/user-attachments/assets/7ccb47a5-d151-42b0-8ac1-5ae7299ee902)

Went to check hidden wiki for more links to different places.

![image](https://github.com/user-attachments/assets/637247ec-4f05-42c8-9005-7b840e040412)

Looked for different deep web browsers, the ads on the right seemed very trustworthy :)

![image](https://github.com/user-attachments/assets/7cfbbf65-2c48-4643-ab8e-1e1f095a119e)

Looked for a life extraction service. Wondered why is the same link shown multiple times? The hash seems to be the same.

![image](https://github.com/user-attachments/assets/fd862059-d6ff-42e0-8967-95f83c04d6ba)

Next up looked for a forum and found reddit's onion version.

![image](https://github.com/user-attachments/assets/cd1259f5-df7e-4bf8-9ff3-789087f4a460)

Also here is BBC News .onion domain.

![image](https://github.com/user-attachments/assets/6484844e-5c49-4428-9c32-1c47b2e6e7c2)

All in all, the hidden wiki proved the most useful site to browse the dark web. Would use it if I had a need to browse the dark web.


# Onion
TOR builds anonymity by using 3 different nodes from which it connects to the server, each adding a layer of security. Basically the first entry-node which you connect to "knows" who you are, then it goes through a middle
node and then an exit node, and the server only knows that it is communicating with the exit node. The 3 different layers are what gives it the name onion. Since onions have layers :)

# Threat models of TOR
In the usage of TOR, there are many threats or incidents which can occur. First, even though the anonymity provided by the browser is better than regular browsers, the anonymity is lessened by the number of people using it. More people using = more anonymity. So there might be an even higher chance of being de-anonymised even though the protection and hiding protocols would be better. There is also the criminal activity happening via the dark web. Since there are possibilities to remain anonym, this increases the cybercrime which happens in the dark web. This in turn increases the risks of collaborating with an illicit operator.

# Don't stick that stick
  - PhishStick attacks work by inserting the malicious device into some of the company's hardware. There are different payloads and different attacks which can be used via a PhishStick, but the basis is to disguise it as a regular USB stick.
  - A typical organization could be vulnerable, since the attacks usually target a singular person and where there is human judgment there is also a possibility for error.
  - I think it links to a broader category of social engineering. They aren't external attacks done from miles away, but you have to physically get the piece of hardware to the target. Technically you could be far away, but doubt many will stick a totally random USB sent in mail in their company laptop.
  - These risks are mitigated by security training, and good communication. Always make sure that a USB stick is truly from a trusted source before inserting it.


# References

Tor-project. https://www.torproject.org/download/

Homework. Assignments. https://terokarvinen.com/trust-to-blockchain/#h6-upside-down-iceberg

Karunanayake, Ahmed, Malaney, Islam and Jha 2021: De-anonymisation attacks on tor: A survey. https://css.csail.mit.edu/6.858/2022/readings/tor-design.pdf

Dingledine, Mathewson and Syverson 2004: Tor: The second-generation onion router. https://ieeexplore.ieee.org/ielx7/9739/9621320/09471821.pdf



