# Square-Cube-of-a-number-using-8051
# 8051 Square  Program

## AIM
To write and execute an Assembly language program for finding the square of a given data using 8051 microcontroller in Keil software.

## APPARATUS REQUIRED
- Personal computer
- Keil μVision IDE

## ALGORITHM
1. Enter the Assembly language program.
2. Provide the input value to Port 0 (P0).
3. Execute the program.
4. The output square value is stored in Port 2 (P2).

## PROGRAM
```
MOV A,P0
MOV R0,A
MOV B,R0
MUL AB
MOV P2,A
END








```

## OUTPUT
<img width="801" height="536" alt="image" src="https://github.com/user-attachments/assets/fe460077-862e-41e2-82fa-6a0225368f00" />
<img width="616" height="351" alt="image" src="https://github.com/user-attachments/assets/4d18baa0-7dae-4123-be6e-5c580cf111da" />


## RESULT
Thus, the square of the given data is calculated using 8051 Keil.

# 8051 Cube  Program

## AIM
To write and execute an Assembly language program for finding the cube of a given data using 8051 microcontroller in Keil software.

## APPARATUS REQUIRED
- Personal computer
- Keil μVision IDE

## ALGORITHM
1. Enter the Assembly language program.
2. Provide the input value.
3. Execute the program.
4. The output cube value is stored in a memory location.

## PROGRAM
```
MOV A, P0
MOV B, A
MUL AB
MOV R0, A
MOV A, R0
MOV B, P0
MUL AB
MOV P2, A
END







```


## OUTPUT
<img width="645" height="461" alt="image" src="https://github.com/user-attachments/assets/5ce72f7f-f362-403d-8e8e-e5ac7f7e9f02" />
<img width="639" height="336" alt="image" src="https://github.com/user-attachments/assets/16151d27-4d50-4426-a219-244d48e5aaa9" />

## RESULT
Thus, the cube of the given data is calculated using 8051 Keil.


