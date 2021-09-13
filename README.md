# Lm35
Pablo Carranza Moreno
float V=0.0;
float T=0.0;
void setup(){
// put your stupcode here, to run once
pinMode(A0, INPUT);
Serial.begin(9600);
}
void loop() {
// put your main code here, to run repeatedly
V= analogRead(A0);
T= ((V*95/1023);
Serial.print("La temperatura es:");
Serial.print(T);
Serial.printin(“°C”);
delay(1000);
}
