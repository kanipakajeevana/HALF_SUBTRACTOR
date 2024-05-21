# HALF_SUBTRACTOR
# AIM:
To simulate and synthesis Half Subtractor using vivado.
# APPARATUS REQUIRE:
vivado 2023.2 software.
# PROCEDURE
STEP:1 Start the vivado software, Select and Name the New project.

STEP:2 Select the device family, device, package and speed.

STEP:3 Select new source in the New Project and select Verilog Module as the Source type.

STEP:4 Type the File Name and module name and Click Next and then finish button. Type the code and save it.

STEP:5 Select the run simulation and then run Behavioral Simulation in the Source Window and click the check syntax.

STEP:6 Click the simulation to simulate the program and give the inputs and verify the outputs as per the truth table.

STEP:7 compare the output with truth table.
#TRUTH TABLE
![image](https://github.com/kanipakajeevana/HALF_SUBTRACTOR/assets/170450203/ea2fc145-bcb6-47f8-8674-88a176af94d6)




# Circuit Diagram
![image](https://github.com/kanipakajeevana/HALF_SUBTRACTOR/assets/170450203/05fa35e9-7555-4232-9724-a72252aca876)

![image](https://github.com/kanipakajeevana/HALF_SUBTRACTOR/assets/170450203/b572b13a-5874-4dac-9b04-6fa8bb574058)
# VERILOG CODE
module halfsubtractor(a,b,diff,borrow);

input a,b;

output diff,borrow;

xor g1(diff,a,b);

and g2(borrow,~a,b); 
endmodule
# OUTPUT
![image](https://github.com/kanipakajeevana/HALF_SUBTRACTOR/assets/170450203/15835950-cd29-4d8c-a0db-13701f8bc96a)
# RESULT
Thus,the verilog program for half subtractor has been simulated and verified successfully.

