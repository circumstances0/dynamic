1.Write a Code to blink 8 LEDs connected to core 2 of microcontroller 8051


#include<reg51.h>

void delay(unsigned int y)
{
    unsigned int i;
    for(i=0;i<=y;i++)
    {}
}
void main()
{
    while(1)
    {
        
        P2=0x80;
        
        delay(100000);
P2=0x40;
        delay(100000);
        P2=0x20;
        delay(100000);
        P2=0x10;
        delay(100000);
        
        P2=0x08;  //on
        delay(100000);
        P2=0x04;
        delay(100000);
        P2=0x02;
        delay(100000);
        P2=0x01;
        delay(100000);
    }
}


2.Write a code to create a running tick √ from left to right and right to left. 
Code of Left to Right

#include<reg51.h>
void delay(unsigned int y)
{
    unsigned int i;
    for(i=0;i<=y;i++)
    {}
}
void main()
{
    while(1)
    {
        
        P2=0x80;
        
        delay(100000);
        P2=0x40;
        delay(100000);
        P2=0x20;
        delay(100000);
        P2=0x10;
        delay(100000);
        
        P2=0x08;  //on
        delay(100000);
        P2=0x04;
        delay(100000);
        P2=0x02;
        delay(100000);
        P2=0x01;
        delay(100000);
    }
}
  
  Code of Right to Left
  
  
#include<reg51.h>
void delay(unsigned int y)
{
    unsigned int i;
    for(i=0;i<=y;i++)
    {}
}
void main()
{
    while(1)
    {
        
        P2=0x01;
        delay(100000);
        P2=0x02;
        delay(100000);
        P2=0x04;
        delay(100000);
        P2=0x08;
        delay(100000);
        
        P2=0x10;  //on
        delay(100000);
        P2=0x20;
        delay(100000);
        P2=0x40;
        delay(100000);
        P2=0x80;
        delay(100000);
    }
}


3.Write a code to create a binary counter to count binary values from 00 to FF H.

Code 
 
#include<reg51.h>
void delay(unsigned int x)
{
unsigned int i;
for(i=0;i<=x;i++)
{}
}
void main()
{
unsigned int j;
while(1)
for(j=0;j<=255;j++)
{
P2=j;
delay(999999999);
delay(999999999);
delay(999999999);
delay(999999999);
delay(999999999);
delay(999999999);
delay(999999999);
delay(999999999);
delay(999999999);
}
}




4.Write a code to generate a square wave on port of microcontroller.  

#include<reg52.h>
void delay (unsigned int y)
{
unsigned int i;
for(i=0;i<y;i++)
{}
}
void main()
{
while(1)
{
P1=0x00; 
delay (1000);
P1=0xFF; 
delay (1000);
}
}


5.Write a code to generate a triangular wave on port  of microcontroller. 


#include<reg51.h>       
void main()  
{  
int j;  
while(1)  
{  
for(j=0;j<256;j++)  
{  
P0=j;  
}  
for(j=255;j>0;j=j-2)  
{  
P0=j;  
}  
}  
}


5.Write a code to generate a sine wave on port 1 of microcontroller. 
#include<reg51.h>
int main()
{
int j;
int c[37]={128,150,172,192,210,226,239,248,254,255,254,248,239,226,210,192,172,150,128,106,84,64,46,30,17,8,2,0,2,8,17,30,46,64,84,106,128};
while(1)
{
for(j=0;j<36;j++)
{
P1=c[j];
}
P1=128;
}
}    


Write a code to blink tick √ of port 2 of 8051 ON and OFF with delay of 1 ms using on board timer delay. 

#include<reg51.h>
void delay()
{
TMOD=0x01;
TH0=0xFC;
TL0=0x66;
TR0=1;
while(TF0==0);
TR0=0;
TF0=0;
}
void main()
{
while(1)
{
     P2=0x00;
     delay();
     P2=0xFF;
     delay();		
  }	
}


Output: Paste the Screenshot / Picture of the Output. 

 

 

