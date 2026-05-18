# sorting-of-numbers
## Aim
To write and execute an Assembly Language Program for sorting data in Ascending and  descending order using 8051 microcontroller on Keil software.
---

## Apparatus Required
- Personal Computer  
- Keil µVision software  
---

## Algorithm(ASCENDING ORDER)
1. Initialize the register **R7** with count (number of elements).  
2. Get the first two elements into two registers.  
3. Compare the two elements:  
   - If the value in register **R0** is lower, exchange **A** and **R0** data.  
   - Otherwise, increment pointer and decrement register **R7**.  
4. Check if **R7 = 0** → if yes, move the register **R0 & A**.  
5. Increment pointer and decrement **R7**.  
6. If **R7 ≠ 0**, repeat from Step 2.  
7. Otherwise, stop the program.  
---

## Program (Ascending order)

<img width="1600" height="900" alt="image" src="https://github.com/user-attachments/assets/c8934a1d-1268-4544-a9b4-df24a9910222" />






## OUTPUT(Ascending order)
<img width="1600" height="900" alt="image" src="https://github.com/user-attachments/assets/a8bc5e3a-6618-435e-a0d2-446f43ce176d" />





## Algorithm(Descending order)
1. Initialize the register **R7** with count.  
2. Get first two elements in two registers.  
3. Compare the two elements of data:  
   - If the value of **R0** register is high, then exchange **A** and **R0** data.  
   - Else, increment pointer and decrement register **R7**.  
4. Check if **R7 = 0**, then move the contents of **R0** and **A**.  
5. Again increment pointer and decrement **R7**.  
6. Check if **R7 = 0**:  
   - If **No**, repeat the process from Step 2.  
   - If **Yes**, stop the program.  
---
## Program (Descending order)

<img width="1600" height="900" alt="image" src="https://github.com/user-attachments/assets/d01ddfa1-0997-4b66-bb63-0a8aee54a281" />






## OUTPUT(Descending order)

<img width="1600" height="900" alt="image" src="https://github.com/user-attachments/assets/5241a5e0-a73c-46d3-be55-b70e4d181a90" />



## RESULT:
Thus the sorting of given data was done using 8051 keil software.

