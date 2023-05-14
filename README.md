# Experiment--02-Implementation-of-combinational-logic
Implementation of combinational logic gates
 
## AIM:
To implement the given logic function verify its operation in Quartus using Verilog programming.
 F1= A’B’C’D’+AC’D’+B’CD’+A’BCD+BC’D
F2=xy’z+x’y’z+w’xy+wx’y+wxy
 
 
 
## Equipments Required:
1.Hardware – PCs, Cyclone II , USB flasher 2.Software – Quartus prime




## Theory
Logic gates are electronic circuits which perform logical functions on one or more inputs to produce one output.
 

## Logic Diagram
Logic Diagram:
Screenshot 2023-04-20 210203
## Procedure
1.Create a project with required entities.

2.Create a module along with respective file name.

3.Run the respective programs for the given boolean equations.

4.Run the module and get the respective RTL outputs.

5.Create university program(VWF) for getting timing diagram.

6.Give the respective inputs for timing diagram and obtain the results.
## Program:
/*
Program to implement the given logic function and to verify its operations in quartus using Verilog programming.
Developed by:Subasini.s
RegisterNumber: 212222240106
~~~
module expf1(a,b,c,d,f1);
input a,b,c,d;
output f1;
assign f1=((~b & d) | (~a & b & d) | (a & b &~c));
endmodule

module exp2(w,x,y,z,f2);
input w,x,y,z;
output f2;
assign f2=((x & y) | (~y & z) | (w & y));
endmodule 
*/
~~~

## Output:
## RTL realization

![image](https://user-images.githubusercontent.com/119404951/233849455-e805ad81-25d3-4bc7-952a-37bb6954117c.png)

![image](https://user-images.githubusercontent.com/119404951/233849296-d46333f5-13a5-4bca-a3c5-eb6cd9609840.png)


## Timing Diagram
![image](https://user-images.githubusercontent.com/119404951/233848908-87ae25fc-a08e-4d35-adb9-e0822efe15f7.png)
![image](https://user-images.githubusercontent.com/119404951/233848939-3207fe98-b25a-4f39-b113-de24bdc09f69.png)
#Time Table
![image](https://user-images.githubusercontent.com/119404951/233849130-2a981470-0577-4d5e-a97b-9a32da4eec72.png)
![image](https://user-images.githubusercontent.com/119404951/233849305-0ba2c996-268d-40c2-9d9b-1371565d17d5.png)



## Result:
Thus the given logic functions are implemented using  and their operations are verified using Verilog programming.