Write a code to create a binary counter to count binary values from 00 to FF H using on board timer delay.
#include<reg51.h>
void delay()
{
TMOD=0x01;
TH0=0xEE;
TL0=0x00;
TR0=1;
while(TF0==0);
TR0=0;
TF0=0;
}
void main()
{
while(1)
{
     P2=0x00;
     delay();
     P2=0xFF;
     delay();		
  }	
}


Output: Paste the Screenshot / Picture of the Output of the Circuit

 


 


Write a code to blink on board LED of Arduino UNO with delay of 2 ms and 5 ms.  

Code 2 ms 
void setup() {
  // put your setup code here, to run once:
pinMode(13,OUTPUT);
}


void loop() {
  // put your main code here, to run repeatedly:
digitalWrite(13,HIGH);
delay(2000);
digitalWrite(13,LOW);
delay(2000);
}

 Code 5 ms

void setup() {
  // put your setup code here, to run once:
pinMode(13,OUTPUT);
}


void loop() {
  // put your main code here, to run repeatedly:
digitalWrite(13,HIGH);
delay(5000);
digitalWrite(13,LOW);
delay(5000);
}



Output: Paste the Screenshot / Picture of the Output. 

Output 2 ms
 


Output 5 ms

 

Interface external LED with Arduino UNO and write a code to blink LED. 
void setup() {
  // put your setup code here, to run once:
pinMode(13,OUTPUT);
}


void loop() {
  // put your main code here, to run repeatedly:
digitalWrite(13,HIGH);
delay(5000);
digitalWrite(13,LOW);
delay(5000);
}




Output: Paste the Screenshot / Picture of the Output of the Circuit
 




Interface external LED with Arduino UNO and write a code to change the intensity of LED from zero to maximum and maximum to zero gradually. 

Code

void setup() {
  
  // put your setup code here, to run once:
pinMode(3,OUTPUT);



}


void loop() {
  // put your main code here, to run repeatedly:
analogWrite(3,0);
delay(1000);
analogWrite(3,50);
delay(1000);
analogWrite(3,100);
delay(1000);
analogWrite(3,150);
delay(1000);
analogWrite(3,200);
delay(1000);
analogWrite(3,255);
delay(1000);


analogWrite(3,255);
delay(1000);
analogWrite(3,200);
delay(1000);
analogWrite(3,150);
delay(1000);
analogWrite(3,100);
delay(1000);
analogWrite(3,50);
delay(1000);
analogWrite(3,0);
delay(1000);
}
 


Output: Paste the Screenshot / Picture of the Output of the Circuit

 













Write a code to interface RGB LED with Arduino and generate RGB colours with delay of 500ms.  

Program:
const int R = 3;
const int G = 5;
const int B = 6;
void setup()
{
  pinMode(R, OUTPUT);
  pinMode(G, OUTPUT);
  pinMode(B, OUTPUT);
}
void loop()
{
  digitalWrite(R, HIGH);
  delay(500); // Wait for 500 millisecond(s)
  digitalWrite(R, LOW);
  delay(500); // Wait for 500 millisecond(s)
  digitalWrite(G, HIGH);
  delay(500); // Wait for 500 millisecond(s)
  digitalWrite(G, LOW);
  delay(500); // Wait for 500 millisecond(s)
  digitalWrite(B, HIGH);
      delay(500); // Wait for 500 millisecond(s)
  digitalWrite(B, LOW);
  delay(500); // Wait for 500 millisecond(s)
}
 


Output: Paste the Screenshot / Picture of the Output. 
Red
 

Green
 

Blue
 



Write a code to generate all the colours of RGB model shown below using tricolour LED. 
  
Program 
const int R = 3;
const int G = 5;
const int B = 6;
void setup()
{
  pinMode(R, OUTPUT);
  pinMode(G, OUTPUT);
  pinMode(B, OUTPUT);
}
void loop() {
  RGB_color(255, 0, 0); // Red
  delay(1000);
  RGB_color(0, 255, 0); // Green
  delay(1000);
  RGB_color(0, 0, 255); // Blue
  delay(1000);
  RGB_color(255, 255, 125); // Raspberry
  delay(1000);
  RGB_color(0, 255, 255); // Cyan
  delay(1000);
  RGB_color(255, 0, 255); // Magenta
  delay(1000);
  RGB_color(255, 255, 0); // Yellow
  delay(1000);
  RGB_color(255, 255, 255); // White
  delay(1000);
}
void RGB_color(int redValue, int greenValue, int blueValue)
 {
  analogWrite(R, redValue);
  analogWrite(G, greenValue);
  analogWrite(B, blueValue);
}

