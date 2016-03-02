Protocol: Exosome RNA cDNA Synthesis
====================================
Created by PI on 2012-10-25

Modified by __ on ____

# Notes:

Protocol has been modified from SeraMir Exosome RNA amplification Kit (SBI system Biosciences and SeraMir exosome RNA amplification (see References section).
Keep all reagents over ice. 

# Materials:

1. System Biosciences SeraMir Exosome RNA Amplification Kit (Cat# RA800A-1, location refrigerator #1 rm. 231 )
2. SYBR Master Mix ( Lot #14633900, opened: 11/2009, location refrigerator #5 rm. 231 ) 
3. Ice

# Methods:

1. poly A Reaction: 

| ADD:                            | PER REACTION: |
|:------------------------------|:---------------:|
|ExoRNA (eluted from spin column) | 5 mcL         |
|5x poly A buffer                 | 2 mcL         |
|MnCl2 (25 mM)                    | 1 mcL         |
| ATP (5 mM)                      | 1.5 mcL       |
| polyA polymerase                | 0.5 mcL       |

2. Incubate at 37°C for 30 minutes. This is saved as EXO1 on thermal cycler. 
3. Add 0.5µL SeraMir 3’ Adaptor Oligo 
4. Incubate at 60°C for 5 minutes. This is saved as EXO2 on thermal cycler. 
5. Incubate at room temperature for 2 minutes. Then place over ice. 
6. RT Reaction (20 mcL total volume): 

| ADD:                            | PER REACTION: |
|:------------------------------|:---------------:|
|polyA exoRNA     | 10 mcL (from above) |
|5x RT Master Mix            | 4 mcL         |
|5' SeraMir Switch Oligo                  | 1 mcL         |
| Reverse Transcriptase                   | 1 mcL       |
| DEPC water               | 4 mcL       |

7. Incubate at 42°C for 30 minutes, 95°C for 10 minutes, and hold at 15°C. This is saved as EXO3 on thermal cycler.
8. To test the exo-cDNA, perform qPCR using SYBR green (30 mcL total volume): 

| ADD:                            | PER REACTION: |
|:------------------------------|:---------------:|
|exo-cDNA    | 0.5 mcL (from above; store remainder at -20C) |
|2X SYBR Master Mix            | 15 mcL         |
|5' SeraMir Spike in assay primer                 | 1 mcL         |
| SeraMir 3' Reverse qPCR primer                 | 0.5 mcL       |
| DEPC water               | 13 mcL       |

9. Load the samples into the qPCR machine with supporting tubes as needed
10. Open "Step One" software. 
   - Select "Advance Settings". Name samples and save data in "Aric Gregson" folder.  
   - Select "Quantitation with ΔCt" 
   - Select "96 well plate" 
   - Select "SYBR GREEN" Make sure the "Melt Curve" box is checked. 
   - Select "2 hour run" 
   - Select "Plate Settings" and list all targets and samples. 
11. Exosome cDNA amplification (25 mcL total volume):

| ADD:                            | PER REACTION: |
|:------------------------------|:---------------:|
|ExoRNA amplified cDNA    | 2 mcL (from above) |
|2X Taq Master Mix            | 12.5 mcL         |
|5'PCR Primer Mix                 | 1 mcL         |
| DEPC water               | 13 mcL       |

12. Place the reaction in a thermal cycler:
   - 95°C for 5 minutes 
   - 35 cycles of:
      - 95°C for 25 seconds
      - 60°C for 20 seconds
      - 72°C for 30 seconds
   - 72°C for 30 seconds 
   - 4°C hold 
   - This is saved as EXO4 on thermal cycler. 
13. Store amplified cDNA in -20°C freezer. 
