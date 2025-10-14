## Michael Neumann: Mechanism of single photon emission from hexagonal boron nitride (Tutorial Lecture)

- At the time, the $g_2(0)$ antibunching was interpreted as a direct analogue of the one in $N_V$ centers.
- Variable SPEs: 1.6 eV to 2.2 eV, observed after many hBN sample preparation protocols, typically with heat treatment around 850 $^\circ$C
- ⚠️ The lack of agreement on "what are these emitters" is imputable to their variability
- Well studied PAH-SPEs: terrylene, anthracene, DBT (di-benzo-terrylene), di-benzo-ovalene
- Organic residues are ubiquitous in processing 2D materials
- They are extrinsic molecules and they are also supposed to sit outside of the sample: the most natural place for them is the sample-substrate interface!
- Two different types of cleaning cycles:
	- cleaning in oxygen at 700 $^\circ$C
	- (*live-cycle*) immersing it in organic solvent after the same cleaning
- **Suspended hBN: virtually no emitters!**
- They thinned down the hBN (see SI) and they see that the density of emitters doesn't scale down that much --> they reside mainly at the sample-substrate interface!!!
- After removing hBN with metal foil, the emitters/contamination are left on the substrate, while the hBN on the metal foil now looks dark (but the Raman signature is still there!)
- **Approach to hBN-SPE sample preparation**
- unfortunately, hBN can have a passive role in the presence of contaminants (every emission is transmitted), whereas for ex. metals are able to quench emission
- we need cleaning steps that make samples intentionally clean
- worst sources of contamination:
	- fingerprints! wearing gloves is important
	- never share tweezers (fingerprints transfer!)
	- do not mix tools among experiments (avoid cross-contamination, especially when dealing with organic solvents!) --> this improves the overall cleaniness 
	- oil droplets from compressed gas guns (injected by compressors) can deposit! use **filtered guns** for **sample drying**
	- carbon tape can leave excessive residue on chip back-side! clean carefully before baking!
	- graphitised residues can give rise to:
		- layer measurable in AFM
		- D band in Raman response! you need a lot of graphitised rings to get that
	- furnace parts need to be thoroughly cleaned!
	- tape:
		- don't use scotch magic tape --> it is dirty as fuck
		- wafer dicing tape (the so-called "blue Nitto tape") is normally more adequate
	- heat treatment in Ar/H$_2$ atmosphere at $\sim 400 ~^\circ$C  doesn't really remove residues, maybe it just spreads them around (so that's why u see less or no Raman response at all)
	- a good treatment is:
		- reduce tape and other residue sources
		- clean flakes in **trichloroethylene** (Daejung Chemicals 8553-4400) --> very good for tape residues removal! **key step**
		- then u need to remove solvent residues: first check optically, in some cases the flake is already clean and it's better to not pursue any further
		- PL mapping is a very good tool to spot such contamination
	- after these steps, one can proceed with the "live" cycle, where emitters are deterministically generated
	- better to not wait too much in between the cleaning steps and the "live" cycle, to avoid further chances of unwanted contamination
	- **tricholoroethylene** (TCE): it diffuses under the flakes and can remove a lot of contaminants at the interface, without leaving much residues!
	- Insgesamt: the combination of TCE and oxygen baking seems to be superior to other cleaning techniques
	- effects of baking in Ar/O$_2$ atmosphere: burns off thin layers of solvent residue from substrate and top of hBN flakes, and appears to have partial cleaning effect under hBN! at least it is able to clean down to 2-3 µm from the flake edge inwards --> very useful for small flakes!!
	- **easy methods to visualise adhesive residues**:
		- contrast enhancement in bright-field images
		  ![[Pasted image 20251002104518.png|300]]
		  Neumann, M., *et al*. (2023). *Organic Molecules as Origin of Visible-Range Single Photon Emission from Hexagonal Boron Nitride and Mica*. ACS Nano, **17** (12), 11679–11691. https://doi.org/10.1021/acsnano.3c02348 (SI)
		- on colorful flakes it's difficult to see residues --> use dark-field imaging!
		  ![[Pasted image 20251002105123.png]]

## Manjari: High Throughput Screening of Spin Defects for Quantum Applications (CC modelling)

## Cheng Engineering Addressable Color Centers in the hBN Lattice with Nanographene (CC modelling)

- Nano Lett 2022 22 23 9227-
- Materials Today Sustainability 28 (2024) 100988
- They used: oxygen plasma + graphite box annealing --> **unstable emission** (fast bleach away in short time) and **unknown process in graphite box**!
- they use now the nanofrazor for nanoscale patterning
- they pattern a thermally sensitive polymer (PPA) on hBN --> they pattern very small (2 nm!) structures
- then they use SF$_6$ to etch and transfer the pattern on the hBN!!
- they etch holes in the hBN --> they light up in DF
- 🧐 u can see contamination on hBN flakes from optical images...
- for **carbon doping**: 
	- oxygen plasma before growth
	- standard graphene growth process
	- Ar-annealing at 1000 $^\circ$C  
- Slide 11: the hBN proves to attract all the carbon/graphite (u see G modes only on the hBN), but from the Raman spectra there is no visible difference between the patterned holes and the rest of the hBN around
- PL mapping after each process: a 💩 lot of contamination and molecule-based emitters, but after annealing much of this 💩 goes away. AND apparently some of the patterned holes light up compared to the surrounding hBN, but very mild, very dim
- in the end, I guess they want to achieve carbon doping in the holes (they want the smallest holes as possible)

## Monika: Optical Investigation of Single Defects in hBN (CC experiments)

- Sample #5: hBN exfoliation and cleaning --> pl mapping #1 --> nanofrazor patterning --> ozone generation --> pl mapping #2 --> heated ozone generation and annealing --> PL mapping #3
- u can KINDA see the patterned area --> BUT it is just the substrate shining through the flake because it is thinner in those spots(?)
- they tried ODMR --> no ODMR BUT mild antibunching(?)
- Sample #6: hBN exfoliation and cleaning --> pl mapping #1 --> nanofrazor patterning --> oxygen plasma --> pl mapping #2 --> Ar annealing (in graphite box?)
- they got a lot of emitters (contamination probably 😭)
- they measure good $g_2$! but what about the durability of the emitters??
- from the $g_2$ they get long delay bunching --> probable metastable state --> probable ODMR behaviour (see Stern *et al.*...) but no ODMR(?)...
- the bright spot from Cheng! --> spectra looks interesting, but the emitter was very unstable (contamination 😭)

## Ilia: Charge state control of $V_B^-$ defect in hBN (CC experiments)

- N$_2$ irradiation and 0/3/12 s of O$_2$ plasma on a 100 nm flake
- they etch the flake a bit (91.2 --> 88.1 nm) and this results in mild PL quenching --> they explain it as thin film effect --> the changed interference behaviour between hBN and substrate lowers the efficiency
- N$_2$ and O$_2$ irradiation on a 40 nm thick flake
- planar gating of N-irradiated hBN flake with one electrode (very *naïve* approach)
- planar gating of N-irradiated hBN flake with two electrodes (not-so *naïve* approach) but no real change
- 100 nm hBN flake after N$_2$ FIB of 1 pC/µm$^2$ with MLG on top --> here they measure up to 3-4% PL quenching, and the lower the opt. power the more measurable is the quenching (it comes at lower V)
- nature.com/articles/s41377-022-00877-7
