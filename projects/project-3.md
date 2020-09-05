---
layout: project
type: project
image: images/Project3.PNG
title: SHA-1
permalink: projects/SHA-1
# All dates must be YYYY-MM-DD format!
date: 2020-04-25
labels:
  - C Language
  - Cryptosecurity
  - SSH
  
summary: My team developed a simple Pokemon GO game with Java's GUI function that allows either capture or escape from nine random Pokemon,
---

<div class="ui small rounded images">
  <img class="ui image" src="../images/Project1-2.PNG">
  <img class="ui image" src="../images/Project1.PNG">
  <img class="ui image" src="../images/Project1-3.PNG">
  
</div>

  SHA-1 HASH is a program that takes an input and produces a message digest (160-bit hash value). It was an ICS 212 final project and it was written in a C program. The program itself will convert any text files that contain any written letters (max of 1,048,576 chars) and convert them into 160-bit hash value. The SHA-1 algorithm was supposed to be secure, however, it was proven to be theoretically vulnerable to attack by other specialists, therefore, not secure at all. 	
  
  We were given a pseudocode for SHA-1 and our objective was to convert it into a C program. There are five functions written in the program. The first function is to read the text file and convert them into bits while appending the 1 bit at the end of the message. Then, calculateBlock() will calculate how many blocks (512 bits) of a file and then it returns a blockCount. After that, it passes to a function that converts the char array into an int array which allows it to be passed into the message digest that will produce a 160-bit value. This program took around two weeks to complete.

   During this project, I learned more about C programming such as pointers, SHA-1, pseudocode, and how to use SSH. I learned that the C program is very good with manipulating the data with pointer references. Furthermore, I also learned a little more about how SHA-1 works. Lastly, I learned more how to use SSH and how to use a command prompt. 


You can learn more at the [GitHub Repositories Website](https://github.com/cjsiador/SHA-1-in-C-Language).
