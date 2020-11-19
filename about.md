---
layout: page
title: Cos'è un CTF
permalink: /abouts
menu: true
---
Un **Capture the Flag** (abbreviato in **CTF**) è un gioco di **hacking** dove team o singoli cercano **vulnerabilità** in sistemi e software messi a disposizione dagli organizzatori della competizione al fine di sfruttarle e di collezionare le varie **flag** nascoste sul sistema bersaglio. Oltre a trovare e sfruttare vulnerabilità molte challenge consistono in risolvere **puzzle logici** o capire come funziona e come abusare un sistema. Il gioco è ispirato e prende il nome da [Rubabandiera](https://it.wikipedia.org/wiki/Rubabandiera), che in inglese è chiamato appunto Capture the Flag.

Ci sono vari tipi di Capture the Flag. I più famosi sono **[Jeopardy](#jeopardy)**, **[Attack/Defense](#attack-defense)** e **[Boot2Root](#boot2root)**. Seppure questi siano i formati più popolari, ci sono rari casi di CTF con formato misto, per esempio Jeopardy + Attack/Defense, o che non rispettano nessun formato particolare.

### <a href="#jeopardy" name="jeopardy">Jeopardy</a>
I CTF di tipo Jeopardy sono probabilmente i più popolari, dato che si adattano bene a competizioni online. In questo formato gli organizzatori mettono a disposizione dei giocatori diverse “challenge”, ognuna delle quali offre una singola flag. Quando un giocatore trova la flag, a seconda della difficoltà della challenge, guadagna dei punti. Il giocatore con il numero più alto di punti vince il CTF.

Queto formato è generalmente a squadre. Le challenge vengono divise e assegnate tra i membri della squadra per velocizzare la loro risoluzione e la conquista delle flag, dato che in genere le competizionii hanno un limite di tempo.

### <a href="#attack-defense" name="attack-defense">Attack/Defense</a>
Il formato Attack/Defense prevede che gli organizzatori forniscano ai giocatori (anche in questo caso principalmente squadre) una o più macchine virtuali. I giocatori quindi avranno un doppio ruolo: cercare di difendere i servizi esposti sulla macchina virtuale (senza compromettere la loro disponibilità) e allo stesso tempo attaccare i servizi dei team concorrenti. Ogni partecipante conquista dei punti di attacco e dei punti di difesa, a seconda di quante flag vengono rubate da un determinato servizio e quante flag vengono conquistate. Il giocatore con il numero più alto di punti è proclamato vincitore.

Data la complessità organizzativa di questo tipo di eventi, i CTF Attack/Defense sono principalmente riservati per eventi “offline” e, come nel formato Jeopardy, i partecipanti formano squadre e hanno un limite di tempo.

### <a href="#boot2root" name="boot2root">Boot2Root</a>
Questo formato di CTF è principalmente preferito da singoli che vogliono esercitarsi a sfruttare vulnerabilità in uno scenario semi-reale, ma non preclude la possibilità di creare un team. In questo caso, l’organizzatore mette a disposizione una macchina virtuale da scaricare, e lo scopo dei giocatori è di trovare e sfruttare vulnerabilità che alla fine daranno accesso root o Administrator alla macchina virtuale.

Essendo questo un formato principalmente offline e senza limite di tempo, non è competitivo, quindi non ci sono punti da conquistare e vincitori.
