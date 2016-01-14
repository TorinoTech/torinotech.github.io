# Torino Tech - torinotech.github.io
### l'aggregatore di tutti gli eventi tech di Torino!

Vai al [Regolamento](#regolamento)

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
  when: 2015-12-10 19:30:00 +1
  free: (campo opzionale) true|false (default: true) (se è richiesta la tessera non è free)
  url: https://url-evento-o-registrazione.com
```

Il titolo del commit sarà anche il testo del Tweet e post Facebook. Esempio di titolo del commit: **31/01: Mio evento X**

Se non sei sicuro puoi comunque testare il sito localmente prima di fare il commit.

## TODO
- [x] Iniziare
- [x] Integrare le modifiche fatte al repo con i social facebook e twitter
- [ ] Convincere le persone a modificare un file su Github per tenere i dati aggiornati
- [x] Differenziare gli eventi gratuiti da quelli a pagamento

### Cosa si intende con eventi tech Open * ?

Eventi che trattano principalmente di tecnologia e utilizzano tecnologie Open Source

### Chi può inserire gli eventi ?

Uno o due membri per gruppo Open * di Torino che hanno fatto richiesta

# Regolamento

*Less is more*

### DEFINE

TorinoTech ha lo scopo di:

- Promuovere gli eventi Open * Tech di Torino e dintorni
- Organizzare propri eventi su tecnologie open trasversali ai vari gruppi, per favorirne la conoscenza e il confronto

Canali ufficiali

- *NEWS*: http://TorinoTech.it con repeater su Facebook / Twitter
- *DISCUSSIONI*: organizzative, aggiunta eventi,.. https://github.com/TorinoTech/torinotech.github.io/issues
- *CHAT*: https://gitter.im/TorinoTech/chat

### CALL

Quando ci sono nell’aria abbastanza talk si apre la fase di CALL. Ovvero ognuno può aprire *fino a 2 issue* del tipo:

```
Titolo: +HashtagTechTopicX Scopri Lorem Ipsum
Testo: Vi parlerò di Hashtag Tech Topic X fun, l’ho usato per fare Y, accenni a pro e limitazioni
```

E si procede subito a bloccare la issue con **Lock conversation**

Le candidature CALL si aprono su: https://github.com/TorinoTech/torinotech.github.io/issues

### VOTE

Finita la fase CALL, si procede al voto feedback. Ovvero **si sbloccano le issue** e chi è interessato all’argomento aggiunge un +1 oppure prova a chiedere al relatore di integrare nel proprio intervento un certo argomento.

**I participants alla issue sono anche i voti**.

Le 4 issue che prendono più voti entrano nel buffer dell’evento TorinoTech. A una settimana dall’evento si chiede la conferma della disponibilità ai relatori e:

- in caso di 3 conferme, abbiamo i 3 talk da 25 min per l’evento
- in caso di 4 conferme il relatore del 4 talk più votato può scegliere di: ritentare alla prossima CALL, farsi ospitare da un * User Group di Torino per una serata singola (se entrambe le parti sono d'accordo)

### EVENT

L’evento. Qualche settimana prima verrà aperto un evento su Eventbrite.
