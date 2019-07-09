:question: Questo file contiene la spiegazione dei vari campi. Per avere un
template pronto all'uso si veda [README.template.md](README.template.md)
:question:

---

# Badges
I badge comunicano in modo semplice e rapido lo stato del progetto: build
status, ultima versione, stato del packaging sui repository di pacchetti scelti etc.
Per questo motivo è buona prassi dotare i propri README di questi badge in cima
al file.
Tendenzialmente è possibile trovare i badge su
[shields.io](https://shields.io/) dove si possono anche personalizzare.  Altri
si possono trovare all'interno delle interfacce dei servizi utilizzati, come ad
esempio circleci.

Per quanto riguarda `/italia`, alcuni badge sono da inserire in tutti i repo
mentre altri sono opzionali. 
Quelli da inserire sono i seguenti:

```
LICENZA - [![License](https://img.shields.io/github/license/italia/bootstrap-italia.svg)](https://github.com/italia/bootstrap-italia/blob/master/LICENSE)
ISSUES - [![GitHub issues](https://img.shields.io/github/issues/italia/bootstrap-italia.svg)](https://github.com/italia/bootstrap-italia/issues)
SLACK - [![Join the #design channel](https://img.shields.io/badge/Slack%20channel-%23design-blue.svg)](https://developersitalia.slack.com/messages/C7VPAUVB3/)
SLACK - [![Get invited](https://slack.developers.italia.it/badge.svg)](https://slack.developers.italia.it/)
FORUM - [![18app on forum.italia.it](https://img.shields.io/badge/Forum-18app-blue.svg)](https://forum.italia.it/c/18app-carta-docente)
```

Di seguito, invece, ci sono degli esempi di altri badge facoltativi ovviamente
da personalizzare per il proprio caso d'uso:

```
[![Chat on Gitter](https://img.shields.io/gitter/room/italia/bootstrap-italia.svg)](https://gitter.im/bootstrap-Italia)
[![Codacy Badge](https://api.codacy.com/project/badge/Grade/4bfe698a793a4270b9bac004515225a3)](https://www.codacy.com/app/cloudify/italia-app?utm_source=github.com&amp;utm_medium=referral&amp;utm_content=teamdigitale/italia-app&amp;utm_campaign=Badge_Grade)
[![dependencies](https://david-dm.org/teamdigitale/italia-app/status.svg)](https://david-dm.org/teamdigitale/italia-app)
[![CircleCI](https://circleci.com/gh/teamdigitale/italia-app.svg?style=svg)](https://circleci.com/gh/teamdigitale/italia-app)
[![codecov](https://codecov.io/gh/teamdigitale/italia-app/branch/master/graph/badge.svg)](https://codecov.io/gh/teamdigitale/italia-app)
[![Maintainability](https://api.codeclimate.com/v1/badges/d813b789c3a2085bd8f4/maintainability)](https://codeclimate.com/github/teamdigitale/italia-app/maintainability)
[![FOSSA Status](https://app.fossa.io/api/projects/git%2Bgithub.com%2Fteamdigitale%2Fitalia-app.svg?type=shield)](https://app.fossa.io/projects/git%2Bgithub.com%2Fteamdigitale%2Fitalia-app?ref=badge_shield)
https://img.shields.io/badge/publiccode%20compliant-%E2%9C%94-blue.svg?logo=data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAA4AAAAOCAMAAAAolt3jAAAAIGNIUk0AAHomAACAhAAA+gAAAIDoAAB1MAAA6mAAADqYAAAXcJy6UTwAAAFxUExURQBmzABmzABmzABkywBkywBmzABmzABmzApszj2L2CyA1QBmzABmzABmzABlzABkywBlzABmzABkywBkywBkyyZ91OXv+qTH7AJlzABlzABmzABlzBJx0Hiu5EyU2wBmzECM2Wil4RRy0CZ91Orz+8/i9W2n4h950gBlzABkyzuJ2Pb6/bbT8AVpzZbA6vX5/TOE1iR80+jx+vn8/uXv+kKO2QBjywBlzA9vz3Cp4kmS2wBlzJbA6vX5/TOE1uvz+7LR8Ch+1AttzgBmzABmzABkywBkywBlzJbA6uz0+6PH7AFlzABmzABmzABlzJbA6jOE1iR70+z0+6TH7AFky5bA6jOF1hx30uPu+c/i9V+f3xl10QBlzABmzABlzIi459/s+TCD1gVpzZ7F7Pb6/evz+0CM2QBjywBmzBd00SV80whrzgBlzBFwzzqJ2DaG1wttzgBmzABmzABlzABlzABmzABmzABkywBkywBmzP///7f5b6EAAAABYktHRHo41YVqAAAAB3RJTUUH4wUWBTMYAFp7MgAAAF50RVh0UmF3IHByb2ZpbGUgdHlwZSBpcHRjAAppcHRjCiAgICAgIDI4CjM4NDI0OTRkMDQwNDAwMDAwMDAwMDAwZjFjMDI2ZTAwMDM1MjQ2NDcxYzAyMDAwMDAyMDAwNDAwCmCaPZ4AAAClSURBVAjXY2DAChiZmFlYwSw2EMHOwcnFzcPAwMvHLyAoJCwiKiYuISnFIC0jKyevoKikrKKqpq7BoKmlraOrp29gaGRsYmrGYG5haWVtY2tnaO/g6OTMwOvi6ubuAeR6enn7+IJMZfXztw0IDAoOkZaCcEP1w8IjIqOiY0Dc2Lj4hMSk5JTUtHSwOzIys7JzcvPyCwrB7ioqLiktMy+vqPRFczoAaG4fQ5lQVPsAAAAldEVYdGRhdGU6Y3JlYXRlADIwMTktMDUtMjJUMDU6NTE6MjQtMDQ6MDDV7wZaAAAAJXRFWHRkYXRlOm1vZGlmeQAyMDE5LTA1LTIyVDA1OjUxOjI0LTA0OjAwpLK+5gAAAABJRU5ErkJggg==
```

# Annunci / Status del progetto
E' importante comunicare all'utente il prima possibile quale sia lo stato
attuale del progetto. Se, ad esempio, il progetto non dovesse più essere
mantenuto o in versione alpha è doveroso comunicarlo al visitatore. 

# Titolo
Il titolo del repository.

> Sottotitolo / Slogan / Descrizione breve

## Multilanguage
E' buona norma avere una versione del README anche in lingua inglese. 
Per notificare la presenza di un altro file chiamato ad esempio `README.EN.md`,
usare questa formula:

```
*Read this in other languages: [English](README.EN.md).*
```

## Immagini e GIF
Siccome un'immagine vale più di mille parole, è buona norma inserire degli
screenshot dell'applicativo in modo tale da comunicare visivamente il layout
e/o alcune funzionalità del sito. 
E' anche possibile creare GIF animate che possono essere molto esplicative. Per
farlo si può utilizzare ad esempio [Recordit](http://recordit.co/).


# Indice

Per avere un indice, è possibile usare questo formato:

```
- [Come iniziare](#come-iniziare)
- [Segnalazione bug e richieste](#segnalazione-bug-e-richieste-di-aiuto)
- [Come contribuire](#come-contribuire)
- [Licenze software dei componenti di terze parti](#licenze-software-dei-componenti-di-terze-parti)
```

# Come iniziare

Questa sezione contiene una serie di informazioni utili a chi vuole *usare* il
software (lato utente). 
Per le informazioni su come contribuire e quindi ad esempio come fare il setup
dell'ambiente di sviluppo, i dev tool da utilizzare etc. ci sarà una sezione
dedicata più sotto.

## Come installare

Per permettere ad un utente di fruire del software è necessario fornire alcune
informazioni relative alle modalità di installazione del software. 

## Documentazione

E' possibile includere nel README parte della documentazione ma è buona norma
inserire per lo più link a risorse esterne contenenti la documentazione estesa
vera e propria. Questo per rendere questo file il più scorrevole possibile
e non appesantirlo con informazioni che potrebbero stare altrove. 

---

# Come contribuire

Questa sezione contiene le informazioni necessarie a chi vuole contribuire
attivamente al codice sorgente contenuto nel repository. 
Le informazioni devono servire sia ad eseguire il setup dei tool di sviluppo
necessari che per quanto riguarda le configurazioni di dev. 

NB: è necessario spiegare anche la struttura delle directory e dei branches.

## Community

Per stimolare la creazione di una vera e propria community intorno al progetto
è possibile utilizzare degli strumenti di comunicazione, quali ad esempio
[Gitter](https://gitter.im) o [Slack](https://slack.com). 

## Responsible Disclosure

Questa sezione è importante per comunicare ai contributor quali policy di
responsible disclosure sono state adottate a livello di community. Per non
ridondare le informazioni è anche possibile inserire un link alla policy
adottata a livello di progetto.

### Code of conduct

Il Code of Conduct regolamenta le interazioni tra i vari attori di un
repository. Tendenzialmente è bene che questo incoraggi qualsiasi tipo di
contribuzione. Esistono diversi template già preimpostati che, dopo attenta
analisi, si possono incorporare nel proprio progetto. Il Team per la
Trasformazione Digitale adotta [questo Codice](https://www.contributor-covenant.org/). 

### Segnalazione bug e richieste di aiuto

E' importante comunicare all'utente quali sono gli strumenti utili per
comunicare con il maintainer e gli sviluppatori. In questa sezione è bene
indicare lo strumento `Issue` di GitHub. Per guidare l'utente nella
compilazione di un issue report, è possibile anche creare un template. Per
farlo, è necessario creare un file denominato `ISSUE_TEMPLATE.md` e inserirlo
nella root del repo (o nella cartella `.github`). Tale template verrà
automaticamente importato durante la creazione di una nuova issue. Siccome ogni
progetto ha esigenze diverse, è difficile realizzare un template comune
a tutti. Un esempio è presente [qui](ISSUE_TEMPLATE.md).

Più esempi sono disponibili in [questo
repo](https://github.com/stevemao/github-issue-templates).

GitHub mette a disposizione uno strumento di "guida" per la creazione di questo
template, si veda [questo
link](https://help.github.com/en/articles/creating-issue-templates-for-your-repository).

### Semantic Versioning

Il versionamento del proprio software è una fase delicata che deve
possibilmente essere quanto più documentata possibile. Cambiare la modalità di
versionamento di un software in corso d'opera può non solo confondere gli
utenti ma potenzialmente potrebbe causare problemi ad altri software che
inseriscono questo progetto come dipendenza. 
Esistono diverse modalità di versionamento, una tra le più utilizzate
è [Semantic Versioning](https://semver.org/). 

# Manutenzione 

La sezione `manutenzione` permette di identificare rapidamente se attualmente il
software è manutenuto o meno. In caso positivo, è possibile indicare i nomi
e, eventualmente, un metodo di contatto.

---

# Licenza 

La sezione di licensing si divide in diverse parti. Innanzitutto deve essere
chiaramente indicata la licenza scelta per questo repository. Dopodichè
è necessario indicare gli autori e chi detiene il copyright.

## Licenza generale 
Di norma, la licenza è indicata in modo abbreviato nel file README in quanto la
sua versione estesa è presente in un file dedicato chiamato `LICENSE.md`
presente, di norma, nella root del repository.  Per avere un aiuto nel percorso
di scelta di una licenza è possibile visitare
[Choose a License](https://choosealicense.com/).
Per i progetti del Team Digitale le licenze preferibili sono
[queste](https://github.com/teamdigitale/licenses).

## Autori e Copyright

La sezione dedicata agli autori è altresì importante in quanto contiene i nomi
e i contatti (email) degli autori. 
Non bisogna dimenticare di esplicitare chi detiene il copyright e in quale
parte. 
Per indicare una community o un gruppo di sviluppatori è anche possibile usare
la formulazione `Linus Torvalds and all Linux contributors`.

## Licenze software dei componenti di terze parti

Nel caso in cui il software utilizzasse componenti di terze parti, bisogna
indicarne le licenze dei singoli. Questa operazione potrebbe essere
particolarmente lunga o laboriosa da riportare e quindi è possibile avvalersi
di alcuni tool automatici di supporto. 
Un esempio di questi tool può essere [FOSSA](https://fossa.com/pricing/). 
