

Per ricevere lo stato di un pir alimentare il rosso e nero con 12V
mettere arancione su gnd
mettere bianco su ingresso (ha una resistenza esterna)
configurare l'ingresso con:

```binary_sensor:
  - platform: gpio
    pin:
      number: 22
      inverted: False
      mode:
        input: True
        pullup: true```
