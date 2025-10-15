# SQUARE AND CUBE OF A NUMBER
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
ORG 00H
MOV R0,#40H
MOV A,@R0
MOV B,A
MUL AB
INC R0
MOV @R0,A
INC R0
MOV @R0,B
END

```

## OUTPUT

<img width="500" height="600" alt="Screenshot 2025-10-15 132611" src="https://github.com/user-attachments/assets/0143847f-647c-4ed3-a922-8e635b14dcad" />

<img width="500" height="300" alt="Screenshot 2025-10-15 132628" src="https://github.com/user-attachments/assets/4c30d8de-e236-4cd1-8d9b-655b781b9e0c" />

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
ORG 00H
MOV R0,#40H
MOV A,@R0
MOV B,A
MUL AB
MOV B,@R0
MUL AB
INC R0
MOV @R0,A
INC R0
MOV @R0,B
END

```


## OUTPUT

<img width="500" height="600" alt="Screenshot 2025-10-15 132158" src="https://github.com/user-attachments/assets/304ff754-adbc-4b95-944c-e2b35cade5f3" />
<img width="500" height="300" alt="Screenshot 2025-10-15 132216" src="https://github.com/user-attachments/assets/24a068e7-028f-48b6-9dd0-e31b3386df31" />



## RESULT
Thus, the cube of the given data is calculated using 8051 Keil.
