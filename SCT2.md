
## Chapter.2: ECD + CMP
Technology inventory:
> Oxidation  
> Lithography  
> Etching (wet & dry, polish)  
> Doping => Implantation (Diffusion)  
> Deposition  
	>Chemical Vapor Deposition
	>(CVD +/- Plasma) - ALD
	>Evaporation /
	>Sputter Deposition (PVD)
	>Electrochem. Depo. (ECD)

#### Electrochem. Depo. (ECD)
Electrochemical deposition is a process where the metallic ion can become solid metal and deposit on the cathode surface if a sufficient amount of electric current passes through the electrolyte solution. The electrolyte contains charged ions, which form by dissolving a metallic salt in water.

#### Chemical mechanical polishing (CMP)
In the evolution of IC products the corrugation of surface topologies grew constantly. On the other hand the CD became constantly smaller. At a certain point in time the technically possible DOF was larger than the corrugation of the surface. =>It became necessary to create a technology for planarization!
Chemical mechanical polishing (CMP) or planarization is a process of smoothing surfaces with the combination of chemical and mechanical forces. It can be thought of as a hybrid of chemical etching and free abrasive polishing.
> Example: Oxide planarization after CVD of insulator layer
> **CMP of SiO2 for Planarization**:1.Stops within the oxide;2.Hard to control; 3.but Does not require selectivity
> **CMP of Copper** must stop at the oxide surface => requires selectivity!
The removal rate is proportional to (local!) DownForce (Pressure) and Velocity (relative velocity between pad and wafer). The local removal rate depends on the local pattern density! A low pattern density causes a high removal rate!(The global downforce concentrates at only a few contact spots – high local pressure!)

## Chapter.3: SC - Basics
> Electrical conductivity and bandgap  
**Fermi Distribution function:**  
> Fermi-Level Energy at which occupation probability = 0,5
	For intrinsic Si Fermi-Level must be in the middle of the bandgap!  
	For n-doped Si Fermi-Level must be near the conductance band of the bandgap!  
	For p-doped Si Fermi-Level must be near the valence band of the bandgap!  
**Work Function:**
> The work function is the energy required to release an electron from a solid!
	
## Chapter.4: DRAM Polycide RIE
> Stringer Problem: Undesired residuals after gate RIE

## Chapter.5: Process integration: MOS Structure, MOS Capacitor
> Process:  
> 1.Si substrate  
> 2.Resist Apply  
> 3.Expose  
> 4.Develop  
> 5.Oxide Etching  
> 6.Resist strip  
> 7.Diffusion or Implantation
> 8.Dry Oxidation
> 9.Litho and Etch Oxide
> 10.Sputter Deposition
> 11.Litho and Etch Metal

Impact of material and layout  
**High K - EOT**  

## Chapter.6: MOS-CV +
**Transition to the MOSFET**
- Accumulation
- Depletion
- Inversion
Dependency on:
- oxide thickness
- doping level

## Chapter.7: MOSFET +
- The current from drain to source is modeled as:
- ${\displaystyle I_{\text{D}}=\mu _{n}C_{\text{ox}}{\frac {W}{L}}\left[\left(V_{\text{GS}}-V_{\rm {th}}\right)V_{\text{DS}}-{\frac {{V_{\text{DS}}}^{2}}{2}}\right](1+\lambda V_{DS})}$

- Threshold voltage:
Body effect:  
    The body effect is the change in the threshold voltage by an amount approximately equal to the change in the source-bulk voltage, {\displaystyle V_{SB}}V_{SB}, because the body influences the threshold voltage  
- ${\displaystyle V_{TN}=V_{TO}+\gamma \left({\sqrt {\left|V_{SB}+2\phi _{F}\right|}}-{\sqrt {\left|2\phi _{F}\right|}}\right)}$
Dependence on oxide thickness:
	the thinner the oxide thickness, the lower the threshold voltage
