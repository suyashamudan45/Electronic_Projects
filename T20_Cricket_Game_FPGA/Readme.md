# T20 Cricket Game using FPGA (Basys3)

A hardware-based implementation of a T20 Cricket game developed on the Basys3 FPGA board using Vivado Xilinx.  
The project simulates core cricket mechanics such as batting, bowling, scoring, and match outcomes using digital logic design.

---

## 📌 Project Overview

This project demonstrates the use of FPGA technology to implement a real-time interactive game system.  
Unlike software-based games, all game logic is implemented directly in hardware using FPGA resources, highlighting parallel processing, timing accuracy, and efficient resource utilization.

The game logic was designed, synthesized, and implemented using Vivado Xilinx and deployed on the Basys3 FPGA board.

---

## 🎯 Objectives

- To design and implement a T20 cricket game using FPGA
- To understand real-time digital system design
- To integrate game logic, input handling, and output display in hardware
- To explore FPGA capabilities beyond conventional applications

---

## 🧠 Key Features

- Batting, bowling, and scoring logic implemented in hardware
- Real-time game simulation using FPGA parallelism
- Match status displayed using LEDs and seven-segment displays
- Efficient use of FPGA resources through optimized logic design
- Fully functional bitstream deployed on Basys3 board

---

## 🛠 Software Used

- **Vivado Xilinx**
  - HDL design (Verilog)
  - Synthesis and implementation
  - Bitstream generation
  - Hardware debugging and validation

---

## 🔧 Hardware Used

- **Basys3 FPGA Board**
- On-board LEDs
- Seven-segment display
- Input switches and buttons

---

## ⚙️ Working Principle

1. Player inputs are provided using switches/buttons on the FPGA board
2. FPGA processes inputs to determine batting, bowling, and scoring outcomes
3. Game logic manages:
   - Runs
   - Wickets
   - Balls
   - Innings status
4. Outputs are displayed using LEDs and seven-segment displays
5. FPGA ensures real-time synchronization between inputs, game logic, and outputs

All processing is performed in hardware, enabling fast and deterministic behavior.

---

## 🗂 Project Structure

T20_Cricket_Game_FPGA/
├── README.md              
├── src/
│   ├── CricketGame_TopModule.v
│   ├── display_controller.v
│   └── input_logic.v
├── constraints/
│   └── basys3.xdc
├── vivado_project/
│   └── project_2.xpr      
├── images/
│   ├── led_output.jpg
│   └── simulation_waveform.png
└── docs/
    └── Project_Report.pdf


---

## ▶️ How to Run the Project

1. Open Vivado Xilinx
2. Create a new project targeting the Basys3 FPGA
3. Add Verilog source files and constraint file
4. Run synthesis and implementation
5. Generate the bitstream
6. Program the Basys3 FPGA board
7. Use onboard switches/buttons to play the game

---

## 📊 Results

- Successful synthesis and implementation in Vivado
- Correct bitstream generation
- Real-time gameplay demonstrated on FPGA board
- Accurate display of:
  - Runs
  - Wickets
  - Balls
  - Match result (win/innings over)

---

## 🧠 What We Learned

- FPGA-based digital system design
- Verilog HDL coding and debugging
- Constraint mapping and hardware interfacing
- Resource optimization in FPGA designs
- Real-time system behavior using parallel logic

---

## 🔮 Future Enhancements

- VGA/HDMI display output for graphical interface
- Sound effects using audio modules
- Multiplayer support
- More realistic cricket mechanics
- AI-based opponent logic

---

## 👥 Team Members

- Sanjay Kumar  
- Suyash Amudan  
- Noel Channayil  
- Akshay Chauhan  

---

## 📎 Academic Context

This project was developed as **Mini Project-2B** for the  
Department of Electronics & Telecommunication Engineering  
under Mumbai University (2023–2024).

---


