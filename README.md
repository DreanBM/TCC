int LEDPin = A0;
int LEDval = 0;

void setup() { Serial.begin(9600);
}

void loop() { LEDval = analogRead(LEDPin);
Serial.println(LEDval);
delay(300); }