- ${\displaystyle I_{fn}=C_{1}WL(E_{ox})^{2}e^{-{\frac {E_{0}}{E_{ox}}}}}$
Temperature dependence:
- ${\displaystyle \phi _{F}=\left({\frac {kT}{q}}\right)\ln {\left({\frac {N_{A}}{n_{i}}}\right)}}$
the MOSFET transconductance is:
-${\displaystyle g_{m}={\frac {\partial I_{D}}{\partial V_{\text{GS}}}}={\frac {2I_{\text{D}}}{V_{\text{GS}}-V_{\text{th}}}}={\frac {2I_{\text{D}}}{V_{\text{ov}}}},}{\displaystyle g_{m}={\frac {\partial I_{D}}{\partial V_{\text{GS}}}}={\frac {2I_{\text{D}}}{V_{\text{GS}}-V_{\text{th}}}}={\frac {2I_{\text{D}}}{V_{\text{ov}}}},}$
output resistance:
- ${\displaystyle r_{\text{out}}\approx {\frac {1}{\lambda I_{\text{D}}}}}{\displaystyle r_{\text{out}}\approx {\frac {1}{\lambda I_{\text{D}}}}}$.

## Chapter.8: Al-Gate FET +Inverter
In contrast to the MOS-cap, it is for the MOS-FET not necessary to generate the inversion charge thermally! Here the high S/D doping enables the “flooding” of the channel as soon as the inversion condition is reached.
**Transfer–curve : ID=f(VG):**
	The smaller this value - respectively the steeper the graph in the subthreshold range, the better is the turn off behavior of the transistor or the larger is the Ion/Ioff ratio.

**Circuits in Aluminum-Gate FET:**
	Process Sequence for a N-MOS FET in Metal (Aluminum) Gate Technology:
	1.Oxidation  
	2.S/D Mask; Ox Etch; S/D Diffusion
	3.Field-Ox Mask; Ox Etch; Gate Oxidation
	4.Contact Mask; Ox Etch; Al Depo
	5.Metal Mask; Metal Etch

**From an inverter to an SRAM:**
	
## Chapter.9: E/D Logic
> Controllable Parameters: -Dielectric Thickness / Dielectric Constant (k)  
	-Substrate Dopant Concentration  
	-Oxide Charge  
	-Workfunction Difference  
	-Body Potential  
	
This FET is called parasitic transistor. It might unintentionally connect any n+ region where Gate lines run over the fieldox. To avoid this, the fieldox thickness has to be as large as possible.

**E/E inverter:**
**E/D inverter:**
Much better transfer behavior of the E/D inverter!
	1. Voutmax=VDD
	2. Slope in the transfer curve high
- Different inverters:
	E/E inverter (4 Masks) and E/D inverter (5 or 6 Masks)

**Self Aligned Process:**
The FET has two important Capacities:The Gate capacity determined by  
	the charge to form the inversion channel and the  
	parasitic capacitors resulting from the overlap of the gate metal with the source/drain region.

The Si Gate FET is the first application of a class of process methods called **self aligned techniques**.In this case: No mask required to define S/D!

## Chapte.10: Further self alignment:
Challenges associated with large dfox:
- Lithography on large topography
	**CD**=k1λ/NA, Critical demention
	**DOF**=k2λ/NA^2, Depth of Focus

How to avoid parasitic FETs: a **Channel Stop**
> To further relax this problem, the p-substrate underneath the fieldox can be doped to p+. This shifts VT of the parasitic transistor to higher VG and insures a safer operation.
> This additional doping is called “channel stopper”. By applying the “channel stopper”, the threshold of the parasitic transistor can not be reached under normal operation.
#### LOCOS Process:
A “self adjusting” way to combine the growth of the fieldox with the masking of the “Channel Stopper” is the so called LOCOS process which stands for **Local Oxidation of Silicon**.
	LOCOS creates significant topography  
	LOCOS requires much floor space  
#### Shallow Trench Isolation (STI):


## Chapter.11: Evolution of fieldoxide: LOCOS --> STI

#### Lightly Doped Drain LDD
Lightly Doped Drain, LDD: Relaxation of the field strength by lowering n-doping
The junction at the Drain side creates a peak in the electric field strength, creating “hot electrons”, which may gain enough energy to penetrate into the gate oxide and degrade the device. A smooth junction relaxes this effect.
To create this smooth junction (LDD) with the required accuracy, no photo alignment is necessary. It is done in a self aligned way utilizing the anisotropic behavior of reactive ion etching.

