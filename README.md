## Chapter.2: Silicon as substrate material
#### Crystal by Lattice and Base
Crystal Structure = Lattice + Base
Si – Crystal: fcc lattice with a 2 atom base at (0,0,0) + (1/4,1/4,1/4)
Each Si atom has 4 nearest neighbors NN

#### Defects
1.Point defects: vacancy, Si intenstitial, intenstitial no Si, Substitutional Atom.
2.Dislocation
3.Areal (2D) Defect: Grain boundaries/Stacking faults
4.Volume (3D) Defect: Precipitates

#### Conductivity & Doping
Energy states of elect rons in atoms
Temporary occupation of states depends on temperature
Interaction of atoms causes split ting of energy states
Transition f rom states in atoms to bands in solids
#### Silicon as most important material for μelectronics
Bandgap EG(Si)=1.1 eV vs. EG(Ge)=0.66
Si Transistor works up to 150 C; whileGe Transistor only up to 100 C
Ri(Ge)= 47Ωcm while Ri(Si)= 230KΩcm
Ge by a decade more expensive than Si.

#### Fabrication of pure Silicon
##### 3 Steps:
A: Making metalurgical grade silicon MGS: 冶金级硅
- SiO2 + 2C → Si + 2CO

B: Making electronic grade silicon EGS: 电子级硅 --> Polycristalline Silicon
- Si(MGS) + 3HCl → SiHCl3 + H2
- 4SiHCl3 + 2H2 → 3Si + SiCl4 + 8HCl

C: Growing the crystal
> 1.Czochralski method.柴可拉斯基法（英語：Czochralski process），简称柴氏法，又称直拉法或提拉法，是一种用来获取半导体（如硅、锗和砷化镓等）、金属（如钯、铂、银、金等）、盐、合成宝石单晶材料的晶体生长方法。CZ grown Si contains oxygen!The quartz crucible dissolves during crystal growth
> 2.Float-zone silicon is very pure silicon obtained by vertical zone melting. The process was developed at Bell Labs by Henry Theuerer in 1955 as a modification of a method developed by William Gardner Pfann for germanium. Making oxygen f ree Si crystal! 
	

##### Making of the wafers:
> 1.Crystal Growth; 
> 2.Single Crystal Ingot; 
> 3.Crystal Trimming; 
> 4.Flat Grinding; 
> 5.Wafer Slicing; 
> 6.Edge Rounding; 
> 7.Lapping; 
> 8.Wafer Etching; 
> 9.Polishing; 
> 10.Wafer Inspection.

##### Relation: Resistance vs. Doping

##### Defects enable the trapping of impurities Gettering:Extrinsic - / Intrinsic
1.Extrinsic:(at the wafer backside)high-pressure water jet treatment 
2.Intrinsic: precipitation + Denuded Zone(缺陷有捕捉雜質的作用)

## Chapter.3: Oxidation
SiO2 used as: 
> Part of the MOS structure (gate-oxide - as thin as possible)
> Isolation between the active devices (field-oxide - as thick as possible)
> Mask material (Diffusion, Ion-Implantation, Etching, …)

Layer growth takes place by exposure to Oxygen at elevated temperature either as:
>O2 : Si + O2 → SiO2 (Dry oxidation) or
>H2O : Si + 2H2O → SiO2 + 2H2 (Wet oxidation)

#### Growth model after Deal and Groove
> Initial growth not hampered by diffusion
	=> growth reaction limited
	=> linear growth
>Further growth hampered by diffusion
	=> concentration of oxidant at the SiO2/Si interface the lower, the thicker the oxide.
	=> parabolic growth
	
#### Dependcy on process variable
>a) wet/dry
	Differences appear in all parameters: D, N, Ks and C*.
	Although DO2 > DH2O the wet oxidation rate is lager than the dry oxidation rate!
	The higher wet oxidation rate is primarily due to the higher solubility (C*) of H2O in SiO2 compared to that of O2 .
	The effect extends to the linear as well as to the parabolic regime.
>b) Temperature
	Diffusion as well as chemical reaction are thermally activated.
