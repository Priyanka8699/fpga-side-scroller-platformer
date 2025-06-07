# FPGA Side-Scrolling Platformer Game

This repository contains the final lab project for ELEC 4475: System on Chip (Spring 2025), in which a complete 2D side-scrolling video game was developed using C, custom IP cores, and an FPGA platform with memory-mapped VGA tile rendering.

## 📽️ Game Features

- **Multi-Screen Backgrounds**: 7 unique screens rendered from tilemaps using efficient memory reuse.
- **Player Mechanics**: Movement, jump physics, sprite animations, and screen transitions.
- **Enemy AI**: Multiple enemy types including flying, bouncing, and boss tracking logic.
- **Projectile System**: Player/enemy bullets with collision detection and boss damage tracking.
- **Lives, Score, and Game Over**: Game logic includes respawning, scoring, and full restart handling.
- **NES-Style Joystick Input**: All gameplay is controlled through joystick input read via AXI GPIO.


## 🧠 Technologies Used

- C Programming
- FPGA Memory-Mapped I/O
- VGA Tile Rendering
- Custom IP Cores (Joystick, VGA, GPIO)
- Xilinx SDK + Platform-specific drivers
- Embedded System Design Practices

## 🏁 Running the Game

1. Clone the repository.
2. Import the code into Xilinx SDK (or Vitis).
3. Connect the FPGA board and NES-style joystick.
4. Build and program the bitstream + ELF file.
5. Observe the game on the VGA output.

## 📷 Demo Screenshots

> ![screen1](https://github.com/user-attachments/assets/2bb90b9a-1637-4f6f-a3d0-5b497e8b125e)
> ![image](https://github.com/user-attachments/assets/39f18eb0-4e02-4f2d-9932-c621a9dccf6c)
> ![image](https://github.com/user-attachments/assets/36bf9823-a25d-4e8e-8904-d481849324ed)
> ![image](https://github.com/user-attachments/assets/47848c67-03cb-4699-a5eb-01f35182eb60)
> ![image](https://github.com/user-attachments/assets/dfd1a7c1-ebbf-47ec-b6de-a11ca481630d)
> ![image](https://github.com/user-attachments/assets/9021769f-0930-4bd5-b11c-ec03164976ef)


## 📜 Report

The full project report is available in [`Soc-Final-Report_priyanka.pdf`](Soc-Final-Report_priyanka.pdf), detailing design goals, implementation strategy, data structures, and reflections.

## 👩‍💻 Author

**Priyanka Akkala**  
Embedded Systems & FPGA Developer  
Email: akkalapriyanka03@gmail.com  
LinkedIn: https://www.linkedin.com/in/akkalapriyanka/  

---





