---
layout: page
title: About me
subtitle: general information
---

# Personal information

My name is Leonardo, I study mathematics at University of Trento and I think I will enjoy speaking about maths in the future - although I have no idea how. 
One chance could be [my youtube channel](https://www.youtube.com/channel/UCO1l67JZBNiNEA2cb8M1fbQ), or maybe writing books, who knows.

My apologies if the content of this website is mostly in Italian, but it would be quite the hustle to translate it all! I could do it some time in the future though.

<figure>
  <img src="https://user-images.githubusercontent.com/64229723/193805618-de2d2594-bd61-48d5-ace9-893dc562eb0c.jpg" alt="me" class="center" width="300"/>
  <figcaption><center>as I like to say, <em>a good plan goes a long way</em></center></figcaption>
</figure>

I generate lots of plans and sometimes some of them even work. After all, there is too much to do in too little time.

Don't listen to those nasty rapscallions going around telling I am a supervillain, lies and deceptions! What, that villain-ish portrait? It's not mine, how did it even get on this page?

### CV (october 2023): [PDF](https://github.com/PlasmaStark/plasmastark.github.io/files/12927004/cv.eng.pdf)

----------

# Projects 

Some projects I worked on for my MSc.

### Implementation of various primitives of cryptographical interest.

**From:** September 2021

**To:** June 2022

**Language:** MAGMA

**Description:** We had to write implementations of various algorithms and protocols of cryptographical interest, and then study their inner workings. This was part of our _Algebraic Cryptography_ course. Examples include 
- symmetric primitives
- hash functions
- standard signature schemes
- ring signature schemes
- factorisation algorithms
- discrete logarithm algorithms
- key distribution
- ZK proofs
- ...

Of course I cannot publicly show these, as it would invalidate all MAGMA projects for this course :)

We also had two large group projects consisting in the implementation and detailed analysis of other similiar algorithms. And of course, I cannot publicly show these either!

### Creation of a factorisation algorithm via Pell curves.

**From:** March 2022

**To:** June 2023

**Language:** MAGMA, Python

**Description:** For our _Advanced Number Theory_ course, we had to find some interesting application of something we studied. I tried exploiting the group structure of the point set of Pell Curves to build a factorisation algoritm. 

This is similiar to what we do with Elliptic Curves, but it proved to be way more difficoult: EC have an interesting operation in their group structure we can exploit as an exit point of the algorithm, PC do not. The experiment proved partially insuccessful, it could be possible to get something out of it.

## Creation of a factorisation algorithm via recurrent sequences of order three

**From:** June 2023

**To:** July 2023

**Language:** Python

**Description:** For our _Advanced Number Theory_ course, we had to find some interesting application of something we studied. After my attempt at working with Pell Curves, I tried getting something out of recurrent sequences. We already have excellent algorithms and theorems for order two sequences. 

The attempt was partially successful. Parameters needed to be brute-forced in part since there is a lack of general theory on this (e.g. we would have needed a generalisation of the Jacobi Symbol for cubic residuals). While some parameters provided an interesting algorithm, the test still performed badly with respect to order two sequences: the theory is too complex and the setup of the algorithm is inefficient if compared to them.

### Simple chat in Java

**From:** December 2022

**To:** December 2022

**Language:** Java, C, bash

**Description:** For the final project of our _Advanced Programming of Cryptographic Methods_ course, we had to build a chat server able to connect to an arbitrary number of clients over an UNIX architecture. This was a group project.

- We worked together a scalable communication protocol that allowed to handle various scenarios, for example user disconnection.
- Primitives were written by me in C (SHA2, AES-GCM, RSA and all their paddings) and imported in Java using the JNI.
- I also worked on the graphics using CSS and JavaFX.
- Other members worked on the Java classes needed to put all together and achieve a working project.
- I wrote some bash commands to allow a quick setup of the project.

### Watermarking: embedding and attacks

**From:** October 2022

**To:** November 2022

**Language:** Python

**Description:** As part of our _Data Hiding_ course, we had to build (1) an embedding algorithm to insert watermarks in images and (2) an attack to remove watermarks. This was a group project in the context of a competition.

- We studied together various publications to find the best embedding algorithm, i.e. one that could achieve good image quality and considerable resistance to attacks.
- Other members implemented two different embedding algorithms.
- I found an interesting statistical attack exploiting the hypotheses under which the competition was held, and then exploited techniques from numerical analysis to maximise image quality while removing the watermark. Luca Di Domenico had another idea to furter perfect this attack. 
- We used the attack to test for the best embedding algorithm and provided that one for the competition.

 We achieved a [PSNR](https://en.wikipedia.org/wiki/Peak_signal-to-noise_ratio) of around 60 on all broken watermarks, and broke all of them, winning the competition.

### Implementation, study and presentation of Quadratic Sieve

**From:** September 2021

**To:** October 2021

**Language:** MAGMA

**Description:** As part of the _Excellence Path_ initiative, I held a presentation on Quadratic Sieve which can be found on this website. I implemented it with MAGMA and studied its complexity, which was of course already well known in literature. 

### Miscellanea 

Some other projects I worked on by myself and for no reason at all.
- ISBN correction and detection algorithm (Python)
- UniTN official Beamer theme for the Department of Mathematics
- Custom Python library for operations on discrete-time digital signals
- Other stuff I probably forgot about
