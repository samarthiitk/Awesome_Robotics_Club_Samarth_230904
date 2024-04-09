FOR TASK 5 PLEASE REFER TO THE LINK 
https://www.tinkercad.com/things/40iKfZSPCsz-daring-bigery-curcan
CODE
// C++ code
#include <LiquidCrystal.h>

// Define potentiometer pin
const int potPin = A0;

// Define obstacle data for both rows
const String obstacleRow1 = "          ***     ****    **         *           ";
const String obstacleRow2 = "               *              *****     **    ***";

void setup() {
  // Set up the LCD's number of columns and rows:
  lcd.begin(16, 2);
}

void loop() {