#### Self aligned Silicide
A class of materials combining low resistance and thermal stability are “silicides”, which are binary compounds of metals and silicide.
To optimize the performance of the MOSFET the resistivity of the gate line, as well as the resistivity of the source/drain contact should be as low as possible.
optimize the performance of the MOSFET the resistivity of the gate line, as well as the resistivity of the source/drain conta

#### Self aligned contacts (SAC)
Self-Aligned Contact (SAC) is a semiconductor process flow technique that adds a protective dielectric layer over the transistor gate in order to prevent contact-to-gate shorts. SAC is used to enable aggressive scaling of the contacted poly pitch while minimizing yield loss due to misalignment and partial overlaps of the contacts over the gate.https://en.wikichip.org/wiki/self-aligned_contact
#### Resist trimming
Resist trimming is an essential step for the manufacturing of sub-20 nm gate length transistors. This step consists in consuming laterally and vertically resists features to reduce their size.Isotropic etch!!!

## Chapter.12
#### Concept of the CMOS Inverter
They operate with very little power loss and at relatively high speed. Furthermore, the CMOS inverter has good logic buffer characteristics, in that, its noise margins in both low and high states are large.

#### LOCOS
https://de.wikipedia.org/wiki/LOCOS-Prozess

#### Shallow trench isolation(STI)
https://de.wikipedia.org/wiki/Grabenisolation
Shallow trench isolation (STI), also known as box isolation technique, is an integrated circuit feature which prevents electric current leakage between adjacent semiconductor device components. STI is generally used on CMOS process technology nodes of 250 nanometers and smaller. 

## Chapter.13
#### Challenges of Scaling
- Leakage current (S/D and Gate/Body)
- Variability of process parameters
- Thermal management
- Interconnects limit switching speed
Sub threshold current slope depends only on temperature.

#### Short channel effects
Drain induced barrier lowering DIBL: https://en.wikipedia.org/wiki/Drain-induced_barrier_lowering
Drain-induced barrier lowering (DIBL) is a short-channel effect in MOSFETs referring originally to a reduction of threshold voltage of the transistor at higher drain voltages.漏极感应势垒降低效应是在半导体制备工艺中，小尺寸场效应晶体管（FET)中所出现的一种不良现象，即当沟道长度减小、漏区源区间电压（Vds)增加，使得漏结与源结的耗尽层靠近时，沟道中的电力线可以从漏区穿越到源区，并导致源极端势垒高度降低，从而使源区注入到沟道的电子数量增加，结果导致漏极电流增加。而当沟道长度越短时，DIBL效应就越严重。

#### Retrograde doping
Required are Super Steep Doping Profiles to confine the channel and drain depletion zones.

#### Shallow junction
Term typically refers to a depth of the source and drain regions in advanced CMOS; scaling rules require continued reduction of the junction depth; 
#### halo implantation, 
used in CMOS fabrication to supress punch-through effect; low energy, low current implantation carried out at large incident angle so that implanted dopants penetrate underneath the edge of the MOS gate stack.
-- High dopped region near source/drain
-- reduce Drain induced barrier lowering

#### Technology approach: SOI
In semiconductor manufacturing, silicon on insulator (SOI) technology is fabrication of silicon semiconductor devices in a layered silicon–insulator–silicon substrate, to reduce parasitic capacitance within the device, thereby improving performance.
#### HKMG
High-k/Metal Gate (HKMG) reduces gate leakage by multiple orders of magnitude

#### Local strain: Stressed Liner Films (Mechanical stress)
Tensile (NMOS) and Compressive (PMOS) PECVD SIN films
Drive current increase

#### Dual Stress Liner (DSL) 
In the DSL process, standard patterning and lithography techniques are used to selectively deposit a tensile silicon nitride film over the NMOS and a compressive silicon nitride film over the PMOS.

## Chapter.14
#### Horizontal Double Gate MOSFET


#### FinFET double-gate Transistor
Significantly less floor space and much better electrostatic control of the body.

