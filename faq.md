---
layout: page
title: FAQ Sicurezza Informatica
permalink: /faq
menu: true
---
***DISCLAIMER** Questo documento non vuole essere un dogma. Le informazioni riportate in basso sono principalmente frutto di opinioni di una community e non sono "scientificamente dimostrate". Sebbene il documento contenga informazioni potenzialmente applicabili a qualsiasi circostanza, il target audience comprende principalmente giovani studenti indecisi. Se volete proporre nuovi contenuti, siete invitati a fare una pull request.*

### Voglio entrare nel mondo della sicurezza informatica, da dove inizio?

La sicurezza informatica è una specializzazione dell'informatica, quindi una conoscenza informatica "moderna" di base è necessaria:

- Programmazione (algoritmi, strutture dati, ecc.)
- Sistemi Operativi (come funzionano, come interagirci, ecc.)
- Reti (almeno i protocolli fondamentali dello stack tcp/ip)
- Architettura (macchina di Von Neumann, un asm moderno, ecc.)

Se credi di avere già un'infarinatura su questi argomenti, puoi cominciare a studiare i concetti specifici collegati al ramo della sicurezza informatica che più ti interessa. Ad esempio:

- Malware Analysis: focus su asm Intel e ARM, techniche di binary analysis, internals Windows/Android.
- Application Security: focus su sistemi operativi/mitigation, programmazione sicura, classi di vulnerabilità.
- Network Security: focus su protocolli di rete a ogni layer e relative classi di attacco, networking stack dei sistemi operativi.
- Incident Response/Digital Forensics: focus su periferiche e i loro canali di comunicazione, file system e hard/solid state drive, Windows/Linux internals.

Inutile ricordare che la conoscenza dell'inglese è fondamentale, e viene prima di qualsiasi altra cosa.

### Quale corso universitario devo seguire?

I corsi consigliati sono quelli che coprono gli argomenti elencati nella prima domanda, quindi per la triennale un corso di Computer Science (informatica) o Computer Engineering (ingegneria informatica).
Esistono anche corsi sulla sicurezza informatica triennali o magistrali, in presenza o online.
Per una lista aggiornata dell'offerta accademica in Italia consulta il sito del [Consorzio CINI](https://cybersecnatlab.it/formazione-in-cybersecurity/).

### Quale OS devo usare?

Quello su cui hai più dimestichezza. Se hai bisogno di un sistema operativo particolare è sempre possibile usare una macchina virtuale (ad es. Virtualbox). Ovviamente, se ti interessa imparare un sistema operativo specifico, usa quello come sistema operativo principale.

### Devo installare Kali Linux (o BackBox, Parrot, BlackArch, ecc...)?

Per studiare sicurezza informatica non è necessario installare Kali Linux, nè in una macchina virtuale, nè come OS principale. Quando si studia un argomento, tipicamente si usano 1-3 tool specifici. Le distribuzioni dedicate come Kali hanno lo scopo di offrire centinaia di tool senza doversi preoccupare di installarli e configurarli. È facile intuire che con un'esigenza di 1-3 tool, installarne centinaia sia uno spreco. In situazioni invece dove, per esempio, si ha la necessità di dover lanciare una singola volta un tool specifico, mai usato prima, che richiede patch e dipendenze installate da sorgente, una distribuzione dedicata è perfetta. Ma raramente studiando ci si trova in questa situazione.

### Devo prendere certificazioni? Quali?

Le certificazioni sono il mezzo per il quale un'azienda può dimostrare di avere personale con competenze in un settore, verificate da un ente indipendente e riconosciuto. Sono quindi principalmente uno strumento aziendale e non un percorso formativo. È quindi responsabilità delle aziende permettere e supportare i propri dipendenti ad ottenere certificazioni professionali.

In termini d'utilità:
- Se sei uno studente senza esperienza lavorativa, non è detto che una certificazione ti aiuti a trovare lavoro perché probabilmente sarai sullo stesso piano di qualcuno non certificato
- Se sei un lavoratore con esperienza informatica ma SENZA esperienza in ambito sicurezza informatica, una certificazione potrebbe aiutarti a cambiare carriera ma probabilmente non sarà sufficiente per mantenere una seniority equivalente
- Se sei un lavoratore con esperienza in ambito sicurezza informatica, una certificazione specifica potrebbe aiutarti a trovare lavoro presso un'aziende che la richiede, ma anche in quel caso potrebbe non essere sufficiente, dato che non si riuscirebbe a dimostrare esperienza in materia

