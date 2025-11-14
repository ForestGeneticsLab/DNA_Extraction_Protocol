# DNA Extraction Guide


## Table of Contents
- [Basic Principles of DNA Extraction](#basic-principles-of-dna-extraction)
- [Qiagen DNeasy Plant Pro Kit Protocol](#qiagen-dneasy-plant-pro-kit-protocol)
- [Modified CTAB DNA Extraction Protocol](#modified-ctab-dna-extraction-protocol)
  - [Pre-Wash Protocol](#pre-wash-protocol)
  - [CTAB Protocol](#ctab-protocol)
  - [Ethanol Precipitation Protocol](#ethanol-precipitation-protocol)


We are using the **Qiagen DNeasy Plant Pro Kit** and a **modified CTAB protocol** to extract genomic DNA from plant tissues. There is a trade-off between speed and convenience with the Qiagen versus higher yield and lower cost with the CTAB protocol. The Qiagen is quicker and more convenient, allowing extraction of ~24 samples in 3–4 hours, though it is relatively expensive and yielded lower DNA concentrations. By contrast, the CTAB protocol requires substantially more time (~12 hours for 24 samples) but produces much higher DNA yields at lower cost, albeit with greater labor and potential impurities.


## Basic Principles of DNA Extraction

DNA (DeoxyriboNucleic Acid) or RNA (RiboNucleic Acid) extraction process involves disruption of tissue and breaking of the cell wall, cell and nuclear membranes to release the DNA/RNA and then isolating the nucleic acid from the rest of the unwanted cell debris. 

Here is a simple overview of the basic principles and science behind DNA extraction:

DNA extraction is the process of isolating DNA from cells or tissues. In plants, this involves:
1. **Sample homogenization and cell lysis** – breaking the tough plant cell wall (often using grinding with liquid nitrogen or bead beating), and using detergents and buffers to dissolve cell membranes and release DNA into solution (lysis).
2. **Removal of contaminants** – separating DNA from proteins, polysaccharides, and other cellular components (centrifugation).
3. **DNA precipitation/binding and cleaning** – capturing DNA on a solid support (e.g., silica column) or with alcohol precipitation.
4. **Elution** – washing and releasing purified DNA into a clean solution for downstream applications. Then concentration of DNA and purity are measured.
5. **Storage** - Store DNA at **–20 °C** for long-term use or **4 °C** for short-term use.

![DNA Extraction Workflow](DNA_extraction.jpg)

---
---
---

# [Qiagen DNeasy Plant Pro Kit Protocol](file:///C:/Users/rsbis/AppData/Local/Temp/MicrosoftEdgeDownloads/e9a9b115-43dd-4784-b72e-a6e0c7888c9c/HB-2552-002_HB_DNY_Plant_Pro_0819_WW%20(1).pdf)

![Qiagen DNeasy Plant Pro Kit Procedure](Qiagen.jpg)

<br>

1. Add ~30 mg of leaf tissue to a bead tube  (If tissue is tough, grind with a mortar and pestle before transfer). 
2. Add **450 µl Solution CD1** and **50 µl Solution PS**.  
   - For samples rich in polyphenolic compounds, increase PS up to **100 µl** and reduce CD1 accordingly (total solution volume = 500 µl).  
3. Incubate at **65 °C for 10 minutes**, then briefly vortex (5 seconds).  
4. Homogenize tissue in the bead mill at **speed 3.1 m/s for 2 minutes**.  
5. Centrifuge at **12,000 × g for 2 minutes**.  
6. Transfer the supernatant to a 1.5 ml collection tube (Some plant particles may remain in the supernatant; this is acceptable)  
7. Add **200 µl Solution CD2** (stored at 4 °C) and vortex for 5 seconds (For problematic samples, increase CD2 up to **250 µl**)
8. Centrifuge at **12,000 × g for 1 minute**.
9. Carefully transfer the supernatant (≈400–500 µl) to a new 1.5 ml tube, avoiding the pellet.  
10. Add **500 µl Buffer APP** and vortex for 5 seconds.  
11. Load **600 µl lysate** onto an MB Spin Column and centrifuge at **12,000 × g for 1 minute**.  
12. Discard the flow-through, then load the remaining lysate onto the same column.  Centrifuge again at **12,000 × g for 1 minute**.  
13. Place the MB Spin Column into a **2 ml collection tube** (Avoid splashing flow-through onto the column). 
14. Add **650 µl Buffer AW1** to the MB Spin Column and centrifuge at **12,000 × g for 1 minute**.
15. Discard flow-through and rplace the MB Spin Column back into the same 2 ml collection tube.  
16. Add **650 µl Buffer AW2** to the column. Let sit for **5 minutes**, then centrifuge at **12,000 × g for 1 minute**.
17. Discard flow-through and place the MB Spin Column back into the same 2 ml collection tube.  
18. Repeat step 16-17: add another **650 µl Buffer AW2**, let sit for 5 minutes, then centrifuge at **12,000 × g for 1 minute**, discard flow-through and place the column back into the same 2 ml collection tube.  
19. Now, centrifuge the empty column at **13,300 × g for 2 minutes** to dry the white filter membrane in the MB Spin Column.  
20. Place the MB Spin Column into a new clean 1.5 ml elution (collection) tube (Wipe the column exterior before placing into the tube).  
21. Add **50 µl Buffer EB** directly to the center of the white filter membrane.  
22. Centrifuge at **12,000 × g for 1 minute** to elute DNA.  
23. Discard the spin column. The eluted DNA is now in the 1.5 ml collection tube.  
24. Measure DNA concentration and purity (e.g., Nanodrop spectrophotometer: better for absorption or Qubit fluorometer: more precise for concentration).  
25. Store DNA at **–20 °C** for long-term use (4 °C is OK for short-term use).

---
---
---

# Modified CTAB DNA Extraction Protocol

:point_right: Reference: [Doyle and Doyle 1987](https://webpages.charlotte.edu/~jweller2/pages/BINF8350f2011/BINF8350_Readings/Doyle_plantDNAextractCTAB_1987.pdf), and [Cullings 1992](https://doi.org/10.1111/j.1365-294X.1992.tb00182.x), With modifications by Jeremy Johnson

**Purpose:** Cost-effective method for extracting DNA from plants with high polysaccharide content.
<br>

### Reagents and Solutions
#### <ins>Washing Buffer:<ins>

We need 1 mL Washing buffer per sample. Prepare X mL (more than N mL) of washing buffer for N samples (rxn) with appropirate proportion of reagents, following the table below;

<table>
  <thead>
    <tr>
      <th rowspan="2">Solutions</th>
      <th colspan="5">Volume of Stock Solution to be Prepared</th>
    </tr>
    <tr>
      <th>X mL</th>
      <th>1000 mL</th>
      <th>100 mL</th>
      <th>50 mL</th>
      <th>25 mL</th>      
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Tris HCl (1M)</td>
      <td>0.1*X mL</td>
      <td>100 mL</td>
      <td>10 mL</td>
      <td>5 mL</td>
      <td>2.5 mL</td>
    </tr>
    <tr>
      <td>EDTA (0.5M)</td>
      <td>0.1*X mL</td>
      <td>100 mL</td>
      <td>10 mL</td>
      <td>5 mL</td>
      <td>2.5 mL</td>
    </tr>
    <tr>
      <td>NaCl (5M)</td>
      <td>0.2*X mL</td>
      <td>200 mL</td>
      <td>20 mL</td>
      <td>10 mL</td>
      <td>5 mL</td>
    </tr>
    <tr>
      <td>H₂O</td>
      <td>0.6*X mL</td>
      <td>600 mL</td>
      <td>60 mL</td>
      <td>30 mL</td>
      <td>15 mL</td>
    </tr>
  </tbody>
</table>


---



#### <ins>CTAB Extraction Buffer:<ins>

We need 0.5 mL CTAB buffer per sample. Prepare X mL (more than (N/2) mL) of CTAB buffer for N rxn with the proportion of reagents as shown in the following table;


<table>
  <thead>
    <tr>
      <th rowspan="2">Solutions</th>
      <th colspan="6">Volume of Stock Solution to be Prepared</th>
    </tr>
    <tr>
      <th>X mL</th>
      <th>1000 mL</th>
      <th>100 mL</th>
      <th>50 mL</th>
      <th>25 mL</th>  
      <th>12 mL</th>       
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Tris HCl (1M)</td>
      <td>0.1*X mL</td>
      <td>100 mL</td>
      <td>100 mL</td>
      <td>5 mL</td>
      <td>2.5 mL</td>
      <td>1.25 mL</td>
    </tr>
    <tr>
      <td>EDTA (0.5M)</td>
      <td>0.04*X mL</td>
      <td>40 mL</td>
      <td>4 mL</td>
      <td>2 mL</td>
      <td>1 mL</td>
      <td>0.5 mL</td>
    </tr>
    <tr>
      <td>NaCl (5M)</td>
      <td>0.28*X mL</td>
      <td>280 mL</td>
      <td>28 mL</td>
      <td>14 mL</td>
      <td>7 mL</td>
      <td>3.5 mL</td>
    </tr>
    <tr>
      <td>CTAB</td>
      <td>X/50 g</td>
      <td>20 g</td>
      <td>2 g</td>
      <td>1 g</td>
      <td>0.5 g</td>
      <td>0.25 g</td>
    </tr>
    <tr>
      <td>H₂O</td>
      <td>0.58*X mL</td>
      <td>580 mL</td>
      <td>58 mL</td>
      <td>29 mL</td>
      <td>14.5 mL</td>
      <td>7.25 mL</td>
    </tr>
  </tbody>
</table>


---

<br>


#### <ins>Other Stocks required:<ins>
→ 2-mercaptoethanol (β-mercaptoethanol) (it's in the fumehood)<br>
→ polyvinylpyrrolidone (PVP)(k-30, S<sub>ABC</sub>) (by weight balance)

#### <ins>TE Buffer:<ins>

We need 100 µL of 1x TE buffer per sample (rxn). Prepare X mL (more than (100xN) µL) of TE buffer needed for samples.


> | Solutions                | X mL for N rxn      | 100 mL for 1000 rxn | 10 mL for 100 rxn | 5 mL for 50 rxn   |
> |--------------------------|---------------------|---------------------|-------------------|-------------------|
> |         Tris-EDTA (100x) |   X/100 mL          |   1 mL              |   0.1 mL          |   0.05 mL         |
> |         H20              |   99X/100 mL        |   99 mL             |   9.9 mL          |   4.95 mL         |
> 

<br>

---

### <b>Be sure to autoclave all buffers!</b>

<br>

---

Functions of reagents in buffers:

:small_blue_diamond: CTAB (Cetyl Triethyl Ammonium Bromide): *Cationic detergent, removes polysaccharides (cellulose) and secondary metabolites, breaks cell membrane*

:small_blue_diamond: 1 mM Tris HCl :- *Maintains pH*

:small_blue_diamond: 0.5 M EDTA (EthyleneDiamineTetraacetic Acid): *Chelating agent. Binds metal ions like Mg<sup>++</sup> that can inactivate enzymes (like nucleases: DNase, RNase)*

:small_blue_diamond: 5M NaCl: *Helps remove protein bound to the DNA. Na+ binds with negative phosphate of DNA and precipitate
Heikrujam et al. 2020: If cells are in hypotonic solution, cell bursting… If in hypertonic solution, water oozes out from the cell, cells shrink and crumple. 0.5 M provides ionic strength needed for CTAB to precipitate polysaccharides. In protocols developed for getting rid fo polysaccharides, higher concentration has been recommended.*

:small_blue_diamond: PVP (PolyVinylPyrrolidone): *Absorbs polyphenolic contamination by binding through hydrogen bond.*

:small_blue_diamond: β-mercaptoethanol (2-mercaptoethanol): *reducing agent, removes tannins and polyphenols*


---
---

<br>

## Extraction begins:

***Prep*:** After pre-wash, the regular extraction procedure continues immediately. Therefore, before starting the pre-wash, the regular extraction buffer needs to be prepared, autoclaved (as mentioned above) and during the pre-wash period, the extraction buffer needs to be heated in an incubator.

*Preheat the heat thermos-mixer to 65°C*


---



### Pre-Wash Protocol

1.  Measure out washing buffer stock (1 mL per reaction) and 10% overage (N + (0.1*N) mL). (eg. for 24 samples, 24 + 2.4 = 26.4 mL)
2.	Stuff bead mill tubes with foliage sample as needed (~30 mg for pine, spruce species), being careful to not cross contaminate samples. If using hands to stuff tubes, change gloves for each sample. (If tissue is tough, grind with a mortar and pestle before transfer)
3.	Add 1 mL Washing buffer, then 0.01 g PVP, and 4.5 µL β-mercaptoethanol.<br> Strategy for this can be like: Adding 0.01*(11N/10) g of PVP, then 4.5*(11N/10) µL of β-ME (in fumehood) to the measured washing buffer.
<br> → *Instead of using bead mill tissue disruption, we can also grind the plant material using liquid nitrogen and clean sterile Micropestle. Add the ground tissue in a tube. Then 1 ml of washing buffer is added to tube. Shake vigorously to mix (use pipette tip to mix in order to guarantee complete mixing)*
4. Insert bead mill tubes into bead mill, making sure that the tubes are in a balanced arrangement.
5. Run bead mill for 2 minutes at 3.55 m/s.
6. Transfer bead mill tubes to centrifuge, making sure that the tubes are in a balanced arrangement.
7.	Spin tubes in centrifuge for 10 min at >10,000 rpm.
8.	Pipette off supernatant and keep the pellet.
9. Proceed with regular extraction protocol immediately


---


### CTAB Protocol

1.	Prepare **CTAB buffer**: [0.5 mL/rxn+10% CTAB stock. Add 0.02g PVP and 2.5 uL β-mercaptoethanol for each reaction](#extraction-buffer).
2.	Add 500 µL CTAB buffer to each tube
3.	Mix vigorously (use pipette tip to guarantee complete mixing)
4.	Incubate samples at 65°C using the Eppendorf thermos mixer for 3 hours
5.	Add 500 µL of 24:1 Chloroform: Isoamyl Alcohol and mix well by vortexing (use filter tips) 
6.	Centrifuge for 5-10 min at maximum speed<br>
a.	Following centrifugation, you should have 3 layers: **aqueous phase** (top), **debris and proteins** (middle), and **chloroform** (bottom).<br> →  *Chloroform: nonpolar hydrophobic solvent in which nonpolar proteins and lipids get dissolved, leaving isolated DNA protected in aqueous phase*. <br>
b.	Go onto next step quickly so the phases do not remix
8.	Pipette off aqueous phase taking care not to suck up any of the middle proteins debris and bottom chloroform phases. Pipetting slowly helps with this.
9.	Place the aqueous phase into a new labeled Eppendorf tube
10.	Repeat steps 5-6
11.	Pipette off aqueous phase (~300 µL) taking care not to suck up the protein or chloroform phases<br>
a.	Pay particular attention to the slight protein layer at this point. Pipette less aqueous phase in order to avoid the other phases will improve quality of DNA
12.	Place the aqueous phase into a new labeled Eppendorf tube
13.	Estimate the volume of the aqueous phase ~ 300 µL
14.	Add 0.08 volumes (~24 µL) of cold 7.5 M ammonium acetate
15.	Add 0.54 volume (~162 µL) of cold isopropanol (2-propanal) (isopropanol precipitates DNA)
16.	Mix well
17.	Incubate in -20°C freezer for 1 hour<br>
a.	Longer times will yield more DNA, but also more contaminants
18.	Centrifuge for 3 min at maximum speed
19.	Pour or pipette off the liquid. Do not lose the DNA pellet
20.	Add 700 µL of cold 70% Ethanol, and mix well
21.	Centrifuge for 1 min at maximum speed
22.	Pour or pipette off the liquid, Do not lose the DNA pellet
23.	Add 700 uL of cold 99% Ethanol and mix
24.	Centrifuge for 1 min at maximum speed
25.	Pour or pipette off the liquid, do not lose the DNA pellet
26.	Dry the pellet for 30 min in the SpeedVac<br>
a.	Turn on the rotor first and wait for the vacuum to start<br>
b.	Set the temperature to 30°C<br>
c.	Turn on the motor second and start suction<br>
d.	Reverse steps to stop
<br> → *If SpeedVac is not availible, allow pellets to dry with Eppendorf tube cap open in fume hood for 1-2 hours.*
27.	Resuspend samples with 100 µL of 1x TE buffer. Allow to resuspend for 1 hr at 55°C or overnight in refrigerator before running a test gel using 5 µL of the DNA
28.	Clean DNA using an **Ethanol precipitation protocol** (below) if needed


---

### Ethanol Precipitation Protocol

1.	If the volume of the DNA is less than 200 μl, bring the volume up to 200 μl with sterile dH<sub>2</sub>O.
2.	Add 1/10<sup>th</sup> volume of 3M sodium acetate to the DNA solution and mix. (i.e. add 20 μL to the 200μL solution)
3.	Add 2 volumes (i.e. 400 μL) of -20°C 100% ethanol (EtOH) and vortex for 10 seconds. Put the tube in a -20°C freezer overnight or a -70°C freezer for 20 minutes.
4.	Spin in a microfuge for 5 minutes. Invert the tube with the lid closed and look for the pellet. While upside down, pour out the EtOH but save the pellet!!
5.	Wash the pellet with 500 μl of 4°C 70% EtOH, gently roll the tube, then dump the EtOH, and SpeedVac the pellet. SAVE THE PELLET!
6.	You can SpeedVac the DNA to dryness if any liquid remains.
7.	Resuspend DNA in appropriate volume of TE or water. (100 μL as before)

