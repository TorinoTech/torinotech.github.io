# Torino Tech - torinotech.github.io
### l'aggregatore di tutti gli eventi tech di Torino!

Lo scopo di questo progetto è quello di avere un punto unico, facilmente modificabile e mantenibile dove far sapere i propri eventi a Torino. Puoi seguire gli eventi anche su [Facebook](https://www.facebook.com/TorinoTech/) e [Twitter](https://twitter.com/torinotech) (vengono sincronizzati circa dopo 30min rispetto le modifiche effettuate qui).

## Come aggiungere un evento

Se hai i permessi [clicca qui](https://github.com/TorinoTech/torinotech.github.io/edit/master/events.yml.txt)
e aggiungi l'evento in ordine cronologico (in basso gli eventi più futuri)

Rispetta esattamente questa sintassi YAML altrimenti si spacca tutto (gli spazi sono significativi), puoi **copiare ed incollare** 
questo esempio e modificarlo:

``` yaml
20151210:
  organizer: User Group
  title: (campo opzionale) Tante belle cose
  when: 2015-12-10T13:15:30Z
  free: (campo opzionale) true|false (default: true)
  url: https://url-evento-o-registrazione.com
```

Il titolo del commit sarà anche il testo del Tweet e post Facebook.

Se non sei sicuro puoi comunque testare il sito localmente prima di fare il commit.

## TODO
- [x] Iniziare
- [x] Integrare le modifiche fatte al repo con i social facebook e twitter
- [ ] Convincere le persone a modificare un file su Github per tenere i dati aggiornati
- [ ] Differenziare gli eventi gratuiti da quelli a pagamento
- [x] Differenziare gli eventi gratuiti da quelli a pagamento

### Cosa si intende con eventi tech Open * ?

Eventi che trattano principalmente di tecnologia e utilizzano tecnologie Open Source

### Chi può inserire gli eventi ?

Uno o due membri per gruppo Open * di Torino che hanno fatto richiesta
