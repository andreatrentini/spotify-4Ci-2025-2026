# spotify-4Ci-2025-2026

## Requisiti
- nodejs: > 20.19
- npm: OK

## Installazione di angular cli /Command Line Interface
```bash
npm install -g @angular/cli
```
> ATTENZIONE: ricordarsi -g: angular va installato in global mode. Significa che angular non viene installato all'interno di un progetto node, ma viene installato sul PC: si avrà a disposizione il comando ng con il quale gestire tutte le operazioni di angular:
> - creare componenti, servizi, classi, interfacce, ecc
> - avviare il server di sviluppo per vedere l'applicazione in esecuzione
> - eseguire il build dell'epplicazione
> - ecc

## Creare l'applicazione
```bash
ng new nome-applicazione
```
In angular quando si usa **ng** se i nomi degli elementi creati (applicazione, componenti, ecc...) sono formati da più parole si separano le parole stesse con il trattino.
> ATTENZIONE: questo non vale in typescript per il nome delle variabili, dove il trattino rappresenta la sottrazione!
Scelta del stylesheet system: c'è libertà di scelta. Nel caso di applicazioni non particolarmente complesse, CSS è un'ottima scelta.

> SSR: Se si attiva la funzionalità SSR, l'applicazione deve essere ospitata su un server NODE: le pagine vengono elaborate dal server prima di essere inviate al client. Il programmatore deve decidere dove viene eseguito il codice nel template HTML.
