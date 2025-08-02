---
# MIOP terms
methodology_category: Omics Analysis
project: MURI MMARINeDNA
purpose: polymerase chain reaction NCIT:C17003 
analyses: organism detection by PCR assay [OBI:0002740]
geographic_location: North East Pacific Ocean [GAZ:00013765]
local_environmental_context: California current [GAZ:00000346]
environmental_medium: sea water [ENVO:00002149]
target: mitochondrial control region d-loop  [SO:0002294]
creators:  Nastassia Patin 
materials_required: thermal cycler [OBI:0400116], gel electrophoresis system [OBI:0001121]|
skills_required: sterile technique, pipetting skills, standard molecular technique
time_required: 180
personnel_required: 1
language: English 
issued: 2025-08-02
audience: scientists
publisher: California Cooperative Oceanic Fisheries Investigations
hasVersion:
license:
maturity level: mature
env_broad_scale: marine biome [ENVO:00000447]
env_local_scale: marine photic zone [ENVO:00000209], marine pelagic zone [ENVO_00000208], marine aphotic zone [ENVO_00000210]
env_medium: sea water [ENVO:00002149]

# FAIRe terms
pcr_0_1: 1
amplificationReactionVolume: 20
assay_name: MURI_mifish
assay_validation: not provided
targetTaxonomicAssay: mitochondrial control region d-loop metabarcode sequencing
TaxonomicScope: cetaceans
target_gene: mitochondrial control region
target_subfragment: d-loop
ampliconSize: 240-275
pcr_primer_forward: TCACCCAAAGCTGRARTTCTA
pcr_primer_reverse: GCGGGTTGCTGGTTTCACG
pcr_primer_name_forward: Dlp1.5-H
pcr_primer_name_reverse: Oordlp4
pcr_primer_reference_forward: https://doi.org/10.1046/j.1365-294x.1998.00380.x
pcr_primer_reference_reverse: https://doi.org/10.3389/fmars.2018.00133
pcr_primer_vol_forward: 1.0
pcr_primer_vol_reverse: 1.0
pcr_primer_conc_forward: 10
pcr_primer_conc_reverse: 10
probeReporter: not applicable
probeQuencher: not applicable
probe_seq: not applicable
probe_ref: not applicable
probe_conc: not applicable
commercial_mm: 2X Phusion Master Mix
custom_mm: PCR reactions were run in 20 uL reaction volumes, with 2.0 uL of DNA, 10 uL of 2X Phusion Master Mix, 5 uL of water, and 1.0 uL of each primer (10 uM).
pcr_dna_vol: 2.0
pcr_rep: 1.0
pcr_cond: initial denaturation:98_0.5; denaturation:98_0.1667;annealing:60_0.5;elongation:72_0.75;final elongation:72_10;35
annealingTemp: 60
pcr_cycles: 45
---

# CalCOFI MMARINeDNA D-loop PCR Protocol 
## PROTOCOL INFORMATION

### Minimum Information about an Omics Protocol (MIOP)

- MIOP terms are listed in the YAML frontmatter of this page.
- See <https://github.com/BeBOP-OBON/miop/blob/main/model/schema/terms.yaml> for list and definitions.

### Making eDNA FAIR (FAIRe)

- FAIRe terms are listed in the YAML frontmatter of this page.
- See <https://fair-edna.github.io/download.html> for the FAIRe checklist and more information.
- See <https://fair-edna.github.io/guidelines.html#missing-values> for guidelines on missing values that can be used for missing FAIRe or MIOP terms.

 
### Authors

| PREPARED BY  | AFFILIATION | ORCID  | DATE |
| ------------- | ------------- | ------------- | ------------- |
|  Nastassia Patin  | California Cooperative Oceanic Fisheries Investigations  | <https://orcid.org/0000-0001-8522-7682> | 2025-08-02 |

## RELATED PROTOCOLS

