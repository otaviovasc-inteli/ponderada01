# Parte 1: Blink Led Interno

Entrega Parte 1: em seu GitHub pessoal (usando sua conta com email Inteli), inserir screenshots de sua tela com o IDE e seu código, além de uma fotografia que demonstre seu Arduino ligado no computador e o seu led aceso. Você também poderá enviar um vídeo que evidencie esse funcionamento.


```c
void setup() {
  // initialize digital 10th pin as an output.
  pinMode(LED_BUILTIN, OUTPUT);
}

// the loop function runs over and over again forever
void loop() {
  digitalWrite(LED_BUILTIN, HIGH);  // turn the LED on (HIGH is the voltage level)
  delay(200);                      // wait for a .2 second
  digitalWrite(LED_BUILTIN, LOW);   // turn the LED off by making the voltage LOW
  delay(200);                      // wait for a .2 second
}
```

# Parte 2: Blink Led externo

```c
void setup() {
  // initialize digital 10th pin as an output.
  pinMode(10, OUTPUT);
}

// the loop function runs over and over again forever
void loop() {
  digitalWrite(10, HIGH);  // turn the LED on (HIGH is the voltage level)
  delay(200);                      // wait for a .2 second
  digitalWrite(10, LOW);   // turn the LED off by making the voltage LOW
  delay(200);                      // wait for a .2 second
}
```

Link do tinkercard: https://www.tinkercad.com/things/kQgh7S9sUx9/editel
