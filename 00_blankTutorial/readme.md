Single-Supply vs. Dual-Supply Op-Amp Circuits
We will now briefly discuss the difference between single-supply and dual-supply op-amp circuits. In previous labs, you have primarily worked with dual supplies when using op amps. 
Note: Vmid is calculated as the midpoint between the positive and negative power supplies: Vmid=VDD + VSS2

![Uploading image.png…]()

A dual-supply circuit uses two supply rails, typically one positive and one negative relative to ground (GND). In a dual supply circuit, GND serves as the midpoint between the positive (VDD) and negative (VSS) supply rails. The supply voltages VDD and VSS are typically equal in magnitude but opposite in polarity. For example, when operating the LM741 op amp in Lab 1 or EE2015 labs, you operated the circuit at VDD = 12V and VSS = -12V. In this case, the midpoint reference Vmid is simply 0V or GND. 
