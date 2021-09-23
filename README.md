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
	SiO2 + 2C → Si + 2CO
B: Making electronic grade silicon EGS: 电子级硅 --> Polycristalline Silicon
	Si(MGS) + 3HCl → SiHCl3 + H2
	4SiHCl3 + 2H2 → 3Si + SiCl4 + 8HCl
C: Growing the crystal
	1.Czochralski method.柴可拉斯基法（英語：Czochralski process），简称柴氏法，又称直拉法或提拉法，是一种用来获取半导体（如硅、锗和砷化镓等）、金属（如钯、铂、银、金等）、盐、合成宝石单晶材料的晶体生长方法。CZ grown Si contains oxygen!The quartz crucible dissolves during crystal growth
	2.Float-zone silicon is very pure silicon obtained by vertical zone melting. The process was developed at Bell Labs by Henry Theuerer in 1955 as a modification of a method developed by William Gardner Pfann for germanium. Making oxygen f ree Si crystal! 
	

##### Making of the wafers:
1.Crystal Growth; 2.Single Crystal Ingot; 3.Crystal Trimming; 4.Flat Grinding; 5.Wafer Slicing; 6.Edge Rounding; 7.Lapping; 8.Wafer Etching; 9.Polishing; 10.Wafer Inspection.

##### Relation: Resistance vs. Doping

##### Defects enable the trapping of impurities Gettering:Extrinsic - / Intrinsic
1.Extrinsic:(at the wafer backside)high-pressure water jet treatment 
2.Intrinsic: precipitation + Denuded Zone(缺陷有捕捉雜質的作用)

## Chapter.3: Oxidation
SiO2 used as: > Part of the MOS structure (gate-oxide - as thin as possible)
			  > Isolation between the active devices (field-oxide - as thick as possible)
			  > Mask material (Diffusion, Ion-Implantation, Etching, …)
Layer growth takes place by exposure to Oxygen at elevated temperature either as:
		O2 : Si + O2 → SiO2 (Dry oxidation) or
		H2O : Si + 2H2O → SiO2 + 2H2 (Wet oxidation)

#### Growth model after Deal and Groove
Initial growth not hampered by diffusion
	=> growth reaction limited
	=> linear growth
Further growth hampered by diffusion
	=> concentration of oxidant at the SiO2/Si interface the lower, the thicker the oxide.
	=> parabolic growth
	
#### Dependcy on process variable
a) wet/dry
	Differences appear in all parameters: D, N, Ks and C*.
	Although DO2 > DH2O the wet oxidation rate is lager than the dry oxidation rate!
	The higher wet oxidation rate is primarily due to the higher solubility (C*) of H2O in SiO2 compared to that of O2 .
	The effect extends to the linear as well as to the parabolic regime.
b) Temperature
	Diffusion as well as chemical reaction are thermally activated.
c) Pressure
d) Orientation
e) Doping

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
	􀀀 Resin (Mat rix Material)
	􀀀 Solvent for the layer application
	􀀀 Photoactive component (PAC)
Basic function: UV light changes through the PAC the property of the resist f ilm so that the solubility in a liquid differs significantly between exposed and unexposed areas
1.Negative resist: Effect of cross linking(exposed regions): Solubility in organic solvent significantly reduced.
However solvent creates swelling even in exposed regions. This reduces pattern accuracy. - > Not used for pattern below 2μm.
2.Positive resist: A positive photoresist is a type of photoresist in which the portion of the photoresist that is exposed to light becomes soluble to the photoresist developer. The unexposed portion of the photoresist remains insoluble to the photoresist developer.
3.DUV resist: Modified resin; Chemically amplified resist

#### Pattern transfer still by Optical Lithography
Smallest feature (CD) is proportional to the SQRT of the product of wavelength times gap between mask and substrate
bmin = 3/2*sqrt(λ*(g+d/n))
Resolution is diffraction limited:
1.Large separation of light beams => Several Diffraction Orders => High contrast at the image
2.Smaller separation of light beams => fewer Diffraction Orders => Low contrast at the image

CD: Critical Dimension(smallest structure width on a device): CD=K1*λ/NA
数值孔径（英語：NA, Numerical aperture）是光学系统的一个无量纲数，用以衡量该系统能够收集的光的角度范围。在光学的不同领域，数值孔径的精确定义略有不同。在光学显微镜领域，数值孔径描述了物镜收光锥角的大小，而后者决定了显微镜收光能力和空间分辨率；在光纤领域，数值孔径则描述了光进出光纤时的锥角大小。

DOF: Depth of Focus (Tolerance range of the focal distance): DOF=K2*λ/NA^2
Image contrast only within the DOF sufficiently high enough

Projection lithography concepts: Full Field imaging is efficient but has some technical limitations!
Resist profile: Resist profile depends on Image- and Resist quality. 
				> Steep Line prof ile obtained by high resist contrast
				> Resist cont rast does not af fect the bot tom CD
				> However , line width can be cont rolled by light intensity and/or development time
Interference: 1. a dependency of the mean intensity on the resist thickness and
			  2. what is called: standing waves --> cause over-exposure and under-exposure
			  solution: Bottom Anti Reflective Coating
						DQN: Post Exposure Bake activates diffusion of Carboxyl Acid
						
#### Pattern Enhancement
􀀀 Phase shifting mask (PSM)
􀀀 Off axis illumination: By Changing the Illumination Conditions the Diffraction Orders captured by the lens can be improved
􀀀 Optical proximity correction: take advantage of the interference generated by phase differences to improve image resolution in photolithography. 
􀀀 Immersion lithography: replaces the usual air gap between the final lens and the wafer surface with a liquid medium that has a refractive index greater than one.
􀀀 Resist trimming: resist line made narrower by isotropic etching of the resist in oxygen plasma. In both case (line/space) remains constant 
􀀀 Double exposure: 
􀀀 EUV: Extreme UV (λ=13,5 nm) Multilayer reflective mask necessary

#### Photomasks
Classical approach: Exposure by UV light through mechanically adjusted slits.
Today: Mask writing either by LASER or e-Beam


## Chapter.4: Doping
The doping of a semiconductor determines its electrical behavior. The process of doping (the controlled incorporation of dopant atoms) is therefore decisive for the circuit behavior.
> Doping at crystal growth (bulk doping)

> Neutron Transmutation Doping (NTD) (very specific)

> Doping during Epitaxy (low above high doping level possible)

> Doping by diffusion

> Doping by implantation

For a structured (masked) doping the latter two techniques are used.