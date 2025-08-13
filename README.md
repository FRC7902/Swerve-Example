# Swerve Subsystem

This template provides a partially completed WPILib Java project for a Swerve subsystem.  
Programmers are expected to **correct the code**.

The `backleft.json`, `backright.json`, `frontleft.json`, `frontright.json`, and `swervedrive.json` in the deploy/swerve have incorrect values! It is up to you to correct this code so that we can simulate the swerve drive! After you are done, you should be able to do the following:


### ▶️ 1. Run the Robot in Simulation

Once you’ve filled in the required code, you can **run the robot in simulation** using the WPILib extension:

1. Open the Command Palette in VS Code: `Ctrl+Shift+P` (Windows) / `Cmd+Shift+P` (Mac).
2. Select `WPILib: Simulate Robot Code`.
3. Choose the option: **Sim GUI**.

---

### 🎮 2. Set Up Robot Control

To control the robot simulation:

1. In AS, open the **"Robot Simulation"** window (usually on the right or bottom).
2. Under **Joysticks**, find the `Joysticks[0]` slot.
3. Drag **Keyboard 0** into `Joysticks[0]` (unless you have a physical controller connected).
   - `Joysticks[0]`, `[1]`, etc., represent the slots used in your robot code (e.g., `new Joystick(0)`).
   - Binding `Keyboard 0` simulates a gamepad using your keyboard.
4. Under **Robot State**, click **“Teleoperated”** to enable the robot.

### 🕹️ Default Keyboard Controls

- `W` = Drive Forward  
- `S` = Drive Backward  
- `A` = Drive Left  
- `D` = Drive Right

---
