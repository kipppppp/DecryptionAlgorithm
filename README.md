<h1>Encryption/Decryption Algorithm</h1>

<h2>Description</h2>
This project allows the user to encrypt a string. Utilizes overloaded constructors to assign random keys, or allows the user to specify the amount of keys (1-20) and the specific key values (1-126). The decryption algorithm utilizes brute force to iterate through key values, scanning the potentially decrypted text for the occurence of the 5 character string " the ". If found, the message is displayed to the user with the current key values. The user has the option to continue searching through keys if the message is not correctly decrypted.

The overall program is broken into 4 header files and 4 C++ files for modularization. Because this project was completed for course work, I am unable to <ins>publically</ins> share the source code.
<br />


<h2>Languages Used</h2>

- <b>C++: Header files to compartmentalize classes, public & private data members</b> 

<h2>Program Walk-Through:</h2>

<p align="center">
View the plain text, encryption key, encrypted text, and decrypted text using known key <br/>
<img src="https://i.imgur.com/UI56ueg.png" height="50%" width="50%" alt="Launch program"/>
<br />
<br />
Utilize brute force decryption algorithm (all attempted keys displayed)  <br/>
<img src="https://i.imgur.com/39pj0Me.png" height="50%" width="50%" alt="Brute force decrypt"/>
<br />
<br />
</p>
