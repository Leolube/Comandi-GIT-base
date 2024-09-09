# Istruzioni GIT for dummies

## Introduzione 

In questo documento verranno illustrate le principali istruzioni di GIT per fare il primo commit.

## Comandi

I comandi che abbiamo illustrato sono: 
- git init
- git add "**<nome_file>**"
- git commit -. "*messaggio*"
- git push
- git status

## Descrizione dei comandi

Per inizializzare una repository devo usare il comando

```Powershell
git init
```
Successivamente, per visualizzare lo status di una repository posso usare:
```Powershell
git status
```

Poi, per aggiungere alla **staging area** un file userò il comando 
```Powershell
git add .
```
Per effettuare un commit userò il comando 
```Powershell
git git commit -m "Messaggio"
```

Per effettuare l'invio sulla repository online userò il comando
```Powershell
git push
```