Output: Paste the Screenshot / Picture of the Output of the Circuit
 





Write a code to generate a traffic signal using RGB LED such as Red light will be ON for 6 seconds, then yellow light will be ON for 3 seconds and green light will be ON for 5 seconds. 
Program

const int R = 3;
const int G = 5;
const int B = 6;
void setup()
{
  pinMode(R, OUTPUT);
  pinMode(G, OUTPUT);
  pinMode(B, OUTPUT);
}
void loop() {
  RGB_color(255, 0, 0); // Red
  delay(6000);
   RGB_color(255, 100, 0); // Yellow
  delay(3000);
  RGB_color(0, 255, 0); // Green
  delay(5000);
}
void RGB_color(int redValue, int greenValue, int blueValue)
 {
  analogWrite(R, redValue);
  analogWrite(G, greenValue);
  analogWrite(B, blueValue);
}

Output: Paste the Screenshot / Picture of the Output of the Circuit

 

 



 









Write a code to interface RGB LED with Arduino and generate RGB colours with delay of 500ms.  

Program:
const int R = 3;
const int G = 5;
const int B = 6;
void setup()
{
  pinMode(R, OUTPUT);
  pinMode(G, OUTPUT);
  pinMode(B, OUTPUT);
}



void loop()
{
  digitalWrite(R, HIGH);
  delay(500); // Wait for 500 millisecond(s)
  digitalWrite(R, LOW);
  digitalWrite(G, HIGH);
  delay(500); // Wait for 500 millisecond(s)
  digitalWrite(G, LOW);
  digitalWrite(B, HIGH);
      delay(500); // Wait for 500 millisecond(s)
  digitalWrite(B, LOW);
}









Output: Paste the Screenshot / Picture of the Output. 

RED:
 

GREEN:
 
BLUE:
 




Write a code to generate all the colours of RGB model shown below using tricolour LED. 
  

PROGRAM:
const int R = 3;
const int G = 5;
const int B = 6;
void setup()
{
  pinMode(R, OUTPUT);
  pinMode(G, OUTPUT);
  pinMode(B, OUTPUT);
}



void loop() {
  RGB_color(255, 0, 0); // Red
  delay(1000);
  RGB_color(0, 255, 0); // Green
  delay(1000);
  RGB_color(0, 0, 255); // Blue
  delay(1000);
  RGB_color(255, 255, 125); // Raspberry
  delay(1000);
  RGB_color(0, 255, 255); // Cyan
  delay(1000);
  RGB_color(255, 0, 255); // Magenta
  delay(1000);
  RGB_color(255, 255, 0); // Yellow
  delay(1000);
  RGB_color(255, 255, 255); // White
  delay(1000);
}
void RGB_color(int redValue, int greenValue, int blueValue)
 {
  analogWrite(R, redValue);
  analogWrite(G, greenValue);
  analogWrite(B, blueValue);
}









Output: Paste the Screenshot / Picture of the Output of the Circuit

 








Write a code to generate a traffic signal using RGB LED such as Red light will be ON for 6 seconds, then yellow light will be ON for 3 seconds and green light will be ON for 5 seconds. 

PROGRAM:
const int R = 3;
const int G = 5;
const int B = 6;
void setup()
{
  pinMode(R, OUTPUT);
  pinMode(G, OUTPUT);
  pinMode(B, OUTPUT);
}



void loop() {
  RGB_color(255, 0, 0); // Red
  delay(6000);
   RGB_color(255, 100, 0); // Yellow
  delay(3000);
  RGB_color(0, 255, 0); // Green
  delay(5000);
}
void RGB_color(int redValue, int greenValue, int blueValue)
 {
  analogWrite(R, redValue);
  analogWrite(G, greenValue);
  analogWrite(B, blueValue);
}












