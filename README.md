# SERIAL-IN-SERIAL-OUT-SHIFTREGISTER

**AIM:**

To implement  SISO Shift Register using verilog and validating their functionality using their functional tables

**SOFTWARE REQUIRED:**

Quartus prime

**THEORY**

**SISO shift Register**

A Serial-In Serial-Out shift register is a sequential logic circuit that allows data to be shifted in and out one bit at a time in a serial manner. It consists of a cascade of flip-flops connected in series, forming a chain. The input data is applied to the first flip-flop in the chain, and as the clock pulses, the data propagates through the flip-flops, ultimately appearing at the output.

The logic circuit provided below demonstrates a serial-in serial-out (SISO) shift register. It comprises four D flip-flops that are interconnected in a sequential manner. These flip-flops operate synchronously with one another, as they all receive the same clock signal.

![image](https://github.com/naavaneetha/SERIAL-IN-SERIAL-OUT-SHIFTREGISTER/assets/154305477/e81c4072-37f9-46c6-8145-566764b74c3a)

Figure 01 4 Bit SISO Register

The synchronous nature of the flip-flops ensures that the shifting of data occurs in a coordinated manner. When the clock signal rises, the input data is sampled and stored in the first flip-flop. On subsequent clock pulses, the stored data propagates through the flip-flops, moving from one flip-flop to the next.
Each D flip-flop in the circuit has a Data (D) input, a Clock (CLK) input, and an output (Q). The D input represents the data to be loaded into the flip-flop, while the CLK input is connected to the common clock signal. The output (Q) of each flip-flop is connected to the D input of the next flip-flop, forming a cascade.


**PROGRAM**


![Screenshot 2024-12-27 221803](https://github.com/user-attachments/assets/71f12a4e-eb67-4625-ab7a-26cf35538d2d)

Developed by: SATHANA.V

RegisterNumber:24901144



**RTL LOGIC FOR SISO Shift Register**

![Screenshot 2024-12-27 221810](https://github.com/user-attachments/assets/2e37259a-4fba-42b5-972b-9ca20a4e6eb4)

**TIMING DIGRAMS FOR SISO Shift Register**

![Screenshot 2024-12-27 221819](https://github.com/user-attachments/assets/f4e82aa1-1617-4c41-9c78-5f9e4f503b85)


**RESULTS**

Thus the serial in and serial out shift register is implememted using verilog with the truth table and timing diagram. 
