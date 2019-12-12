# Cryptography
<p align="center">
  <img src="/cryptography.png" height= "420" width="600"/>
</p>

**[View Cryptography Project](https://saharafathelbab.github.io/Cryptography/Cryptography/Cryptfun.html?)**
<br> 

#### General Information

Inspired by the book Code Girls, I developed my own Code & Cipher system. The aim of this Cryptography project
is for peers to communicate with a private key - the codebook I created. The encoded message is only able to be read
if a peer has the private key to decipher the message.

#### Technologies Used

* HTML & CSS
* JavaScript

#### Editor Used

* Atom

#### Special Note:

The author of the book Code Girls reached out to tell me how thrilled she was to see that
her book prompted me to create my own code & cipher system.

##### Why was this project created?

The inspiration for this side project came from the book Code Girls. After finishing the book in early December 2017, in January 2018 I decided to try my hand at creating a Code & Cipher.

#### Aim of Cryptography Project

The aim of this Cryptography project is for peers to communicate with a private key - the codebook I created. The encoded message is only able to be read if a peer has the private key to decipher the message.

#### What is the problem and how does this Cryptography Project solve it?

Problem: People want to have secure communications and to prevent sensitive information from getting into the wrong hands.

Cryptography Project Solution: This Cryptography Project allows for peers to have secure communications that can only be deciphered via the codebook.

I would like to note that this is an imaginary problem based on the book Code Girls. The book details that secure communications was necessary to ensure that coordinates of the US Army & Navy during WWII did not end up in the hands of the enemy.

#### What is the difference between a Code & Cipher? </h1>
Code: Words/Phrases are converted into something else; shortening the message.
Cipher: The level of individual letters, small groups of letters, or in modern schemes, individual bits and blocks of bits.

#### Functional Requirements:
For each letter, Lowercase and Uppercase, I wanted for it to be ciphered.
For words, phrases, Special Characters, and Numbers , I want for that to be coded.

#### Researching Ciphers
For inspiration for my cipher, I decided to look at ciphers used in the past.
<a href = "https://www.exploratorium.edu/ronh/secret/secret.html"> Francis Bacon </a> created a substitution cipher where each letter was turned into 5 character groups. I decided to use this method of ciphering for individual Uppercase and Lowercase letters. I decided to use the author's name: <b>Liza Mundy </b> as a base. As shown below, for the letter A, I used the letter L (first letter in her first name) as a place holder for four characters and the fifth character is an M (first letter in her last name).
    <p class="center">
      <img height="400px" width="300px" src = "/images/Dictionarystart.JPG" alt = "first draft cipher">
    </p>

After completing this, I realized how easy it would be for someone to essentially crack the cipher. In the book, it mentioned how WAVES - Navy Women Accepted for Volunteer Emergency Service would look forpatterns to decipher & decode ciphers and code.

After realizing how easy it would be for someone to grasp the flow of the cipher and piece together which five character group stood for each letter, I decided to go back to the drawing board. I knew I wanted to continue using five characters for each letter, but I knew that in order for the cipher to be stronger and harder for someone without the codebook to decipher, I needed to fix the arrangement of what five characters equated to each letter.

The <a href = "https://www.exploratorium.edu/ronh/secret/secret.html"> diagrammatic cipher</a> - <a class = "link_for_crypt" href = "http://crypto.interactive-maths.com/pigpen-cipher.html"> Pigpen cipher </a> - caught my eye, and I decided to implement the diagrammatic cipher with my Fracis Bacon inspired cipher with a slight difference. I decided to use the diagonal effect and placed the five character groups in 5 rows. Then I would list the letter the five character group would be assigned to in diagonal format.

After completing this diagonal format for all 26 letters, I then decided to add another minor change to my cipher to include spaces in between the letters.

In the end, lowercase and uppercase letters had a unique cipher each.


#### Researching Codes

For the code for Words, Phrases, Special Characters and Numbers, I decided to first look at Telegraphic Codes. I looked at

<a href = "https://en.wikipedia.org/wiki/Commercial_code_(communications)"> Commerical code (communications)</a>,

<a class = "link_for_crypt" href = "https://en.wikipedia.org/wiki/Australian_railway_telegraphic_codes"> Australian Railway Telegraphic Codes </a>

<a class = "link_for_crypt" href = "https://en.wikipedia.org/wiki/Great_Western_Railway_telegraphic_codes"> Great Westen Railway Telegraphic Codes </a>

Since cable tolls were charged by the word, phrases and words became small code groups and thus saved a lot of people money. Below is an example of a <a class = "link_for_crypt" href = "https://en.wikipedia.org/wiki/Commercial_code_(communications)"> 1910 radiator catalog: </a>

<p class="center">
    <img height="400px" width="300px" src = "/images/telegraphcode.jpg" alt = "telegraphic code">
</p>


In the Australian Railway Telegraphic Codes and Great Western Railway Telegraphic codes large phrases were shortened into code groups. <a class = "link_for_crypt" href = "https://en.wikipedia.org/wiki/Great_Western_Railway_telegraphic_codes"> For example: </a>
        
<b>Boyne </b> – There is no water at the following station. Instruct drivers.

I then began to search for a telegraphic book to learn more about how coding worked for each phrase. I found the

<a href = "https://archive.org/details/unicodeuniversa00unkngoog">1889 "Unicode".: The Universal Telegraphic Phrase-book </a>.
From there, as I flipped through the pages, I discovered that the first began with the two letters Ab(other letters) and the next section after that was Ac(other letters) and so forth:

<p class="center">
      <img height="400px" width="300px" src = "/images/codebooktelegraph.png" alt = "telegraphic code"/>
</p>

#### What does my code look like?
For my code for Words, Phrases, Numbers and Special Characters I decided to adopt the same technique described above. My codebook, after the ciphered letters, is divided into sections of frequent 2 letter words, 4 letter words, questions etc.

#### Why is your codebook in its entirety not available for viewing?</h1>

Well, wouldn't that defeat the purpose? I want you - however you landed here, welcome! - to try and break my code and cipher system just as the WAVES - Women Accepted for Volunteer Emergency Service- broke the German's code & cipher system. The author said to me, when she discovered my cryptography project, many will try to break the code & cipher system. And to that I say, good luck & enjoy the challenge! (and try not to cheat by looking at my source code!)