>c) Pressure
>d) Orientation
>e) Doping

#### Oxidation Technology
Very uniform temperature profile required!
Thickness measuremnent
#### Stress
Strain is caused by i) difference in CTE(Coefficient of Thermal Expansion) between Film and substrate (extrinsic strain) and
					ii) build in strain inside of the film (intrinsic strain)
					
## Chapter.4: Lithography
#### process flow:
	a) Cleaning: Removal of Particles via megasound, brushing, etc. Films & contaminants via acidic and alkaline solutions
	b) Dehydration: This converts the hydrophilic surface into an oleophilic (lipophilic) surface - > organic resist adheres well!
	c) Application of primer(底漆): HMDS application(SAM –self aligned monolayer)
	d) Resist apply
	e) Pre exposure bake
	f) Exposure
	g) Post exposure bake (PEB)
	h) Development
	i) Post development bake (UV hardening)
	j) Resist removal (stripping)

#### Photoresists
Generally Photoresists consist of 3 parts:
- 	a) Resin (Mat rix Material)
- 	b) Solvent for the layer application
- 	c) Photoactive component (PAC)

Basic function: UV light changes through the PAC the property of the resist f ilm so that the solubility in a liquid differs significantly between exposed and unexposed areas
-  Negative resist: Effect of cross linking(exposed regions): Solubility in organic solvent significantly reduced. However solvent creates swelling even in exposed regions. This reduces pattern accuracy. - > Not used for pattern below 2μm.
-  Positive resist: A positive photoresist is a type of photoresist in which the portion of the photoresist that is exposed to light becomes soluble to the photoresist developer. The unexposed portion of the photoresist remains insoluble to the photoresist developer.
-  DUV resist: Modified resin; Chemically amplified resist

#### Pattern transfer still by Optical Lithography
Smallest feature (CD) is proportional to the SQRT of the product of wavelength times gap between mask and substrate
- bmin = 3/2*sqrt(λ*(g+d/n))

Resolution is diffraction limited:
- 1.Large separation of light beams => Several Diffraction Orders => High contrast at the image
- 2.Smaller separation of light beams => fewer Diffraction Orders => Low contrast at the image

CD: Critical Dimension(smallest structure width on a device): CD=K1*λ/NA
数值孔径（英語：NA, Numerical aperture）是光学系统的一个无量纲数，用以衡量该系统能够收集的光的角度范围。在光学的不同领域，数值孔径的精确定义略有不同。在光学显微镜领域，数值孔径描述了物镜收光锥角的大小，而后者决定了显微镜收光能力和空间分辨率；在光纤领域，数值孔径则描述了光进出光纤时的锥角大小。

- DOF: Depth of Focus (Tolerance range of the focal distance): DOF=K2*λ/NA^2
Image contrast only within the DOF sufficiently high enough

- Projection lithography concepts: Full Field imaging is efficient but has some technical limitations!
Resist profile: Resist profile depends on Image- and Resist quality. 
				> Steep Line prof ile obtained by high resist contrast
				> Resist cont rast does not af fect the bot tom CD
				> However , line width can be cont rolled by light intensity and/or development time
Interference: 
              > 1. a dependency of the mean intensity on the resist thickness and
			  > 2. what is called: standing waves --> cause over-exposure and under-exposure
			  solution: Bottom Anti Reflective Coating
						DQN: Post Exposure Bake activates diffusion of Carboxyl Acid
						
#### Pattern Enhancement
	a) Phase shifting mask (PSM)
	b) Off axis illumination: By Changing the Illumination Conditions the Diffraction Orders captured by the lens can be improved
	c) Optical proximity correction: take advantage of the interference generated by phase differences to improve image resolution in photolithography. 
	d) Immersion lithography: replaces the usual air gap between the final lens and the wafer surface with a liquid medium that has a refractive index greater than one.
	e) Resist trimming: resist line made narrower by isotropic etching of the resist in oxygen plasma. In both case (line/space) remains constant 
	f) Double exposure: 
	g) EUV: Extreme UV (λ=13,5 nm) Multilayer reflective mask necessary

