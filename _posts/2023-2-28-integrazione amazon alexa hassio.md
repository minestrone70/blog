Mi ha creato problemi con google che ha pensato si trattasse di phishing. Durante la registrazione, infatti, ha aperto la login di amazon alexa, facendola comparire come se fosse prodotta dal mio server locale. 
Ho chiesto una revisione a google search console, che spero che venga accolta. Ora la app non funziona

comunque la integrazione funziona:
```
service: notify.alexa_media
data:
  data:
    type: tts
  message: Rilevata presenza non riconosciuta.
  target: media_player.xxx
```
