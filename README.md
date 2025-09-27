# 🤖 VEX V5 Claw Hero Bot (Tojo)

This project contains the codebase for a **VEX V5 Claw Hero Bot** built using C++ in VEXcode Pro.  
The robot is equipped with a drivetrain, claw mechanism, and an arm for object manipulation.  
It was developed to demonstrate autonomous and driver-controlled operation for robotics challenges.

---

## ⚙️ Hardware Configuration

The robot is configured with the following components:

- **Drivetrain**:  
  - 2-motor drive  
  - 4-inch wheels  
  - 18:1 gear ratio  
  - Wheelbase: 295 mm wide, 40 mm long  

- **Arm System**:  
  - `arm_motor` (Port 13) – controls vertical lift for placing objects  

- **Claw System**:  
  - `claw_motor` (Port 14) – opens and closes claw for object grabbing  
  - `Grabber` (Port 6) – secondary grabber/assist motor  

- **Controller**:  
  - `Controller1` for driver control inputs  

---

## 🖥️ Software

- **Language**: C++  
- **IDE**: VEXcode Pro V5  
- **SDK Version**: `20220726_10_00_00`  

---

## 🚀 Features

- Manual driving with `Controller1`
- Arm and claw control for grabbing and placing objects
- Modular configuration for future autonomous routines
- Code organized into `main.cpp` and hardware abstraction via `robot-config.*`

---

## 📖 How to Use

1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/vex-claw-hero-bot.git

2. Open the project in VEXcode Pro V5.

3. Connect the V5 Brain to your computer.

4. Build and download the program to the robot.

5. Run the program to control the Claw Hero Bot.
