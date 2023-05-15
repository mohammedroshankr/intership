# 10 DAYS INTERNSHIP AT JYOTHI ENGINEERING COLLAGE
# DAY 1
## PROFILE
# DAY 2
## EXP 1
### BLINKING LED
#### [CLICK HERE TO VIEW IN SITE](https://www.tinkercad.com/things/01zj30ue382-led-1/editel)
#### CIRCUIT DIAGRAM 
![INMG](https://github.com/ameeshilliasmv/intership/blob/main/img/EXP1.png)
## EXP 2
### BLINKING LED USING PUSHBUTTON 
#### [CLICK HERE TO VIEW IN SITE](https://www.tinkercad.com/things/k6dwPI0tLT2-led-2/editel)
#### CIRCUIT DIAGRAM
![IMG](https://github.com/ameeshilliasmv/intership/blob/main/img/exp%202.png)
# DAY 3
## EXP 1
### AND GATE
#### [CLICK HERE TO VIEW IN SITE](https://www.tinkercad.com/things/k6dwPI0tLT2-and-gate/editel)
#### CIRCUIT DIAGRAM
![img](https://github.com/ameeshilliasmv/intership/blob/main/img/day3-11.png)
#### SCHEMATIC DIAGRAM
![img](https://github.com/ameeshilliasmv/intership/blob/main/img/day3-12.png)
#### COMPONENTS REQUIRED
![img](https://github.com/ameeshilliasmv/intership/blob/main/img/day3-13.png)
## EXP 2
### BLINKING LED USING ARDUINO
#### [CLICK HERE TO VIEW IN SITE](https://www.tinkercad.com/things/k6dwPI0tLT2-blinking-led-using-arduino/editel)
#### CIRCUIT DIAGRAM
![img](https://github.com/ameeshilliasmv/intership/blob/main/img/DAY3-21.png)
#### SCHEMATIC DIAGRAM
![img](https://github.com/ameeshilliasmv/intership/blob/main/img/DAY3-22.png)
#### COMPONENTS REQUIRED
![img](https://github.com/ameeshilliasmv/intership/blob/main/img/DAY3-23.png)
#### CODE
## EXP 3
### DANCING LED USING ARDUINO 
#### [CLICK HERE TO VIEW IN SITE](https://www.tinkercad.com/things/k6dwPI0tLT2-dancing-led-using-arduino/editel)
#### CIRCUIT DIAGRAM
![img](https://github.com/ameeshilliasmv/intership/blob/main/img/DAY3-31.png)
#### SCHEMATIC DIAGRAM
![img](https://github.com/ameeshilliasmv/intership/blob/main/img/DAY3-32.png)
#### COMPONENTS REQUIRED
![img](https://github.com/ameeshilliasmv/intership/blob/main/img/DAY3-33.png)
#### CODE
## EXP 4
### DANCING LED USING ARDUINO 2 
#### [CLICK HERE TO VIEW IN SITE](https://www.tinkercad.com/things/k6dwPI0tLT2-dancing-led-using-arduino-2/editel)
#### CIRCUIT DIAGRAM
![img](https://github.com/ameeshilliasmv/intership/blob/main/img/DAY3-41.png)
#### SCHEMATIC DIAGRAM
![img](https://github.com/ameeshilliasmv/intership/blob/main/img/DAY3-42.png)
#### COMPONENTS REQUIRED
![img](https://github.com/ameeshilliasmv/intership/blob/main/img/DAY3-43.png)
#### CODE
```
// C++ code
//
void setup()
{
  pinMode(13, OUTPUT);
  pinMode(12, OUTPUT);
  pinMode(9, OUTPUT);
  pinMode(8, OUTPUT);
}

void loop()
{
  digitalWrite(13, HIGH);
  delay(20); // Wait for 1000 millisecond(s)
  digitalWrite(12, HIGH);
  delay(20); // Wait for 1000 millisecond(s)
  digitalWrite(8, HIGH);
  delay(20); // Wait for 1000 millisecond(s)
  digitalWrite(7, HIGH);
  delay(20); // Wait for 1000 millisecond(s)
  digitalWrite(7, LOW);
  delay(20); // Wait for 1000 millisecond(s)
  digitalWrite(8, LOW);
  delay(20); // Wait for 1000 millisecond(s)
  digitalWrite(12, LOW);
  delay(20); // Wait for 1000 millisecond(s)
  digitalWrite(13, LOW);
  delay(20); // Wait for 1000 millisecond(s)
}
```
## EXP 5
### SIMPLE 7 SEGMENT DISPLAY
#### [CLICK HERE TO VIEW IN SITE](https://www.tinkercad.com/things/k6dwPI0tLT2-simple-7-segment-display/editel)
#### CIRCUIT DIAGRAM
![img](https://github.com/ameeshilliasmv/intership/blob/main/img/day3-51.png)
#### SCHEMATIC DIAGRAM
![img](https://github.com/ameeshilliasmv/intership/blob/main/img/day3-52.png)
#### COMPONENTS REQUIRED
![img](https://github.com/ameeshilliasmv/intership/blob/main/img/day3-53.png)
# DAY 5 
## EXP 1 
### POTENTIOMETER READING
#### [CLICK HERE VIEW IN SITE](https://www.tinkercad.com/things/k6dwPI0tLT2-POT/editel)
#### CICUIT DIAGRAM 
![img](https://github.com/ameeshilliasmv/intership/blob/main/img/DAY5-11.png)
#### SCHEMATIC DIAGRAM
![img](https://github.com/ameeshilliasmv/intership/blob/main/img/DAY5-12.png)
#### COMPONENTS REQUIRED
![img](https://github.com/ameeshilliasmv/intership/blob/main/img/DAY5-13.png)
#### GRAPH
![img](https://github.com/ameeshilliasmv/intership/blob/main/img/DAY5-14.png)
#### CODE
```
const int potPin=A0;

void setup(){
  Serial.begin(9600);
}
void loop()
{
  int potvalue = analogRead(potPin);
  Serial.println(potvalue);
  delay(1000);
}
```
