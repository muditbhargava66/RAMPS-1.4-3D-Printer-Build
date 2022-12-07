# Marlin (v-2.0.9.5) for the 3D printing:

---

This Repo is focused on making a old 3D printer (in our case ANET A8) ready for different kind of experiments. The goal for my project lies in expanding the Research of Additive Manufacturing in the field of Hardware Trojan. 

The initial set-up is made of:

- ANET A8 (Body + Motors + Limit Switches + Heat Bead + Extruder)
- Ramps 1.4 Boards
- A4988 Motor Drivers + Shunts + Heat Sinks
- RepRap Full Graphic Smart Controller Display
- SD Card
- Arduino Mega 2560
- Power Supply (12/24 V)
- PLA Filament

> Note: If you are buying any Ramps Kit, do buy the Original Arduino Mega 2560.
As with the cheap copy there will be many issues in terms of voltage supply, port detection, heating etc.
> 

Firmware:  **Marlin Version-2.0.9.5**

You can use this code for the similar setup, or else the using the LTS version of the Marlin at the time of your project.

Software used:

- **Arduino** ~ For uploading the Marlin
    - Install these libraries in Arduino via Library Manager, otherwise it will throw an error while verifying :
        - U8glib
        - U8glib-HAL
        
        Above mentioned 2 libraries are for the Display to work properly
        
- **Ultimaker Cura**/ Repetier ~ Slicing

> Note: Latest version of each software was used in the whole process.
> 

---

## Compiling:

Make changes if you want in the code, I have replaced the `Configuartion.h` & `Configuartion_adv.h` from the Example configuration to the Default Marlin (v-2.0.9.5).

The uploading Process takes though **AVRISP mkll** as Programmer.

---