## Letture consigliate suddivise per categoria

### Crypto

- [Applied Cryptography: Protocols, Algorithms, and Source Code in C](https://www.amazon.it/Applied-Cryptography-Protocols-Algorithms-Source/dp/1119096723/)
- [Serious Crypto](https://nostarch.com/seriouscrypto)
- [CryptoBook](https://crypto.stanford.edu/~dabo/cryptobook/)
- [Overview of Cryptography](https://www.garykessler.net/library/crypto.html)

### Sistemi operativi/architettura

- [I moderni sistemi operativi](https://www.amazon.it/moderni-sistemi-operativi-aggiornamento-online/dp/8891901016/)
- [Architettura calcolatori](https://www.amazon.it/Architettura-dei-calcolatori-approccio-strutturale/dp/8871929624/)

### Programmazione

- [Introduction to Algorithms](https://www.amazon.it/Introduction-Algorithms-Thomas-H-Cormen/dp/0262533057/)
- C
  - [King](https://www.amazon.it/Programmazione-C-Kim-N-King/dp/8838785821/)
  - [K&R](https://www.dipmat.univpm.it/~demeio/public/the_c_programming_language_2.pdf)
- Assembly
  - [Practical Reverse Engineering](https://www.amazon.it/Practical-Reverse-Engineering-Reversing-Obfuscation-ebook/dp/B00IA22R2Y/)
  - [Modern Assembly Language Programming with the ARM Processor](https://www.amazon.it/Modern-Assembly-Language-Programming-Processor/dp/0128036982/)
- Rust
  - [Rust Book](https://doc.rust-lang.org/book/)
- Go
  - [Effective Go](https://golang.org/doc/effective_go.html)
- Python
  - [Learn Python the Hard Way](https://learnpythonthehardway.org/)
- [Think](https://greenteapress.com/wp/)

### Networking

- [Reti di calcolatori e internet. Un approccio top-down](https://www.amazon.it/calcolatori-internet-approccio-top-down-aggiornamento/dp/8891902543/)
- [TCP/IP Illustrated: The Protocols: 1](https://www.amazon.it/TCP-IP-Illustrated-Protocols-1/dp/0321336313/)

### OS

- Windows
  - [Windows Internals, Book 1: User Mode](https://www.amazon.it/Windows-Internals-Book-User-Mode/dp/0735684189/)
  - [Accelerated Windows Malware Analysis with Memory Dumps](https://www.amazon.it/Accelerated-Windows-Malware-Analysis-Memory/dp/1908043865/)
- Linux
  - [Amministrare GNU/Linux](https://www.operedigitali.com/archivio/Amministrare-GNU-Linux-V4.0-web-cover-bis.pdf)
  - [Understanding the Linux Kernel](https://www.amazon.it/Understanding-Linux-Kernel-Daniel-Bovet/dp/0596005652/)
  - [Guida alla Programmazione in Linux](https://gapil.gnulinux.it/)
- macOS
  - [MAC OS X Internals: A Systems Approach](https://www.amazon.it/MAC-OS-Internals-Systems-Approach/dp/0134426541/)

### Misc

- [phrack](https://www.phrack.org)
- [PoC &#124;&#124; GTFO](https://nostarch.com/gtfo)
- [PoC &#124;&#124; GTFO 2](https://nostarch.com/gtfo2)
- [The paradox of choice](http://azeria-labs.com/downloads/Paradox-Of-Choice_Azeria.pdf)

### News

- [HackerNews](https://news.ycombinator.com/) (Quello vero 🙃)

### Blog

- [Google Project0](https://googleprojectzero.blogspot.com/)
- [Orange Tsai](https://blog.orange.tw/)

## Wall of Shame: materiale caldamente sconsigliato
- Qualsiasi distro "per il pentest" (Kali, Parrot, ecc.)
- Gli "Hacker" che sentono il bisogno di scriverlo nella bio di Twitter e/o Linkedin
- Qualsiasi corso che in tre semplici lezioni ti farà diventare un hacker etico
- Hacklog e qualsiasi altro videocorso che promette risultati garantiti in 7 giorni
- Qualsiasi religion war relativa a software, sistemi operativi, ecc. Il radicalismo (in qualsiasi ambito) è il tumore del progresso. Gli estremisti fungono da metastasi.