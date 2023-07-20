# Eye-matrix
_This code is used in arduino by tinkercad [Link of circuit] (https://www.tinkercad.com/things/eLm2EmjNm1R-eye-matrix/editel?sharecode=-EjmRbUIDhE4S0XYPOWziNKQ4NON5uw0bFzKTrhK3t8)_
const int L1 = 13; 
const int L2 = 12; 
const int L3 = 8; 
const int L4 = 7;  
const int L5 = 4; 

const int L6=  A1;
const int L7=  A2; 
const int L8=  A3; 
const int L9=  A4; 
const int L10=  A5; 

void setup()
{
  pinMode(L1, OUTPUT);  
  pinMode(L2, OUTPUT);
  pinMode(L3, OUTPUT);
  pinMode(L4, OUTPUT);
  pinMode(L5, OUTPUT);
  
  pinMode(L6, OUTPUT);
  pinMode(L7, OUTPUT);
  pinMode(L8, OUTPUT);
  pinMode(L9, OUTPUT);
  pinMode(L10, OUTPUT);
}

void loop()
{
  digitalWrite(L1, HIGH); 
  digitalWrite(L2, HIGH);
  digitalWrite(L3, HIGH);
  digitalWrite(L4, HIGH);
  digitalWrite(L5, HIGH); 
  
  digitalWrite(L6, HIGH); 
  digitalWrite(L7, HIGH);
  digitalWrite(L8, HIGH);
  digitalWrite(L9, HIGH); 
  digitalWrite(L10, HIGH);
  delay(1000);
  
  digitalWrite(L1, LOW); 
  digitalWrite(L2, HIGH);
  digitalWrite(L3, HIGH);
  digitalWrite(L4, HIGH);
  digitalWrite(L5, LOW); 
  
  digitalWrite(L6, LOW); 
  digitalWrite(L7, HIGH);
  digitalWrite(L8, HIGH);
  digitalWrite(L9, HIGH); 
  digitalWrite(L10, LOW);
  delay(500);
}