#### Photomasks
Classical approach: Exposure by UV light through mechanically adjusted slits.
Today: Mask writing either by LASER or e-Beam


## Chapter.5: Doping
The doping of a semiconductor determines its electrical behavior. The process of doping (the controlled incorporation of dopant atoms) is therefore decisive for the circuit behavior.
> Doping at crystal growth (bulk doping)  
> Neutron Transmutation Doping (NTD) (very specific)  
> Doping during Epitaxy (low above high doping level possible)  
> Doping by diffusion  
> Doping by implantation  
For a structured (masked) doping the latter two techniques are used.

#### Diffusion
The dynamic range of doping is limited by the solubility for the upper value(ca. 10^20 - 10^21 1/cm3 ) and by the purity of the bulk material for the lower value (10^12 – 10^13 1/cm3 )

Doping by Diffusion: Diffusion is the transport of particles along a concentration gradient (in a solid thermally activated).

Two step diffusion: 
> Predeposition: doping often proceeds by an initial predep step to introduce the required dose of dopant into the substrate.  
> Drive-in: a subsequent drive-in anneal then redistributes the dopant giving the required junction depth.  

- a) Out diffusion: This effect causes the junction depth to appear at a slightly larger value. undesired effect occurring at high temperature: dopant atoms diffuse from the material featuring high doping level to the material featuring low doping level; common in high temperature epitaxial deposition where it prevents sharp change in dopant concentration between epi layer and the substrate; temperature of epitaxial deposition must be reduce to control outdiffusion.
- b) Diffusion of a step like profile
- c) Diffusion in combination with oxidation: Boron deplets at the Si surface while phosphorus accumulates!
- d) Oxidation enhanced diffusion(LOCOS: LOCal Oxidation of Silicon): Local oxidation of Si injects point defects into the Si lattice below the growing interface. These point defects cause a locally larger effective diffusion coefficient which enlarges junction depth. Due to the misfit in binding length between Si-Si and Si-O during oxidation the concentration of interstitials and vacancies is significantly changed. This impacts the diffusivity of dopants.
- e) Concentration dependency of D:
- f) Lateral diffusion: Diffusion is an isotropic process. Therefore the dopants spread out not only vertically down into the silicon but also horizontally below the mask. As a rule of thumb the lateral extension of a junction is about 80% of the vertical junction depth.

Diffusion Processing: 1.Gas source doping; 2.Liquid source doping; 3.spin on glass doping

#### Ion implantation
Diffusion is an isotropic process acting also in lateral direction!
	=> Limits miniaturization (degree of integration)!
> Alternative:Directional incorporation of the doping by bombardment of the surface with high energetic doping element ions so that they penetrate into the silicon.
	=> Ion implantation

Ions of the doping atoms inside of a high vacuum system become highly accelerated and penetrate into the silicon surface.

Ion stopping is dominated by two mechanisms:
	1.Electronic stopping: Electronic excitation creates heat
	2.Nuclear stopping:    Crystalline si substrate damaged by collision
Ion stopping is dominated by two mechanisms:
	1.stopping dominates at high energies
	2.Nuclear stopping dominates at low energies
> Projected Range  
> Implantation Masks  
> Channeling  
> Further effects: 
	a) Sputter effect
	b) Impact damage
	c) Amorphisation Dose
	d) Profile tailoring by multiple implantation  
>Damage recovery:Annealing in the diffusion furnace (hours)
				􀀀 Rapid Thermal Anneal RTA(seconds)
				􀀀 Ultra Short Anneal -Laser/Flash(milliseconds)

Advantages of ion implantation:
	a)Photoresist as mask material possible (low temperature)
	b)High fines of structure (no lateral implantation)
	c)Possibility of self alignment
	d)High accuracy of the dose
	e)Very special profiles possible by multiple implantation
	f)Doping through a thin film possible
	
