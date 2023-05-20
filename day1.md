# 10 DAYS INTERNSHIP AT JYOTHI ENGINEERING COLLAGE
# DAY 1
## PROFILE
![img](https://github.com/ameeshilliasmv/intership/blob/main/img/IMG-20220805-WA0031.jpg)
### NAME           : AMEESH ILLIAS MV
### ADDRESS        : MUSLIYAM VEETIL(H),PO BLANGAD ,CHAVAKKAD
### PLACE          : CHAVAKKAD
### CURRENT STATUS : STUDENT
### QUALIFICATION  : DIPLOMA IN ENGINEERING
### COURSE         : ELECTRONICS AND COMMUNICATION ENGINEERING
### USED SITES     : 1) [LINKEDIN-](https://www.linkedin.com/in/ameesh-illias-mv-474b5a275/)
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
```
// C++ code
//
void setup()
{
  pinMode(LED_BUILTIN, OUTPUT);
}

void loop()
{
  digitalWrite(LED_BUILTIN, HIGH);
  delay(500); // Wait for 1000 millisecond(s)
  digitalWrite(LED_BUILTIN, LOW);
  delay(500); // Wait for 1000 millisecond(s)
}
```
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
```
// C++ code
//
void setup()
{
  pinMode(13, OUTPUT);
  pinMode(8,OUTPUT);
}

void loop()
{
  digitalWrite(8, HIGH);
  delay(1000); // Wait for 1000 millisecond(s) 
  digitalWrite(8, LOW);
  delay(1000); // Wait for 1000 millisecond(s)
  digitalWrite(13, HIGH);
  delay(1000); // Wait for 1000 millisecond(s)
  digitalWrite(13, LOW);
  delay(1000); // Wait for 1000 millisecond(s)
}

```
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
# DAY 4
## EXP 1
### SIMPLE CALCULATOR PROGRAM USNG BLOCKLY
#### PROGRAM
![img](https://github.com/ameeshilliasmv/intership/blob/main/img/DAY4-1.png)
#### CODE
```
var num_1, num_2, operator;

// Describe this function...
function packet() {
  for (var count = 0; count < 10; count++) {
    num_1 = Number(window.prompt('enter first number'));
    num_2 = window.prompt('enter the second number');
    operator = window.prompt('enter the operator');
    if (operator == '+') {
      window.alert(num_1 + num_2);
    } else if (operator == '-') {
      window.alert(num_1 - num_2);
    } else if (operator == '*') {
      window.alert(num_1 * num_2);
    } else if (operator == '/') {
      window.alert(num_1 / num_2);
    }
  }
}


packet();
```
# DAY 5 
## INTRODUCING DRONES BY NAVANEETH 3RD YEAR STUDENT OF ROBOTICS 
#### 1- INTRODUSING DRONES
#### 2- EXPLAINED ABOUT DRONES PARTS
#### 3- ALSO SPEAKED ABOUT THE TECHNICAL SPECIFICATION LIKE (THRUST,ALTITUDE,PROPELER DIAMENTION,WEIGHT MANAGEMENT)
![img](https://github.com/ameeshilliasmv/intership/blob/main/img/DAY5.jpg)
#### 4- TO CONFIG THE DRONES WITH SOFTWARE NAMED AS MISSION PLANNER 
## RELATED PROGRAMS ARE SHOWN BELOW
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
## EXP 2
### DISPLAY 0-9 USING 7 SEGMENT 
#### [CLICK HERE TO VIEW IN SITE](https://www.tinkercad.com/things/k6dwPI0tLT2-0-to-9-display/editel)
#### CIRCUIT DIAGRAM
![img](https://github.com/ameeshilliasmv/intership/blob/main/img/DAY5-21.png)
#### SCHEMATIC DIAGRAM 
![img](https://github.com/ameeshilliasmv/intership/blob/main/img/DAY5-22.png)
#### COMPONENTS REQUIRED
![img](https://github.com/ameeshilliasmv/intership/blob/main/img/DAY5-23.png)
#### CODE 
```
// C++ code
//
void setup(){
  pinMode(2, OUTPUT);
  pinMode(3, OUTPUT);
  pinMode(4, OUTPUT);
  pinMode(5, OUTPUT);
    first introduced of the 3d printing
    creating models by the tinkercad 3D modeling
    start with basic shapes
    also cover the previous design's
    created a base and top cover for the flower bottel by using Tinkercad
    then introduced the 3D printer
    also printed a design (duration 19 min)

  pinMode(6, OUTPUT);
  pinMode(7, OUTPUT);
  pinMode(8, OUTPUT);
}
void loop()
{
  digitalWrite(2,LOW);
  digitalWrite(3,LOW);
  digitalWrite(4,LOW);
  digitalWrite(5,LOW);
  digitalWrite(6,LOW);
  digitalWrite(7,LOW);
  digitalWrite(8,HIGH);
  delay(2000);
  digitalWrite(2,HIGH);
  digitalWrite(3,LOW);
  digitalWrite(4,LOW);
  digitalWrite(5,HIGH);
  digitalWrite(6,HIGH);
  digitalWrite(7,HIGH);
  digitalWrite(8,HIGH);
  delay(2000);
  digitalWrite(2,LOW);
  digitalWrite(3,LOW);
  digitalWrite(4,HIGH);
  digitalWrite(5,LOW);
  digitalWrite(6,LOW);
  digitalWrite(7,HIGH);
  digitalWrite(8,LOW);
  delay(2000);
  digitalWrite(2,LOW);
  digitalWrite(3,LOW);
  digitalWrite(4,LOW);
  digitalWrite(5,LOW);
  digitalWrite(6,HIGH);
  digitalWrite(7,HIGH);
  digitalWrite(8,LOW);
  delay(2000);
  digitalWrite(2,HIGH);
  digitalWrite(3,LOW);
  digitalWrite(4,LOW);
  digitalWrite(5,HIGH);
  digitalWrite(6,HIGH);
  digitalWrite(7,LOW);
  digitalWrite(8,LOW);
  delay(2000);
  digitalWrite(2,LOW);
  digitalWrite(3,HIGH);
  digitalWrite(4,LOW);
  digitalWrite(5,LOW);
  digitalWrite(6,HIGH);
  digitalWrite(7,LOW);
  digitalWrite(8,LOW);
  delay(2000);
  digitalWrite(2,LOW);
  digitalWrite(3,HIGH);
  digitalWrite(4,LOW);
  digitalWrite(5,LOW);
  digitalWrite(6,LOW);
  digitalWrite(7,LOW);
  digitalWrite(8,LOW);
  delay(2000);
  digitalWrite(2,LOW);
  digitalWrite(3,LOW);
  digitalWrite(4,LOW);
  digitalWrite(5,HIGH);
  digitalWrite(6,HIGH);
  digitalWrite(7,HIGH);
  digitalWrite(8,HIGH);
  delay(2000);
  digitalWrite(2,LOW);
  digitalWrite(3,LOW);
  digitalWrite(4,LOW);
  digitalWrite(5,LOW);
  digitalWrite(6,LOW);
  digitalWrite(7,LOW);
  digitalWrite(8,LOW);
  delay(2000);
  digitalWrite(2,LOW);
  digitalWrite(3,LOW);
  digitalWrite(4,LOW);
  digitalWrite(5,LOW);
  digitalWrite(6,HIGH);https://www.tinkercad.com/things/9nBmNP5Dtww-0-to-9-display-using-potentiometer/editel
  digitalWrite(7,LOW);
  digitalWrite(8,LOW);
  delay(2000);
} 
```
# DAY 6
## BASICS OF 3D PRINTING CONDUCTED BY 3RD YEAR ROBORTICS STUDENTS

###  1.FIRST INTRODUCED OF THE 3D PRINTING
###  2.CREATING MODELS BY THE TINKERCAD 3D MODELING
###  3.START WITH THE BASIC SHAPES
###  4.ALSO COVER THE PRIVIOUS DESING'S 
###  5.CREATED A BASE AND TOP COVER FOR THE CAR BY USING [TINKERCAD](https://www.tinkercad.com/dashboard)
###  6.THEN INDRODUSED THE 3D PRINTER 
###  7.ALSO PRINTED A DESIGN (DURATION 19 MINUTE)
# DAY 7 
## INTRODUSED THE YESKAWA ARM ROBOT
![IMG](https://github.com/ameeshilliasmv/intership/blob/main/img/DAY%207.jpeg)
###  1.THE INDRODUCTION OF YASKAWA AR1440
### 2. THEN INDRODUSED ABOUT THE ELECTRIC VEHICLE (EV)
# DAY 8
## EXP 1
### DISPLAY 0-9 USING 7 SEGMENT AND POTENTIOMETER
#### [CLICK HERE TO VIEW IN SITE](https://www.tinkercad.com/things/9nBmNP5Dtww-0-to-9-display-using-potentiometer/editel)
#### CIRCUIT DIAGRAM
![img](https://github.com/ameeshilliasmv/intership/blob/main/img/DAY8-11.png)
#### SCHEMATIC DIAGRAM 
![img](https://github.com/ameeshilliasmv/intership/blob/main/img/DAY8-12.png)
#### COMPONENTS REQUIRED 
![img](https://github.com/ameeshilliasmv/intership/blob/main/img/DAY8-13.png)
#### CODE
```
const int potPin=A0;

void setup(){
  Serial.begin(9600);
  pinMode(2, OUTPUT);
  pinMode(3, OUTPUT);
  pinMode(4, OUTPUT);
  pinMode(5, OUTPUT);
  pinMode(6, OUTPUT);
  pinMode(7, OUTPUT);
  pinMode(8, OUTPUT);
}
void loop()
{ 
  int potvalue = analogRead(potPin);
  Serial.println(potvalue);
  digitalWrite(2,LOW);
  digitalWrite(3,LOW);
  digitalWrite(4,LOW);
  digitalWrite(5,LOW);
  digitalWrite(6,LOW);
  digitalWrite(7,LOW);
  digitalWrite(8,HIGH);
  delay(potvalue);
  digitalWrite(2,HIGH);
  digitalWrite(3,LOW);
  digitalWrite(4,LOW);
  digitalWrite(5,HIGH);
  digitalWrite(6,HIGH);
  digitalWrite(7,HIGH);
  digitalWrite(8,HIGH);
  delay(potvalue);
  digitalWrite(2,LOW);
  digitalWrite(3,LOW);
  digitalWrite(4,HIGH);
  digitalWrite(5,LOW);
  digitalWrite(6,LOW);
  digitalWrite(7,HIGH);
  digitalWrite(8,LOW);
  delay(potvalue);
  digitalWrite(2,LOW);
  digitalWrite(3,LOW);
  digitalWrite(4,LOW);
  digitalWrite(5,LOW);
  digitalWrite(6,HIGH);
  digitalWrite(7,HIGH);
  digitalWrite(8,LOW);
  delay(potvalue);
  digitalWrite(2,HIGH);
  digitalWrite(3,LOW);
  digitalWrite(4,LOW);
  digitalWrite(5,HIGH);
  digitalWrite(6,HIGH);
  digitalWrite(7,LOW);
  digitalWrite(8,LOW);
  delay(potvalue);
  digitalWrite(2,LOW);
  digitalWrite(3,HIGH);
  digitalWrite(4,LOW);
  digitalWrite(5,LOW);
  digitalWrite(6,HIGH);
  digitalWrite(7,LOW);
  digitalWrite(8,LOW);
  delay(potvalue);
  digitalWrite(2,LOW);
  digitalWrite(3,HIGH);
  digitalWrite(4,LOW);
  digitalWrite(5,LOW);
  digitalWrite(6,LOW);
  digitalWrite(7,LOW);
  digitalWrite(8,LOW);
  delay(potvalue);
  digitalWrite(2,LOW);
  digitalWrite(3,LOW);
  digitalWrite(4,LOW);
  digitalWrite(5,HIGH);
  digitalWrite(6,HIGH);
  digitalWrite(7,HIGH);
  digitalWrite(8,HIGH);
  delay(potvalue);
  digitalWrite(2,LOW);
  digitalWrite(3,LOW);
  digitalWrite(4,LOW);
  digitalWrite(5,LOW);
  digitalWrite(6,LOW);
  digitalWrite(7,LOW);
  digitalWrite(8,LOW);
  delay(potvalue);
  digitalWrite(2,LOW);
  digitalWrite(3,LOW);
  digitalWrite(4,LOW);
  digitalWrite(5,LOW);
  digitalWrite(6,HIGH);
  digitalWrite(7,LOW);
  digitalWrite(8,LOW);
  delay(potvalue);
} 

```
# DAY 9
## EXP 1
### BLINKING LED USING PUSHBUTTON AND ARDUINO
#### [CLICK HERE TO VIEW IN SITE](https://www.tinkercad.com/things/5kjADqRY583-blinking-led-using-pushbutton/editel)
#### CICUIT DIAGRAM
![img](https://github.com/ameeshilliasmv/intership/blob/main/img/day9-111.png)
#### SCHEMATIC DIAGRAM
![img](https://github.com/ameeshilliasmv/intership/blob/main/img/day9-12.png)
#### COMPONENTS REQUIRED
![img](https://github.com/ameeshilliasmv/intership/blob/main/img/day9-13.png)
#### CODE
```
const int buttonPin = 2;     // the number of the pushbutton pin
const int ledPin =  13;      // the number of the LED pin

// variables will change:
int buttonState = 0;         // variable for reading the pushbutton status

void setup() {
  // initialize the LED pin as an output:
  pinMode(ledPin, OUTPUT);
  // initialize the pushbutton pin as an input:
  pinMode(buttonPin, INPUT);
}

void loop() {
  // read the state of the pushbutton value:
  buttonState = digitalRead(buttonPin);

  // check if the pushbutton is pressed. If it is, the buttonState is HIGH:
  if (buttonState == HIGH) {
    // turn LED on:
    digitalWrite(ledPin, HIGH);
  } else {
    // turn LED off:
    digitalWrite(ledPin, LOW);
  }
}
```
## EXP 2
### SIGNAL LIGHT USING PUSHBUTTON AND ARDUINO
#### [CLICK HERE TO VIEW IN SITE](https://www.tinkercad.com/things/eYFkRNvet8A-signal-light-using-push-button/editel)
#### CIRCUIT DIAGRAM
![img](https://github.com/ameeshilliasmv/intership/blob/main/img/day9-21.png)
#### SCHEMATIC DIAGRAM 
![img](https://github.com/ameeshilliasmv/intership/blob/main/img/daty9-22.png)
#### COMPONENTS REQUIRED
![img](https://github.com/ameeshilliasmv/intership/blob/main/img/day9-23.png)
#### CODE
```
const int buttonPin1 = 2; // the number of the pushbutton pin
const int buttonPin2 = 4;
const int buttonPin3 = 7;
const int greenledPin =  13;      // the number of the LED pin
const int yellowledPin =  12;
const int redledPin =  8;

// variables will change:
int buttonState1 = 0;         // variable for reading the pushbutton status
int buttonState2 = 0; 
int buttonState3 = 0; 

void setup() {
  pinMode(greenledPin, OUTPUT);
  pinMode(buttonPin1, INPUT);
  pinMode(yellowledPin, OUTPUT);
  pinMode(buttonPin2, INPUT);
  pinMode(redledPin, OUTPUT);
  pinMode(buttonPin3, INPUT);
}

void loop() {
  buttonState3 = digitalRead(buttonPin1);

  if (buttonState3 == HIGH) {
    digitalWrite(greenledPin, HIGH);
  } else {
  digitalWrite(greenledPin, LOW);
  }
  buttonState3 = digitalRead(buttonPin2);

  if (buttonState3 == HIGH) {
    digitalWrite(yellowledPin, HIGH);
  } else {
  digitalWrite(yellowledPin, LOW);
  }
  buttonState3 = digitalRead(buttonPin3);

  if (buttonState3 == HIGH) {
    digitalWrite(redledPin, HIGH);
  } else {
  digitalWrite(redledPin, LOW);
  }
}
```
