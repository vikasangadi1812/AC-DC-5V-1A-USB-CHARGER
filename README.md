# AC–DC 5V 1A USB Charger

## 📌 Project Overview

AC Mains
   ↓
Step-Down Transformer
   ↓
Bridge Rectifier
   ↓
Filter Capacitor
   ↓
7805 Voltage Regulator
   ↓
Protection Stage
   ↓
5V DC Output
   ↓
USB / Low-Power Device


🎯 Objectives

230V AC Input
   ↓
Step Down High Voltage
   ↓
Convert AC to DC
   ↓
Reduce Ripple
   ↓
Regulate Voltage
   ↓
Obtain Stable 5V DC
   ↓
Supply Low-Voltage Devices

🔧 Components Used
Step-Down Transformer
        ↓
Bridge Rectifier
        ↓
Filter Capacitor
        ↓
7805 Voltage Regulator
        ↓
Current Limiting Resistor
        ↓
Protection Diode
        ↓
Fuse
        ↓
USB / Load
⚙️ Specifications
Input Voltage → 230V AC
       ↓
Frequency → 50 Hz
       ↓
Transformer → 230V AC to 9V AC
       ↓
Rectifier → Full-Wave Bridge
       ↓
Filter → Capacitor
       ↓
Regulator → 7805
       ↓
Output → 5V DC
       ↓
Maximum Current → 1A
🔄 Working Principle
230V AC Mains
      ↓
Step-Down Transformer
      ↓
9V AC Secondary
      ↓
Bridge Rectifier
      ↓
Pulsating DC
      ↓
Filter Capacitor
      ↓
Smooth DC
      ↓
7805 Voltage Regulator
      ↓
Regulated 5V DC
      ↓
Protection Stage
      ↓
USB / Load
🧮 Design Calculations
Transformer Calculation
Primary Voltage = 230V AC
        ↓
Transformer
        ↓
Secondary Voltage = 9V AC
        ↓
Peak Voltage = 9 × √2
        ↓
Peak Voltage = 12.73V
Bridge Rectifier Calculation
Peak Secondary Voltage = 12.73V
        ↓
Two Diodes Conduct
        ↓
Diode Drop = 2 × 0.7V
        ↓
Total Drop = 1.4V
        ↓
Rectified Voltage = 12.73 − 1.4
        ↓
Rectified Voltage = 11.33V
Ripple Calculation
Capacitor = 470µF
        ↓
Load Current = 1A
        ↓
Input Frequency = 50Hz
        ↓
Full-Wave Ripple Frequency = 2 × 50
        ↓
Ripple Frequency = 100Hz
        ↓
Vr = I / (fr × C)
        ↓
Vr = 1 / (100 × 470 × 10⁻⁶)
        ↓
Vr ≈ 21.3V
7805 Regulation
Rectified DC = 11.33V
        ↓
Minimum 7805 Input ≈ 7V
        ↓
11.33V > 7V
        ↓
7805 Operates in Regulation
        ↓
Output = 5V DC
Current Limiting Resistor
Resistance = 2.2Ω
        ↓
Maximum Current = 1A
        ↓
Voltage Drop = I × R
        ↓
Voltage Drop = 1 × 2.2
        ↓
Voltage Drop = 2.2V
        ↓
Power = I² × R
        ↓
Power = 1² × 2.2
        ↓
Power = 2.2W
        ↓
Selected Rating ≥ 3W
Protection Diode
Output = 5V DC
        ↓
Protection Diode
        ↓
Forward Voltage Drop ≈ 0.7V
        ↓
Provides Reverse-Polarity Protection
🖥️ Simulation
AC Source
   ↓
Transformer
   ↓
Bridge Rectifier
   ↓
Filter Capacitor
   ↓
7805 Regulator
   ↓
Output Measurement
   ↓
≈ 5V DC

📈 Waveform
AC Input
   ↓
Step-Down AC
   ↓
Full-Wave Rectified Waveform
   ↓
Filtered DC Waveform
   ↓
Regulated DC
   ↓
Stable 5V Output

🔬 Hardware Implementation
230V AC Supply
      ↓
Step-Down Transformer
      ↓
Bridge Rectifier
      ↓
Filter Capacitor
      ↓
7805 Regulator
      ↓
Protection Components
      ↓
5V DC Output
      ↓
Load / USB Device

📊 Output
Input
  ↓
230V AC
  ↓
Transformer
  ↓
9V AC
  ↓
Bridge Rectifier
  ↓
11.33V Peak DC
  ↓
Filter Capacitor
  ↓
7805 Regulator
  ↓
5V DC
  ↓
USB / Low-Power Device

The hardware output was measured close to 5V DC.

📋 Results
AC Input
   ↓
Voltage Step-Down
   ↓
AC Rectification
   ↓
Ripple Reduction
   ↓
Voltage Regulation
   ↓
Stable 5V DC
   ↓
Successful Hardware Output
🚀 Future Scope
Current Design
      ↓
Replace 7805
      ↓
SMPS-Based Design
      ↓
Higher Efficiency
      ↓
Add Thermal Protection
      ↓
Add Surge Protection
      ↓
Add Short-Circuit Protection
      ↓
SMD Miniaturization
      ↓
Compact Charger
👥 Team Members
Shashank Iranatti
        ↓
Vikas Angadi
        ↓
Arpita Yalamalli
        ↓
AC–DC 5V 1A USB Charger
📂 Project Structure
AC-DC-5V-1A-USB-Charger
        ↓
README.md
        ↓
images/
        ↓
block_diagram.png
simulation_circuit.jpeg
simulation_waveform.png
oscilloscope_output.jpeg
pcb_implementation.jpeg
        ↓
docs/
        ↓
AC-DC_5V_1A_USB_Charger_Report.pdf
📄 Documentation
Project
   ↓
Complete Report
   ↓
Design
   ↓
Calculations
   ↓
Simulation
   ↓
Hardware Implementation
   ↓
Results
   ↓
Conclusion
⚠️ Safety
230V AC Mains
      ↓
High Voltage
      ↓
Electrical Hazard
      ↓
Use Proper Isolation
      ↓
Use Fuse & Protection
      ↓
Perform Testing Under Supervision
