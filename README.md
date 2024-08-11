Name:GUBBALA NAGA VENKATA SAI CHARAN
Company:CODETECH IT SOLUTIONS
ID:CT4VLSI3592
Domain:VLSI
Duration:july to August

OVERVIEW OF THE PROJECT:-
Project:FLOATING POINT UNIT DESIGN

![floating unit2](https://github.com/user-attachments/assets/86391d1c-d068-43b9-a434-ed272d49c0ca)
The architecture of the fused add-subtract unit. It is derived from the floating-point add unit. The exponent difference, significant shift and exponent adjustment functions can be performed once with a single set the architecture of the fused add-subtract unit, 
exponent carries 8 bits it represents both positive and negative. Floating point numbers are of four types of exceptions. They are Overflow, Underflow, Division by zero, Invalid operation.
1. Floating point fused Add-Subtract
unit Computer Architecture of Floating point fused add subtract unit
The architecture of the fused add-subtract unit. It is derived from the floating-point add unit. The exponent difference, significant shift and exponent adjustment functions can be performed once with a single set shows the architecture of the fused add-subtract unit, the blocks with white background are the same blocks used for a single floating-point add operation. The blocks with green background are additional blocks used to perform the subtract operation, and the
blocks with yellow background are similar to the floating point add blocks, but with extended
functionality to calculate the sign and exponent for the new subtract operation. It detects the effective operation based on the signs of the two operands and the intended operation. It also generates guard and pre-sticky bits that aid in the proper rounding of the final results. In a parallel conventional implementation of the fused add-subtract such as that two floating-point adders are used to perform the operation. This approach is fast, however, the area and power overhead is large because two floating point add/subtract units are used.

![floating unit](https://github.com/user-attachments/assets/d4c165ac-a006-4647-b0cd-0ff810b81133)
The architecture of the fused dot-product unit. It is derived from the floating-point add unit. The exponent difference, significand shift and exponent adjustment functions can be performed once with a single set of hardware, with the results shared by both the add and the subtract operations New add and normalize blocks are needed for the new subtract operation. It shows the architecture of the fused add-subtract unit, the blocks with white background are the same blocks used for a single floating-point add operation. The blocks with green background are additional blocks used to perform the subtract operation, are similar to the floating point add blocks, but with extended functionality to calculate the sign and exponent for the new subtract operation. Since two operations are explicitly performed for sum and difference results (e.g., if the addition is used for the sum, the subtraction is used for the difference), the
addition and subtraction are separately placed and only one LZA and normalization (for the subtraction) is required. Assuming both sign bits are positive, the addition and subtraction are performed separately. Then, two multiplexers select the sum and difference with the operation decision bit, which is the XOR of the two sign bits. This will realize their Dot-product format of multiplication and sum them again to make as FDP for better than serial implementation. This FDP will increase the efficiency of FFT implementation.