| PROTOCOL NAME | LINK  | VERSION | RELEASE DATE | RELATIONSHIP |
| ------------- | ------------- | ------------- | ------------- | ------------- |
| Qubit dsDNA HS Assay| [Qubit dsDNA HS Assay] (https://tools.thermofisher.com/content/sfs/manuals/Qubit_dsDNA_HS_Assay_UG.pdf)| B.0 | 2015-03-05 | Protocol for using the Qubit to quantify DNA|
# BACKGROUND

This protocol describes steps for performing PCR for the d-loop region of the mitochondrial control region  using eDNA extracted from sea water. It was developed by the Marine Mammal Remote detection via
INnovative environmental DNA project team at the University of Washington and NOAA NWFSC.

## Summary

The purpose of this protocol is to conduct PCR targeting cetaceans in marine eDNA samples.


## Method description and rationale

This protocol is used for PCR amplifying the mitochondrial control region d-loop marker gene region of environmental DNA. It is highly reproducible and can easily be adapted for any number of samples (i.e. a full 96-well plate or a few samples). Nextera XT adapters are already present on the primers described in the following protocol.


## Spatial coverage and environment(s) of relevance

This protocol can be used to amplify the d-loop marker gene region of any eDNA sample.

## Personnel Required

One person with molecular laboratory and biology experience.

## Safety

There are no hazardous chemicals or materials involved in this protocol. Standard lab safety techniques should still be used such as wearing PPE to avoid skin or eye contact.

## Training requirements

Basic molecular biology training is sufficient for this protocol including sterile technique, pipetting small volumes and programming/running thermal cyclers.

## Time needed to execute the procedure

Protocol takes about 4 hours including set-up and thermal cycler run time.

# EQUIPMENT

| DESCRIPTION | PRODUCT NAME AND MODEL | MANUFACTURER | QUANTITY | REMARK |
| ------------- | ------------- | ------------- | ------------- | ------------- |
| **Durable equipment** |
| 100-1000 µl Pipette | Eppendorf Research Plus Adjustable-Volume Pipette | Eppendorf | 1 | Can be substituted with any accurate pipette |
| 10-100 µl Pipette | Eppendorf Research Plus Adjustable-Volume Pipette | Eppendorf | 1 | Can be substituted with any accurate pipette |
| 1-10 µl Pipette | Eppendorf Research Plus Adjustable-Volume Pipette | Eppendorf | 1 | Can be substituted with any accurate pipette |
| Thermal Cycler | Applied Biosystems SimpliAmp | Thermo Fisher Scientific | 1 | Can be substituted for generic |
| Microwave | Generic Microwave | Generic Brand | 1 | 
| Flask | 500 mL Flask | Generic Brand | 1 | Used for mixing agarose gel solution
| 1-L Glass Container | 1 L Glass Container | Generic Brand | 1 | Used for storing 1x TBE buffer
| Gel Tray & Box| Gel Electrophoresis Box and Tray | Generic Brand | 1 | 
| Gel Combs | Gel Electrophoresis Combs | Generic Brand | 2 | Use the correct number of wells for your samples
| **Consumable equipment** |
| Gloves | Nitrile Gloves, Exam Grade, Powder-free | ULINE | 1 box | Can be substituted with generic |
| Kim Wipes | KimWipe Delicate Task Wipers | KimTech | 1 box | Can be substituted with generic |
| 8-Count Strip Tubes and Caps| Microamp 8-Tube Strips| Thermo Fisher Scientific |  | As many as samples |
| 1000 µL Filter Tips | TipOne RPT Filter Tips, 1000 µL | US Scientific | 1 box | Can be substituted with generic |
| 200 µL Filter Tips  | TipOne RPT Filter Tips, 200 µL | US Scientific| 2 boxes | Can be substituted with generic |
| 10 µL Filter Tips | TipOne RPT Filter Tips, 10 µL | US Scientific | 2 boxes | Can be substituted with generic |
| Milli-Q quality water | Milli-Q Type 1 Ultrapure Water Systems| EMD Millipore | 4 µL per sample well |  |
| 2X Phusion Mastermix | Phusion® High-Fidelity PCR Master Mix with HF Buffer, M0531S | New England Biolabs| 10µL per sample well| |
| TBE Buffer (10x)| TBE Buffer 10X Solution, Molecular Biology Grade, UltraPure| Thermo Scientific | 100 µL |  |
|Agarose| Agarose LE, Molecular Biology Grade, UltraPure | Thermo Scientific|4g  | |
| SYBR Safe|  SYBR Safe DNA Gel Stain| Invitrogen|  20µL| Light sensitive - do not expose to light
| Gel stain loading dye | DNA Gel Loading Dye (6x)|Thermo Scientific|480 µl (per plate)
| 100bp DNA Ladder| Generuler 100 bp DNA Ladder | Thermo Scientific| 6 µl per lane on gel | |
| Parafilm| Parafilm M Lab Film| Generic | 1 roll| Can substitute with generic brand |
| **Chemicals** |
| EtOH | Ethanol| Generic Brand | 1 wash bottle | Must be molecular grade ethanol |
| **(Optional) Qubit** |
| Qubit Reagents | Qubit dsDNA Quantification Assay Kit| Invitrogen | 1 kit |  |
| Clear Qubit Assay tubes | 0.5 mL thin-walled, polypropylene tubes| Invitrogen | 98| Must be correct tubes to allow for fluorometer to read concentration |

# STANDARD OPERATING PROCEDURE

### Preparation

1. Dilute primers from 100 µM to 10 µM if not already at 10uM.
2. Set up PCR under hood by wiping all surfaces, pipettes, and racks with bleach and ethanol and UV sterilization for 5-10 mins.

### PCR
1. Create the PCR template-free mix consisting of the Taq, both forward and reverse primers, MilliQ water and rAlbumin. 
2. Add 18 µL to each strip tube well (can use the same tip). 
3. Add 2 µL eDNA sample to each well, switching tips between each sample.

**Primers**: PCR primer sequences

| PCR Primer Name | Direction | Sequence (5’ -> 3’)| Sequence (5’ -> 3’) with Nextera XT Overhang Sequence| 
| ----- | ----- | ----- | -----|
|Dlp1.5-H| forward | TCACCCAAAGCTGRARTTCTA |TCGTCGGCAGCGTCAGATGTGTATAAGAGACAGTCACCCAAAGCTGRARTTCTA |
|Oordlp4 | reverse | CATAGTGGGGTATCTAATCCCAGTTTG| GTCTCGTGGGCTCGGAGATGTGTATAAGAGACAGGCGGGTTGCTGGTTTCACG|

**Reaction Mixture**: PCR reagents, volumes, initial and final concentrations

| reagent | volume | intial concentration| final concentration|
| ----- | ----- | ----- |----- |
| 2X Phusion Master Mix | 10µL | 2 |1 |
| 10 µM Forward Primer | 1µL | 10µM |.5µM |
| 10 µM Reverse Primer | 1µL | 10µM |.5µM |
| Nuclease-Free Water| 5µL |  | |
| rAlbumin| 1µL | 10µg/µL |.5µg/µL |
| Template DNA| 2µL (1-10µL recommended)|  | |

**PCR Cycling Program**: 

| PCR step | Temperature | Duration | Repetition |
| ----- | ----- | ----- | ----- |
| Initial Denaturation | 98ºC | 30 s | 1x|
| Denaturation | 98ºC | 10s | 45x |
| Annealing | 60ºC | 30s | 45x |
| Extension | 72ºC | 45s | 45x |
| Final Extension | 72ºC | 10min | 1x |
| Hold | 4ºC | Infinity | |



### Quality control, PCR clean-up

2% Agarose Gel Following PCR amplification

1. Make stock solution of TBE buffer (1x) in a 1-L glass container by adding 100 ml of stock TBE buffer (10x) to 900 ml DI water.
2. Depending on size of gel tray, mix a proportion of 100 ml of TBE buffer (1x) to 2 g of agarose in a flask. Use scale to weigh agarose.
3. Microwave mixture for 1 minute, followed by 15-30 second intervals. Watch carefully after 1 minute - mixture can bubble out of flask! The agarose should be fully dissolved so that the solution is mostly clear. 
4. Wear a protective glove when handling flask as the mixture will be hot. Allow for gel mixture to cool in flask for 5-10 min. 
5. While cooling, set up gel tray in gel box. Make sure the tray is oriented properly and sealed tight for gel pouring. Add two gel combs for 20 wells each lane - total of 40 wells (or however many is needed for number of samples).
6. Pour the gel mixture slowly into the tray and remove any bubbles using a pipette tip.
7. Allow gel to set for 30-45 min.
8. Cut large strips of parafilm or use 8-strip tubes and label each sample as a position on the parafilm/tubes.
9. Combine 10 µL PCR product with 2µL loading dye and DNA stain such as SYBR to visualize the product on an agarose gel. Pipette to mix 2-3 times.
10. Once the gel is set, load it with the samples (12 µL total). Also add 1µL of ladder into its own well combined with 1uL loading dye and 4µL MilliQ water.
13. Fill the gel box with enough TBE buffer (1x) to fully submerge the gel beneath ~1cm of buffer.
14. Run gel at ~100 V for 40-50 min then visualize on gel reader machine.

(Optional)
To quantify the DNA in the samples post-PCR, the Qubit can be utilized to determine the DNA concentrations. Refer to the Manufacturer protocol for High Senstivity: [Qubit Protocol](https://tools.thermofisher.com/content/sfs/manuals/Qubit_dsDNA_HS_Assay_UG.pdf)

## Quality control

To confirm there is no contamination during the PCR process, at least one negative control is to be included. Similarly, in order to confirm that the PCR is accurately amplifying DNA, a positive control is to be included. This may be a species that is not likely to be present within the samples. Take care not to cross-contaminate samples with controls and with other samples by switching tips, pipetting slowly and completely, and gently opening and closing tubes.

## Basic troubleshooting guide

If contamination bands are present on the gel, ensure the lab bench is sterilized and re-run the PCR with new aliquots of reagents and MilliQ water.

## ACRONYMS AND ABBREVIATIONS

| ACRONYM / ABBREVIATION | DEFINITION |
| ------------- | ------------- |
| PCR | Polymerase Chain Reaction |
| eDNA | Environmental DNA |
| EtOH | Ethanol |
| PPE | Personal Protective Equipment |

## REFERENCES

[Qubit Protocol](https://tools.thermofisher.com/content/sfs/manuals/Qubit_dsDNA_HS_Assay_UG.pdf)


## APPENDIX A: DATASHEETS

Not applicable.
