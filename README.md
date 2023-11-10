# ssed_project[ear phones]
## mobile charger
First, it converts AC to DC then again back to AC and finally to DC.
normal charger circuit that converts 220V AC to 5V DC.There are diodes, capacitors, transistors, resistors, transformers and an optocoupler. Also, there are resistors below the PCB. Once the power is on, it turns on
# Application
.
Diodes only allow current to flow in one direction. In first half cycle of AC diode D2 & D3 are forward biased and D1 and D4 are reversed biased, and in the second half cycle (negative half) Diode D1 and D4 are forward biased and D2 and D3 are reversed biased. This Combination converts the negative half cycle into positive.
# AC to DC conversion 
## pn junction diode
Diodes only allow current to flow in one direction. In first half cycle of AC diode D2 & D3 are forward biased and D1 and D4 are reversed biased, and in the second half cycle (negative half) Diode D1 and D4 are forward biased and D2 and D3 are reversed biased. This Combination converts the negative half cycle into positive.
 4 pn juction diodes as rectifier.Rectification is the process of removing the negative part of the Alternate Current (AC), hence producing the partial DC
 220V 50Hz AC comes as input. a bridge rectifier, it converts AC to fluctuating DC
  fluctuating DC filters from the capacitor and becomes almost pure DC
## filter capacitor
   The input filter capacitor smooths out the ripples and
   provides a more stable DC voltage to the voltage regulator chip

# oscillator
![Screenshot 2023-11-10 093304](https://github.com/Ravikrishnan05/ssed_project/assets/134152503/d3f803d3-7eed-4856-9030-2f7f8fa3e777)
This is an oscillator circuit. This converts DC back to high-frequency AC of 15 to 50 KHz.
These consist two NPN transistors.NPN transistors in a mobile charger oscillator work to generate a high-frequency AC signal that is used to drive the transformer.

When the circuit is first turned on, Q1 is slightly turned on by the base current flowing through R1. This causes Q1 to conduct a small amount of current, which flows through the inductor

The current flowing through the inductor induces a voltage in the feedback winding present below . This voltage is applied to the base of Q2, turning it on

Now, this current passes from the 2M ohm resistor to the base of the 1st  transistor to turn it on. This transistor isn’t fully turned on, because of the resistance it turns on partially. Due to the partial turning on of the transistor, a low current passed from the primary winding of the transformer. This induces a low voltage in the auxiliary winding.

https://www.engineersgarage.com/insight-how-mobile-phone-charger-works/
![Cell-Phone-Charger-Circuit](https://github.com/Ravikrishnan05/ssed_project/assets/134152503/004248e6-e837-43d3-8667-35df0ef15f38)
![Screenshot 2023-11-09 233537](https://github.com/Ravikrishnan05/ssed_project/assets/134152503/91bcabb2-41e3-42ea-9e2c-6c1d3394d3d3)
## open these web links 
https://www.youtube.com/watch?v=2N_T7VFymFg

https://circuitdiagrams.in/how-does-a-5v-mobile-charger-work/

https://circuitdigest.com/electronic-circuits/cell-phone-charger-circuit-diagram
