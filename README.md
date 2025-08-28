# Encryption
Practice with different encryption software &amp; hardware. 8/27/25

This small lab helped me to familiarize with both encryption software and hardware for both browsers and operating systems. I also reviewed the history of encryption using a presentation found online, but I will not be detailing it here.

## VeraCrypt

Veracrypt was the first free software I found and used in today's project. It is open-source and fairly easy to use. This software can encrypt either your whole drive or create a container to hold sensitive data. I will be performing the latter.

1. After downloading VeraCrypt, a click to create a volume ang go through the process of creating a file container.

---

![photo1](https://github.com/MichaelJbyte/Encryption/blob/40a3dfd84f1bf999ae4eab66ceed6c456e7b26e1/VeraCrypt02.jpg)

Found via [veracrypt.io](https://veracrypt.io/en/Beginner%27s%20Tutorial.html)

---

2. Next I was able to chose the encrpytion algorithm for my new container. I selected the Advanced Encryption Standard (AES) and chose SHA-512 for my hash algorithm.
    - I chose these two understanding they will provide sufficient encrpytion for a lab and reasonable processing time.
    - During this time I also chose a strong password, a vital component in ensuring the confidentiality of the container.
  

3. Next I was able to dedicate a selected amount of storage to give the container. I chose 1 gigabyte. Following this, VeraCrypt prompted me to move the mouse around on the window swiftly. This would be used to randomize and format the container, finalizing its creation.

---

![photo2](https://github.com/MichaelJbyte/Encryption/blob/40a3dfd84f1bf999ae4eab66ceed6c456e7b26e1/VeraCrypt03.png)

Found via [arcanecode.com](https://arcanecode.com/2021/05/31/creating-and-using-hidden-containers-in-veracrypt/)

---

4. After the container's creation, I returned to the initial VeraCrypt window and mounted the newly encrypted file onto my computer. Once the password was entered, the file opened up as a seperate disk in the file explorer, allowing me to insert whatever sensitive data I have to keep encrypted.

---

![photo3](https://github.com/MichaelJbyte/Encryption/blob/40a3dfd84f1bf999ae4eab66ceed6c456e7b26e1/VeraCrypt01.png)


---

5. Finally, I closed the file and unmounted the container. This ensures my data stays safe and cannot be accessed unless VeraCrypt is used to mount and the right password is inserted.

## LastPass

LastPass is another program where encryption is used. LastPass is both a chrome extension and website used to store a variety of passwords. It utilizes AES-256 to encrypt its data. I will be using the services it offers by creating an account for it to hold, demonstrating its use, and acquainting myself with another method of encryption.

1. I begin by visiting the website and creating an account. This allows me to use their service and insert account details, free of worry.

2. As displayed below, I create fake credentials for a website titled Discogs. LastPass accepts them, encrypts the credentials, and locks them up. This displays to the user that their login info is kept secure with the AES-256 encryption, also showing the great assitance encryption can provide with daily tasks.

---

![photo3](https://github.com/MichaelJbyte/Encryption/blob/40a3dfd84f1bf999ae4eab66ceed6c456e7b26e1/LastPass1.png)


---

# Afterthoughts

Overall, this excercise taught me a great amount about encrpytion. I first reviewed the origins of cryptography, then proceeded to hands-on activities with encryption software. Combined, these practices helped to familarize me with both the concept and usage of encryption, displaying my understanding and newfound experience with basic cryptography tools. 

In a later update, I will use Microsoft's Bitlocker, via a Windows 11 virtual machine, to earn even more experience with cryptography.
