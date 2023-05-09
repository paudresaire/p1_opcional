# Ejercicios voluntarios de mejora de nota
### Codi exercici voluntari

```cpp
#include <Arduino.h>

const int potPin = 34;
int potValue = 0;

void setup() {
    Serial.begin(115200);
    delay(1000);
}

void loop() {
    potValue = analogRead(potPin);
    Serial.println(potValue);
    delay(500);
}
```

### Imatge Terminal

![Imatge_terminal_p1op](https://github.com/paudresaire/p1_opcional/assets/125595278/9a8bc29b-c130-4467-ae7c-f2711a3a9062)


### Exercici voluntari:
Llegir el valor de un convertidor A/D de entrada; treurel per el port serie i treure el mateix valor per un altre pin
