# BOOLEAN_FUNCTION_MINIMIZATION

**AIM:**

To implement the given logic function verify its operation in Quartus using Verilog programming.

F1= A’B’C’D’+AC’D’+B’CD’+A’BCD+BC’D 

F2=xy’z+x’y’z+w’xy+wx’y+wxy

**Equipment Required:**

Hardware – PCs, Cyclone II , USB flasher

**Software – Quartus prime**

**Theory**

Boolean Algebra is a branch of algebra that deals with boolean values—true and false. It is fundamental to digital logic design and computer science, providing a mathematical framework for describing logical operations and expressions.

**Procedure**

1.	Type the program in Quartus software.

2.	Compile and run the program.

3.	Generate the RTL schematic and save the logic diagram.

4.	Create nodes for inputs and outputs to generate the timing diagram.

5.	For different input combinations generate the timing diagram.
   
   
** Boolean Minimization :**

F1

![f1 boolian mini](https://github.com/user-attachments/assets/281038e7-4ef1-4a70-9606-c3140725e9d7)


F2

![f2 boolien min](https://github.com/user-attachments/assets/8e069c7e-9dfc-462f-b24f-db5de84488e9)

** TRUTH TABLE **

F1

![f1 boolean](https://github.com/user-attachments/assets/610be2f2-ce77-4728-913e-667d7a1adc83)

F2

![f2 boolean](https://github.com/user-attachments/assets/137026fc-9993-4e14-b59e-49249c475278)


**Program:**

 Program to implement the given logic function and to verify its operations in quartus using Verilog programming. 

Developed by:  DHANUSHKUMAR SIVAKUMAR

RegisterNumber:  24901013


f1

```


module funct1(a,b,c,d,f1);
input a,b,c,d;
output f1;
assign f1=((~b & ~d)|(~a & b & d)|(a & b & ~c));
endmodule

```

**RTL :**

f1

![Screenshot 2024-11-29 143040](https://github.com/user-attachments/assets/e6dce803-5ebe-4e2c-a4d4-8c0fe98aaeaf)


**OUTPUT :**

f1


![Screenshot 2024-11-29 143648](https://github.com/user-attachments/assets/da00320f-1c36-4422-ae0f-58f3add8368f)


**Program:**

f2

```

module funct2(w,x,y,z,f2);
input w,x,y,z;
output f2;
assign f2=((~y & z)|( w & y )|(x & y));
endmodule

```

**RTL :**

f2

![Screenshot 2024-11-29 143434](https://github.com/user-attachments/assets/ba16f251-a745-4b2d-9f6c-76344727b932)


**OUTPUT :**

f2

![Screenshot 2024-11-29 143936](https://github.com/user-attachments/assets/3197226d-b3ee-490d-be3a-d98c42bc3e4e)



**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

