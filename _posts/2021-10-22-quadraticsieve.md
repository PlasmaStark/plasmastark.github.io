---
layout: post
title: Quadratic Sieve
subtitle: come fattorizzare numeri composti! ... probabilmente?
gh-repo: PlasmaStark
gh-badge: [follow]
tags: [specialistico, algebra computazionale]
comments: true
---

Avendo di nuovo trovato una sorprendente quantità di tempo libero, mi trovo a raccontare di un algoritmo per la fattorizzazione di numeri composti dalla grande rilevanza storica.
Quadratic Sieve è a tutti gli effetti il nonno di molti degli algoritmi che vengono utilizzati ancora oggi - ad esempio GNFQS - e ne vedremo una versione elementare e semplificata. Vedremo anche in che senso si tratta di una versione "semplificata".

Siccome sto provando a studiare crittografia, costringerò il lettore a valutare anche la rilevanza crittografica di questo tipo di algoritmi e delle loro più recenti implementazioni.

L'argomento mi è stato consigliato dal professor Nadir Murru dell'Università di Trento, che ringrazio ancora per la prontissima disponibilità.

## Abstract

Discuteremo dell’algoritmo di fattorizzazione QS (Quadratic Sieve) e del suo ruolo nel contesto storico crittografico di fine secolo, utilizzando il crittosistema RSA come base didattica ed intuitiva per tale utilizzo di QS. Dopo un approccio intuitivo ad RSA e QS, potremo procedere da una prospettiva teorica ed in seguito analizzare le conseguenze di quanto visto.

_Seminario nell'ambito del PEM - Laurea Triennale_

## Documenti

PDF: [PDF_2021-10-19.pdf](https://github.com/PlasmaStark/plasmastark.github.io/files/7404288/PDF_2021-10-19.pdf)


Slides: [Quadratic_Sieve_slides.pdf](https://github.com/PlasmaStark/plasmastark.github.io/files/7404284/SLIDES_2021-10-21.pdf)


Registrazione: [Google Drive](https://drive.google.com/file/d/1xeV2917JCaEqjg0tOSMMl1d9aeCoeaXU/view?usp=sharing)

![1 3tKUTKDKh84hmiJlLHQoWA](https://user-images.githubusercontent.com/64229723/115857445-fe306480-a42d-11eb-93fa-e45ca597a4c8.jpeg){: .mx-auto.d-block :}
*(immagine dall'[articolo del prof. Bill Buchanan](https://medium.com/asecuritysite-when-bob-met-alice/so-how-many-bits-does-the-prime-number-have-e5dbbdf568ea), Medium)*

## Bibliografia

Mi sono basato soprattutto sull'articolo di Pomerance _A Tale of Two Sieves_ per l'aspetto storico; una lettura decisamente interessante per chi volesse approfondire. Le altre fonti sono in bibliografia, ma si tratta di testi decisamente più tecnici.
