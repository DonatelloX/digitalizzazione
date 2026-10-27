# digitalCUP - rilasci

Repository di servizio di digitalCUP: contiene solo file firmati e cifrati.

- `licenze/` - abilitazioni dei PC (firmate Ed25519, senza nomi ne' codici macchina)
- `aggiornamento.json` - ultima versione pubblicata (firmata)
- Releases - pacchetti del programma, cifrati AES-256-GCM

Gestito con `strumenti/licenze.py` e `strumenti/pubblica_versione.py`.