## Chapter.6: Epitaxy
Special case of CVD: Mono crystalline Film growth on a mono crystalline substrate.
	If Substrate material = Film material => Homo epitaxy
	If Substrate material ≠ Film material => Hetero epitaxy

Requires most highest purity of chemicals surfaces and tools and lowest defect concentration of the substrate.

#### 6.1 CVD Epitaxy
Prerequisite for uniformity -> Laminar gas flow!

Two parameters are technically more or less easily controllable:
	a)Gas flow velocity
	b)Temperature
	
**Reaction kinetics**:
Two regimes of deposition operation:
	a) Reaction limited
	b) Transport limited
Depending on the Mol fraction, the process can go from Monocrystalline via Polycrystalline up to etching!

**Pattern Displacement**: This „horizontal“ growth may cause pattern displacement.

To prevent autodoping it is necessary to deposit the wafer backside with a diffusion barrier.

**Epi Process**:
> 1. Removal of the native Oxide at ca. 1200 °C: SiO2 (s) + H2 (g) => SiO (g) + H2O (g)  
> 2. Sacrificial etching of Si by HCL  
> 3. Growth using SiHxCl4-x :  
	ex. SiCl4 (g) + 2 H2 (g) < = > Si (s) + 4 HCl (g) at 1250 °C  
	however also side reactions (Etching!) SiCl4 (g) + Si (s) => 2SiCl2 (g)  
	=> Typical Process performed at low SiCl4 concentration!  
	
**Hetero Epitaxy**:
	a) By Epi it is possible to generate low doped layers above highly doped layers.  
	b) Epi layers do not contain oxygen (in contrast to CZ wafers)  
	c) Doping is uniform and independent from the wafer position within the CZ ingot  
	d) Compound semiconductors enable „Band Engineering“  
	
**Si(x)Ge(1-x)**: Ge Epitaxy on Si is generally not possible. However mixing Si with low Ge content can
create strained lattice material. Maximum Ge fraction is related to the film thickness.

#### 6.2 MBE Molecular Beam Epitaxy
Physical deposition of the pure film material
1.Crystalline growth at relatively low temperature possible (400 – 800 ºC)
	-> no autodoping!  
2.Requires extremely „good“ vacuum 10-10 mBar or lower!
	-> UHV (Ultra High Vacuum)  

> Molecular-beam epitaxy takes place in high vacuum or ultra-high vacuum (10−8–10−12 Torr). The most important aspect of MBE is the deposition rate (typically less than 3,000 nm per hour) that allows the films to grow epitaxially. These deposition rates require proportionally better vacuum to achieve the same impurity levels as other deposition techniques. The absence of carrier gases, as well as the ultra-high vacuum environment, result in the highest achievable purity of the grown films. allowing precise control of the thickness of each layer, down to a single layer of atoms. 


## Chapter.7: CVD(Chemical vapor deposition)
Growth of amorphous or polycrystalline films on arbitrary substrates (temperature must match!)
	- large material diversity (Si, Oxides, Nitrides, Carbides, Metals, Silicides …)
	- arbitrary layer thickness with variable properties (composition, strain, …)
	- low process temperatures possible
	
Kinetics of CVD:
	a) Diffusion of educts to surface
	b) Adsorption at surface
	c) Surface events (diffusion, dissociation, reaction, nucleation and growth)
	d) Desorption of some products
	e) Release to the exhaust

Common CVD materials in microelectronics:
- Poly Si (p-Si)
- SiO2 > undoped (USG)  
	   > PSG Phosphorus doped Silicate Glass  
	   > BSG Boron doped silicate Glass  
	   > BPSG  
- Si3N4 Silicon Nitride
- SiNxOy Silicon Oxynitride
- W Tungsten
- WSi2

#### 7.1 CVD of Polysilicon
Typically as LPCVD reaction between 600-650 ºC: SiH4 → Si + 2H2

Used as:
> Gate electrode in MOSFET  
> Electrode in deep trench capacitors (DRAM)  
> Conduction line / Resistor  
> Getter layer (Autodoping)  
> MEMS devices (surface micromachining)  

