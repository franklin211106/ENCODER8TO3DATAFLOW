# name:FRANKLIN.F
# REF.NO :24900641
### ENCODER 8TO3 DATAFLOW Modelling

# AIM:

To implement  Encoder 8 To 3 in Dataflow Modelling using verilog and validating their functionality using their functional tables

**SOFTWARE REQUIRED:** Quartus prime

# THEORY
An encoder is a digital combinational circuit that converts a human friendly information into a coded format for processing using machines. In simple words, an encoder converts a piece of information normal form to coded form. This process is called encoding.
Encoders are crucial components in various digital electronics applications such as data transmission, controlling and automation, communication, signal processing, etc.
An encoder consists of a certain number of input and output lines. Where, an encoder can have maximum of "2n" input lines whereas "n" output lines. Hence, an encoder encodes information represented by "2n" input lines with "n" bits.
**Encoder 8 To 3**

The 8 to 3 line Encoder is also known as Octal to Binary Encoder. In 8 to 3 line encoder, there is a total of eight inputs, i.e., D0, D1, D2, D3, D4, D5, D6, and D7 and three outputs, i.e., A0, A1, and A2. In 8-input lines, one input-line is set to true at a time to get the respective binary code in the output side. Below are the block diagram and the truth table of the 8 to 3 line encoder.

![image](https://github.com/naavaneetha/ENCODER8TO3DATAFLOW/assets/154305477/0bc242c1-eb9e-4c47-afe5-30428470efc3)

Figure 01  Block Diagram of Encoder 8 * 3

**Truth Table**

![image](https://github.com/naavaneetha/ENCODER8TO3DATAFLOW/assets/154305477/35496b14-ae6e-4cd1-9abd-d6736b576575)

The logical expression of the term A0, A1, and A2 are as follows:

A0 = D1 + D3 + D5 + D7

A1 = D2 + D3 + D6 + D7

A2 = D4 + D5 + D6 + D7

Logical circuit of the above expressions is given below:

![image](https://github.com/naavaneetha/ENCODER8TO3DATAFLOW/assets/154305477/95acaee6-c873-4c75-89eb-ef09fb158053)

Figure 02  Encoder 8 * 3

**Procedure**



# PROGRAM

![WhatsApp Image 2024-12-07 at 10 24 28_9dc78e88](https://github.com/user-attachments/assets/69e42541-d6ea-44f1-a36f-713eed77fa0e)


Developed by: RegisterNumber:


# TL LOGIC FOR Encoder 8 To 
![WhatsApp Image 2024-12-07 at 10 13 06_b027b5b8](https://github.com/user-attachments/assets/c63a9ece-ffc8-42fb-9084-6748418b8ed7)
3 in Dataflow Modelling

# TIMING DIGRAMS FOR Encoder 8 To 3 in Dataflow Modelling
![WhatsApp Image 2024-12-07 at 10 13 40_3dda7990](https://github.com/user-attachments/assets/ee8f2df4-5418-4a9b-bb04-fb4516279aeb)

# RESULTS
To implement  Encoder 8 To 3 in Dataflow Modelling using verilog and validating their functionality using their functional tables



