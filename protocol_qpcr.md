Protocol: qPCR using DMBT1 as target and ribosome RNA 18s as reference
======================================================================

By DC on 2015-05-28

# Notes

- Modified from “Comparative Ct Experimental Set Up for qPCR using StepOnePlus” by Slav
- Keep all reagents over ice. 
- Be careful to avoid contamination by DNase
- Vortex and briefly spin down reagents before use
- Cover reagents with foil 
- This protocol uses DMBT1 and 18S as examples. 

# Materials

1. 20x Target Mix (TaqMan Gene Expression Assays DMBT1 number: 01069606)
   - freezer #5
2. 20x Endogenous Mix (Applied Biosystems Ribosome rna 18s)
   - Fridge #1
3. cDNA (prepared from earlier)
4. RNase-free water (DPEC treated water)
5. 2X TaqMan Universal Master Mix 
   – Fridge #1
6. MicroAmp Optical 8 cap strip and cap
7. 1.5ml centrifuge tubes
8. Fischer Scientific Mini Centrifuge
9. Fischer Scientific Vortex Genie
10. StepOnePlus™ Real-Time PCR System
11. Ice

# Methods

| Component | Volume (mcL) |
|:---: | :---: |
| 20X Target Mix (DMBT1) | 1.0 |
| 20X Endogenous Mix (18S) | 1.0 |
| cDNA Template | 2.0 |
| RNase-free water | 6.0 |
| 2X TaqMan Universal Master Mix | 10.0 |
| Total Volume | 20 |

1. Make “master mix” of all reagents without cDNA first, as per the above table, in a 1.5-mL centrifuge tube
   - 20x Target Mix, 20x Endogenous Mix, RNase-free water, 2x TaqMan Universal Master Mix
   - Mix starting with the reagents with the greatest quantity
   - Make sure that the volume of the master mix is one more unit than what would be actually used. For example, if processing 2 positive controls, one sample, and 1 negative control, the volume of the master mix should be (10+6+1+1)*5 = 90-mcL
2. Vortex and spin down master mix tube
3. Aliquot 18ul of mastermix each into the wells of a MicroAmp strip
4. Add 2ul of cDNA into their respective wells
5. Cover the wells with MicroAmp caps and seal thoroughly. Vortex gently and spin at 3500rpm for 10 seconds to eliminate air bubbles
6. Set up the program
   - Turn on the computer and log in (just press OK)
   - Double-click on StepOnePlus Software v2.3
   - Click on Advanced Set Up
   - Click the Experimental Name field, and then enter the experiment name
   - Select StepOne instrument (96 wells)
   - Select Quantification: Comparative Ct if you are not using standard curve
   - Select Taqman Reagents
   - Select Standard, 2hour run
   - Click on Plate Set Up
   - Select Add New Target
   - Type Target Name(s) and select FAM or VIC and TAMRA or MGB
   - DMBT1 is FAM and 18s is VIC
   - Type Sample Name(s)
   - Click on Assign Targets and Samples
   - Select wells that you are using and label them with Target Names and Sample Names
   - Select your Endogenous control (housekeeping gene you are using)
   - Select your Control samples
   - Make sure that ROX is selected as a Passive Reference
   - Click Run Method and check the conditions:
   
   | Step | Amp Erase UNG Activation | AmpliTaq Gold Enzyme Activation | PCR Denature | PCR Anneal | 
   |:---|:---:|:---:|:---|---:|
   |  |  |  |  40 Cycles | 40 Cycles |
   |Time |  2 min | 10 min | 15 sec | 1 min |
   | Temperature | 50 C | 95 C | 95 C | 60 C |
   
   - Click Run
   - Save your template and click OK
   - The usual run time for qPCR reaction is 1 hour and 15 minutes
