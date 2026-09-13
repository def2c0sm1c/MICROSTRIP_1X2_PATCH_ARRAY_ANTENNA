# MICROSTRIP_1X2_PATCH_ARRAY_ANTENNA

## OVERIVIEW

This project focuses on the design and fabrication of a 2.4 GHz 1×2 microstrip patch array antenna to study the practical behavior of an array-based configuration. The two-element array provides a simple platform for achieving more directional radiation characteristics than a single patch while maintaining a compact structure.

Operating in the 2.4 GHz ISM band, the antenna is relevant to applications such as Wi-Fi, Bluetooth, IoT, and short-range wireless systems. The primary focus is the comparison of simulated and measured S₁₁ performance to examine the practical variation introduced after fabrication and VNA testing.


---
## PROJET OBJECTIVES
·Design and simulate a 2.4 GHz 1×2 microstrip patch array antenna.

·Fabricate the simulated antenna design.

·Measure the fabricated antenna using a Vector Network Analyzer (VNA).

·Compare simulated and measured S₁₁ characteristics.

·Study the practical variation between simulation and measurement.

---

## ANTENNA SPECIFICATIONS
![image alt](https://github.com/def2c0sm1c/MICROSTRIP_1X2_PATCH_ARRAY_ANTENNA/blob/9ae319720350feb2af7e674fc92065e84ae5d900/Antenna_Specifications.png)

## Antenna Design & Fabrication

The antenna consists of two rectangular microstrip patches connected through a corporate feed network with a quarter-wave impedance transformer. The design was simulated in CST Studio Suite and subsequently fabricated on an FR-4 PCB for experimental characterization.

![image alt](https://github.com/def2c0sm1c/MICROSTRIP_1X2_PATCH_ARRAY_ANTENNA/blob/bfc4563f5e0eea1d5d7702822f5cb504ce724a69/TOP_and_Bottom_view.png)

## FABRICATED ANTENNA 

![image alt](https://github.com/def2c0sm1c/MICROSTRIP_1X2_PATCH_ARRAY_ANTENNA/blob/bfc4563f5e0eea1d5d7702822f5cb504ce724a69/Fabricated%20_Top_and_Bottom_view.png)

---

## Simulation & Experimental Results

The simulated antenna exhibits a resonance near 2.45 GHz with a minimum S₁₁ of approximately −38 dB.
![image alt](https://github.com/def2c0sm1c/MICROSTRIP_1X2_PATCH_ARRAY_ANTENNA/blob/9ae319720350feb2af7e674fc92065e84ae5d900/Simulation_Return_loss.png)

The fabricated antenna was measured using a Keysight FieldFox VNA, giving a measured resonance near 2.400 GHz with a minimum S₁₁ of −14.67 dB.

![image alt](https://github.com/def2c0sm1c/MICROSTRIP_1X2_PATCH_ARRAY_ANTENNA/blob/95b17c754701baf6d93347d33a3a35b75d139bef/VNA_output.png)

---
## RESULT
The proposed 1 × 2 rectangular microstrip patch array antenna was successfully designed, simulated, fabricated, and experimentally characterized. The CST simulation produced a minimum return loss (S₁₁) of −38 dB at the designed resonant frequency of 2.4 GHz, indicating excellent impedance matching. After fabrication, the antenna was characterized using a Vector Network Analyzer (VNA), which measured a return loss of −15 dB at the same operating frequency. Although the measured return loss was higher than the simulated value, it remains well below the acceptable threshold of −10 dB, confirming satisfactory impedance matching and antenna operation. 

The variation between the simulated and measured results is primarily attributed to fabrication tolerances, variations in the dielectric properties of the FR-4 substrate, SMA connector soldering, conductor losses, and practical measurement uncertainties. The fabricated antenna successfully demonstrated the desired radiation characteristics, making it suitable for 2.4 GHz ISM band wireless communication applications.

## Reference & Study Purpose

This antenna design is based on an established IEEE paper and is reproduced for learning, simulation, fabrication, and experimental study. No novel antenna design or modification is claimed in this repository.

The included CST project file is provided for study and educational purposes only. It may be used to examine and understand the antenna design and simulation setup.

### Skills Demonstrated

CST Studio Suite · Microstrip Patch Array Design · Antenna Fabrication · VNA Measurement · S₁₁ Analysis · · Simulation vs Measurement Analysis · RF & Microwave Engineering