Deposition parameters: 
> Temperature and pressure  
> Silane concentration  
> Dopant concentration  

#### 7.2 CVD of Siliconoxide SiO2
Used as:
> Insulation film  
> Passivation layer  
> Doping mask  
> MEMS μ-mechanics as sacrificial layer  
 
“Reflow” generates a „local planarization“ and rounds sharp corners for a better following (conformal) metallization. By thermal treatment the oxide film becomes viscous and surface tension smoothen the surface topology.

#### 7.3 CVD of Silicon Nitride Si3N4
Used as:
> Passivation (moisture barrier)  
> Part of LOCOS process  
> „Hard Mask“ in multilayer resist  
> „Stop layer“ at polish  
> MEMS: Mask for KOH Si etch  

#### 7.4 Plasma enhanced CVD – PECVD of SiO2 and SiNxHy
**Advantage: Low Temperature! Deposition on Al or even on polymers possible.**
**Properties can be controlled via the plasma conditions**

#### 7.5 CVD of Tungsten
Used as:
> Polycide/SILICIDE (gate material)  
> Contact metal to the Si substrate  

Properties: 
> excellent step coverage  
> selective deposition possible  
> no metalurgical reaction below 600ºC  

Generally 2 ways of CVD: 
	i) Pyrolysis(高温分解):Thermal decomposition of a supply gas(SiH4 -> Si + 2H2)
	ii) Reaction: Thermally induced heterogeneous reaction of supply gases( SiH4 + O2 -> SiO2 + 2 H2)
	
How to avoid these dependencies on many parameters: Temperature, local precursor impingement rate, sticking coefficient?
> Utilization of the self limitation lfivnnonf then chemisorption  

Atomic Layer Deposition:
> ALD is an ultrathin film deposition technique that is controlled by gas phase and sequential self-limiting chemical reactions of the precursors at the material surface. Most ALD processes typically require two precursors, which are supplied in sequence one at a time to contribute to surface coating. ALD 是一种超薄膜沉积技术，由气相和材料表面前驱体的顺序自限化学反应控制。 大多数ALD工艺通常需要两种前体，它们一次一个地依次供应以促进表面涂层。In ALD, the growth progresses layer by layer by alternatively pulsing the source gases. This enables ultra fine thickness control.**self limitation!:1.half-reaction A;2.purge or evacuation;3.half-reaction B;4.purge or evacuation**


## Chapter.8:Plasma based Depo & Etch
#### 8.1 Plasma Technology
**Partially ionized gas**
Plasma excited by electrical field: 
> Electrons "absorb" the energy from electrical field, but cannot release their (kinetics) energy by collision with Neutrals or Ions.  
**Plasma generation**:
> Vacuum resp. low pressure is a prerequisite for plasma generation!  
	
#### 8.2 Sputtering
sputtering is a phenomenon in which microscopic particles of a solid material are ejected from its surface, after the material is itself bombarded by energetic particles of a plasma or gas.[1] It occurs naturally in outer space, and can be an unwelcome source of wear in precision components.

#### 8.3 Etching
- chemical etching:
	a) purely chemical reaction
	b) high selectivity
	c) Isotropic etch profile
	d) dry strip/wet etching
- physical etching:
	a) bombarded with iner Ions like arogan
	b) physically dislodging material from surface
	c) Anisotropic etch profile
	d) low selectivity
	a) arogan sputtering etching
- reaction ion etching:
	a) combination of chemical and physical etching
	b) plasma process, ion bombardment, plus free radicals
	c) high and contrallable etch rates
	d) Anisotropic and controllable etch profile
	
> Reactive-ion etching (RIE) is an etching technology used in microfabrication. RIE is a type of dry etching which has different characteristics than wet etching. RIE uses chemically reactive plasma to remove material deposited on wafers. The plasma is generated under low pressure (vacuum) by an electromagnetic field. High-energy ions from the plasma attack the wafer surface and react with it. Application of sidewall passivation to enhance the anisot ropy respectively the aspect ratio.

>Balance between physical & chemical etch in one system: In this case controlled only by the pressure!

