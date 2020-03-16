# MicroProcessor-Lab

This repository is a part of subject **MicroProcessor-Lab** (2nd-Year 2nd-Semester Robotics and AI, KMITL), academic year 2019

![alt text](https://github.com/earthsaharat/MicroProcessor-Lab/blob/master/IMG_1421.JPG "Arduino")

## Content

There are topics of my works

### Read/Write digital pin with Register 
**X** is port name e.g A,B,C,D
- **DDRX** = pinMode

  ```c++
  // set pin4 of PortD as Input
  DDRD  = 0b00010000;
  ```

- **PORTX** = digitalWrite

  ```c++
  // set status of pin4 of PortD as ON
  PORTD  = 0b00010000;
  ```
  
- **PINX** = digitalRead

  ```c++
  // check status of pin0 of PortB
  if(PINB & 0b00000001){
  }
  ```

*Saharat Saengsawang 61011090*
