# 2_bit_synchronous_up_counter
#AIM:
    To implement 2 bit synchronous up counter using verilog and validates its outputs
#HARDWARE: PC,CYCLONE 2,USB flasher
#SOFWARE:Quartus prime
#Theory:
A 2-bit synchronous up counter is a digital circuit that counts up from 0 to 3 in binary (00, 01, 10, 11) in a synchronous manner. This means that the counting process is triggered by a clock signal, and all flip-flops in the circuit change their state simultaneously with the rising edge of the clock. The circuit typically consists of two J-K flip-flops connected in series, each of which advances the count by one. The output of the first flip-flop is connected to the input of the second flip-flop, and the output of the second flip-flop is the final count. The circuit can also be designed with D flip-flops instead of J-K flip-flops.
#Logic diagram:
![logic diagram](https://user-images.githubusercontent.com/121490890/215010793-e6840c35-6251-4b69-ab1b-73d9a6686480.png)
#Procedure:
1)Create a 4-input truth table for the 2-bit counter, including the current states of the two bits (Q1 and Q0) and the external clock signal.
2)Design the next state logic for the counter using the truth table. This can be done by creating a Boolean expression for each output bit, Q1 and Q0, based on the current states of the input bits and the external clock signal.
3)Implement the next state logic in the form of flip-flops or latches, which will store the current state of the bits and update them based on the external clock signal.
4)Connect the output of the flip-flops/latches to the input of the next stage of the counter, if there is one, to create a cascaded counter.
5)Use the external clock signal to trigger the updates of the flip-flops/latches, which will cause the counter to increment.
#Program:







