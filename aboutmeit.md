---
layout: page
title: About me
subtitle: informazioni generali
---

# Informazioni personali

Il mio nome è Leonardo, studio matematica all'Università di Trento e penso che in futuro mi divertirò anche a raccontarla, non so bene come. Una possibilità è [il canale YouTube](https://www.youtube.com/channel/UCO1l67JZBNiNEA2cb8M1fbQ), o forse dei libri, chissà.

<figure>
  <img src="https://user-images.githubusercontent.com/64229723/193805618-de2d2594-bd61-48d5-ace9-893dc562eb0c.jpg" alt="me" class="center" width="300"/>
  <figcaption><center>come mi piace dire, <em>un buon piano va lontano</em></center></figcaption>
</figure>

Formulo un mare di piani ed alcuni a volte funzionano. D'altronde ci sono troppe cose da fare e così poco tempo per farle.

Se vi dicono che sono un supercattivo non ascoltate, tutte menzogne! Cosa, quel ritratto da supercattivo in cima alla pagina? Non è mio, deve essere finito lì per caso...

#### cv in inglese (ottobre 2023): [PDF](https://github.com/PlasmaStark/plasmastark.github.io/files/12927004/cv.eng.pdf)


# Progetti

Alcuni progetti su cui ho lavorato per la mia laurea magistrale.

#### Implementazione di varie primitive di interesse crittografico.

**Da:** settembre 2021

**Fino al:** giugno 2022

**Linguaggio:** MAGMA

**Descrizione:** Abbiamo dovuto scrivere implementazioni di vari algoritmi e protocolli di interesse crittografico e studiarne il funzionamento. Questo faceva parte del nostro corso di _Crittografia Algebrica_. Esempi includono
- primitive simmetriche
- funzioni hash
- schemi di firma standard
- schemi di firma ad anello
- algoritmi di fattorizzazione
- algoritmi di logaritmi discreti
- distribuzione delle chiavi
- Dimostrazioni ZK
- ...

Ovviamente non posso mostrarli pubblicamente, invaliderebbe tutti i progetti MAGMA per questo corso :)

Abbiamo avuto anche due progetti di gruppo consistenti nell'implementazione e nell'analisi dettagliata di altri algoritmi simili. E ovviamente non posso mostrare nemmeno questi pubblicamente!

#### Creazione di un algoritmo di fattorizzazione tramite curve di Pell.

**Da:** marzo 2022

**Fino al:** giugno 2023

**Linguaggio:** MAGMA, Python

**Descrizione:** Per il nostro corso di _Teoria avanzata dei numeri_, dovevamo trovare alcune applicazioni interessanti di qualcosa che avevamo studiato. Ho provato a sfruttare la struttura di gruppo dell'insieme di punti delle Curve di Pell (PC) per costruire un algoritmo di fattorizzazione.

Questo è simile a quello che facciamo con le Curve Ellittiche (EC), ma si è rivelato molto più difficile: le EC hanno un'operazione interessante nella loro struttura di gruppo che possiamo sfruttare come punto di uscita dell'algoritmo, le PC no. L'esperimento si è rivelato parzialmente infruttuoso, ma si potrebbe ricavarne qualcosa.

#### Creazione di un algoritmo di fattorizzazione tramite sequenze ricorrenti di ordine tre

**Da:** giugno 2023

**Fino al:** luglio 2023

**Linguaggio:** Python

**Descrizione:** Per il nostro corso di _Teoria avanzata dei numeri_, dovevamo trovare alcune applicazioni interessanti dei contenuti del corso. Dopo aver provato a lavorare con Curve di Pell, ho provato a ricavare qualcosa dalle sequenze ricorrenti. Disponiamo già di eccellenti algoritmi e teoremi per sequenze di ordine due.

Il tentativo è riuscito parzialmente. Ho dovuto in parte cercare con brute-force i parametri poiché manca una teoria generale al riguardo (ad esempio avremmo avuto bisogno di una generalizzazione del simbolo di Jacobi per i residui cubici). Sebbene alcuni parametri abbiano fornito un algoritmo interessante, il test ha comunque funzionato male rispetto alle sequenze di ordine due: la teoria è troppo complessa e la fase di setup dell'algoritmo è inefficiente a confronto.


#### Chat semplice in Java

**Da:** dicembre 2022

**Fino al:** dicembre 2022

**Linguaggio:** Java, C, bash

**Descrizione:** Per il progetto finale del nostro corso _Programmazione Avanzata di Metodi Crittografici_ abbiamo dovuto costruire un server di chat in grado di connettersi a un numero arbitrario di client su un'architettura UNIX. Questo era un progetto di gruppo.

- Abbiamo lavorato insieme ad un protocollo di comunicazione scalabile che permettesse di gestire vari scenari, ad esempio la disconnessione dell'utente.
- Le primitive sono state scritte da me in C (SHA2, AES-GCM, RSA e tutti i relativi riempimenti) e importate in Java utilizzando JNI.
- Ho lavorato anche sulla grafica utilizzando CSS e JavaFX.
- Altri membri hanno lavorato sulle classi Java necessarie per mettere insieme il tutto e realizzare un progetto funzionante.
- Ho scritto alcuni comandi bash per consentire una rapida configurazione del progetto.

#### Watermarking: embedding ed attacchi

**Da:** ottobre 2022

**Fino al:** novembre 2022

**Linguaggio:** Python

**Descrizione:** Come parte del nostro corso _Data Hiding_, abbiamo dovuto creare (1) un algoritmo di embedding per inserire watermark nelle immagini e (2) un attacco per rimuovere watermark. Questo era un progetto di gruppo nel contesto di una competizione.

- Abbiamo studiato insieme varie pubblicazioni per trovare il miglior algoritmo di embedding, ovvero quello che potesse ottenere una buona qualità dell'immagine e una notevole resistenza agli attacchi.
- Altri membri hanno implementato due diversi algoritmi di embedding.
- Ho trovato un interessante attacco statistico sfruttando le ipotesi su cui si svolgeva il concorso, e poi sfruttato tecniche di analisi numerica per massimizzare la qualità dell'immagine rimuovendo il watermark. Luca Di Domenico ha avuto un'altra idea per perfezionare ulteriormente questo attacco.
- Abbiamo utilizzato l'attacco per testare il miglior algoritmo di embedding e ne abbiamo fornito uno per la concorrenza.

  Abbiamo raggiunto un [PSNR](https://en.wikipedia.org/wiki/Peak_signal-to-noise_ratio) di circa 60 su tutti i watermark rotti e li abbiamo rotti tutti, vincendo la competizione.

#### Implementazione, studio e presentazione di Quadratic Sieve

**Da:** settembre 2021

**Fino al:** ottobre 2021

**Linguaggio:** MAGMA

**Descrizione:** Nell'ambito dell'iniziativa _Percorso dell'Eccellenza_, ho tenuto una presentazione su Quadratic Sieve che può essere trovata su questo sito. L'ho implementato con MAGMA e ne ho studiato la complessità, che ovviamente era già ben nota in letteratura.

#### Miscellanea

Alcuni altri progetti su cui ho lavorato da solo e senza alcun motivo.
- Algoritmo di correzione e rilevamento codici ISBN (Python)
- Tema Beamer ufficiale UniTN per il Dipartimento di Matematica
- Libreria Python personalizzata per operazioni su segnali digitali a tempo discreto
- Altre cose di cui probabilmente mi sono dimenticato

