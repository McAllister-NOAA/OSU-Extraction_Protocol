---
# MIOP terms
methodology_category: sample extraction and purification
project: NOAA Pacific Marine Environmental Laboratory Ocean Molecular Ecology Group protocols
purpose: biodiversity assessment objective [OBI:0001969]
analyses: DNA extraction [OBI:0000257]
geographic_location: North East Pacific Ocean [GAZ:00013765], Bering Sea [GAZ:00008990], Arctic Ocean [GAZ:00000323]
broad_scale_environmental_context: marine biome [ENVO:00000447], marine photic zone [ENVO:00000209]
local_environmental_context: oceanic epipelagic zone biome [ENVO:01000035], marine benthic biome [ENVO:01000024]
environmental_medium: sea water [ENVO:00002149]
target: deoxyribonucleic acid (DNA) [NCIT:C449]
creator: Sean McAllister
materials_required: TBD, vortexer [OBI:0400118], centrifuge [OBI:0400106], incubator [OBI:0000136]
skills_required: TBD, sterile technique, pipetting skills, standard molecular technique
time_required: 	TBD
personnel_required: 1
language: en
issued:	2025-08-12
audience: scientists
publisher:	NOAA Pacific Marine Environmental Laboratory Ocean Molecular Ecology Group; University of Washington Cooperative Institute for Climate, Ocean, & Ecosystem Studies
hasVersion: 1
license: CC0 1.0 Universal
maturity level: mature

# FAIRe terms
samp_vol_we_dna_ext: 1000
samp_vol_we_dna_ext_unit: mL
nucl_acid_ext_lysis: enzymatic | thermal
nucl_acid_ext_sep: magnetic beads
nucl_acid_ext: https://doi.org/10.5281/zenodo.16850033
nucl_acid_ext_kit: Omega Bio-Tek Mag-Bind Blood & Tissue DNA HDQ 96 Kit
nucl_acid_ext_modify: Lysis steps modified for all filters. Reagent volume altered
dna_cleanup_0_1: 0
dna_cleanup_method: not applicable
concentration: not applicable
concentration_method: not applicable
ratioOfAbsorbance260_280: not applicable
pool_dna_num: not applicable
nucl_acid_ext_method_additional: not applicable
---

# OSU Extraction Protocol

**NOTE: This is NOT THE RECOMMENDED extraction protocol for the OME group. For the standard OME protocol, see [NOAA-PMEL-OME_Extraction_Protocol_Sterivex_Centrifuge.md](https://github.com/marinednadude/NOAA-PMEL-OME_Extraction_Protocol_Sterivex_Centrifuge/blob/main/NOAA-PMEL-OME_Extraction_Protocol_Sterivex_Centrifuge.md)**

## PROTOCOL INFORMATION

### Minimum Information about an Omics Protocol (MIOP)

- MIOP terms are listed in the YAML frontmatter of this page.
- See <https://github.com/BeBOP-OBON/miop/blob/main/model/schema/terms.yaml> for list and definitions.

### Making eDNA FAIR (FAIRe)

- FAIRe terms are listed in the YAML frontmatter of this page.
- See <https://fair-edna.github.io/download.html> for the FAIRe checklist and more information.
- See <https://fair-edna.github.io/guidelines.html#missing-values> for guidelines on missing values that can be used for missing FAIRe or MIOP terms.

### Authors

- All authors known to have contributed to the preparation of this protocol, including those who filled in the template.
- Visit https://orcid.org/ to register for an ORCID.
- Date is the date the author first worked on the protocol.

| PREPARED BY All authors known to have contributed to the preparation of this protocol, including those who filled in the template.  | AFFILIATION | ORCID (visit https://orcid.org/ to register) | DATE |
| ------------- | ------------- | ------------- | ------------- |
| Sean McAllister	| Ocean Molecular Ecology, NOAA PMEL & UW CICOES	|0000-0001-6654-3495	| 2021, 2025-08-12 |
| Katie Carter | Oregon State University, Center for Genome Research and Biocomputing (currently Center for Quantitative Life Sciences) | N/A | 2021 |
| Shannon Brown | Ocean Molecular Ecology, NOAA PMEL & UW CICOES  | 0000-0001-9808-2638 |2025-08-?|
| Han Weinrich  | Ocean Molecular Ecology, NOAA PMEL & UW CICOES  | 0009-0007-6063-0986 |2025-08-?|

### Related Protocols

- This section contains protocols that should be known to users of this protocol.
- Include the link to each protocol.
- Include the version number and release date (if available).
- Internal/External: "Internal" are derivative or altered protocols, or other protocols in this workflow. "External" are protocols from manufacturers or other groups.

| PROTOCOL NAME | LINK         | VERSION      | RELEASE DATE | INTERNAL/EXTERNAL |
| ------------- | ------------ | ------------ | ------------ | ----------------- |
| NOAA-PMEL-OME_Extraction_Protocol_Sterivex_Centrifuge | https://github.com/marinednadude/NOAA-PMEL-OME_Extraction_Protocol_Sterivex_Centrifuge | 1.1 | 2025-02-20 | Internal |
| NOAA-PMEL-OME_Extraction_Protocol_DiscFilter_Centrifuge_BeBOP | Pending  | 1.0.0  | Internal |
| Mag-Bind Blood & Tissue DNA HDQ 96 Kit| https://omegabiotek.com/product/tissue-and-blood-kit-genomic-dna-isolation-mag-bind-hdq-96 | Unavailable | Unavailable | External |
| Quant-iT 1X dsDNA HS Assay Kit | https://assets.thermofisher.com/TFS-Assets/BID/manuals/MAN0017526_Quant_iT_1X_dsDNA_HS_Assay_Kit_UG.pdf | Unavailable | Unavailable | External |
| Spens et al. 2017 | https://doi.org/10.1111/2041-210X.12683 | 1.0  | 2016-11-15  | External |

### Protocol Revision Record

- Version numbers start at 1.0.0 when the protocol is first completed and will increase when changes that impact the outcome of the procedure are made (patches: 1.0.1; minor changes: 1.1.0; major changes: 2.0.0).
- Release date is the date when a given protocol version was finalised.
- Description of revisions includes a brief description of what was changed relative to the previous version.

| VERSION | RELEASE DATE | DESCRIPTION OF REVISIONS |
| ------------- | ------------- | ------------- |
| 0.1.0 | 2025-08-13 | Initial release |

### Acronyms and Abbreviations

TBD

| ACRONYM / ABBREVIATION | DEFINITION |
| ------------- | ------------- |
|BSC	|Biosafety cabinent |
|CICOES| Cooperative Institute for Climate, Ocean, and Ecosystem Studies|
|DNA	|Deoxyribonucleic acid|
|eDNA	|environmental DNA|
|EtOH| Ethanol|
|NOAA|National Oceanic and Atmospheric Administration|
|OME	|Ocean Molecular Ecology|
|PCR| Polymerase chain reaction |
|PMEL	|Pacific Marine Environmental Laboratory
|PPE | Personal protective equipment |
|UV| Ultraviolet|
|UW| University of Washington

### Glossary

TBD

| SPECIALISED TERM | DEFINITION |
| ------------- | ------------- |
| Extraction blank  | Extraction negative control. Typically nuclease-free water or an empty filter is run through the DNA extraction process to control for contamination in the DNA extraction step.  |
| Field blank  | Sampling negative control. Typically distilled or reverse osmosis water is run through a filter like a seawater eDNA sample to control for contamination in the field sampling step.  |
| No template control | PCR negative control. Typically nuclease-free water is loaded in place of a sample on a PCR to control for contamination in the PCR step. |
| Positive control  | PCR positive control. Typically a synthetic DNA strand, non-indigenous DNA extract, or intentionally designed mock community is loaded in place of a sample on a PCR to control for contamination and index hopping in the PCR step. |


## BACKGROUND

This document describes the 2021 Oregon State University Center for Genome Research and Biocomputing (CGRB; currently Center for Quantitative Life Sciences, CQLS) protocol to extract DNA from sterivex and disc filters on behalf of the PMEL OME group.

### Summary

Nucleic acid extraction from various filter types is described with varying lysis steps/volumes. After lysis, all samples were extracted via the Omega BioTek Blood and Tissue HDQ kit (M6399), run on a KingFisher Flex (ThermoFisher) robot using deep 96-well plates and magnet. All samples were quantified via the Quant-iT dsDNA high sensitivity kit (ThermoFisher). Extraction protocols for sterivex filters were adapted from [Spens et al 2017](https://doi.org/10.1111/2041-210X.12683).

### Method Description and Rationale

The OSU CGRB/CQLS group performed the following extraction methods on PMEL OME sterivex, 45 mm disc filters, and 25 mm disc filters per discussion with McAllister. For the sterivex filters, the [Spens et al 2017](https://doi.org/10.1111/2041-210X.12683) protocol is a widely used, highly reproducible, minimizes contamination, and easily executable DNA extraction protocol from Sterivex filters. Other fitting methods were apopted for the disc filters.


### Spatial Coverage and Environment(s) of Relevance

This protocol has been used to extract DNA from filtered seawater samples from two 2020 cruises in the U.S. Arctic and coast of Alaska.

### Personnel Required

One person with molecular biology experience.

### Safety

TBD

Buffer AW1 from the DNeasy Blood & Tissue Kit contains guanidine hydrochloride and is classified as category 4 for acute toxicity [(Safety Data Sheet)](https://www.qiagen.com/binary/resource/sds/800000000214-en-GB-IE--1/214-BufferAW1-en-GB-IE--1.00000.pdf). Additional care should be taken when working with this buffer. For other reagents, standard precautions, including wearing PPE, should be taken to avoid skin and eye exposure to chemicals.

### Training Requirements

Molecular biology training (including, at a minimum, sterile technique, pipetting small volumes, and previous DNA/RNA extraction experience) is required to conduct this protocol.

### Time Required to Execute the Procedure

TBD 

## EQUIPMENT

- Description: E.g., "filter".
- Product Name and Model: Provide the official name of the product.
- Manufacturer: Provide the name of the manufacturer of the product.
- Quantity: Provide quantities necessary for one application of the standard operating procedure (e.g., number of filters).
- Remark: For example, some of the consumables may need to be sterilized, some commercial solutions may need to be diluted or shielded from light during the operating procedure.

Minimal equipment list for described protocol:

| DESCRIPTION | PRODUCT NAME AND MODEL | MANUFACTURER | QUANTITY | REMARK |
| ------------- | ------------- | ------------- | ------------- | ------------- |
| **Durable equipment** |||||||
| KingFisher Flex | KingFisher Flex Purification System with 96 Deep-well Head 5400630 | ThermoFisher | 1 | Robot for automation. Need accessories for 96-well magnet purification. |
| Microplate reader | | | 1 | Can substitute Qubit fluorometer | 
| Centrifuge | Eppendorf 5425/5430 R  | Fisher Scientific | 1 | Can be substituted with generic - needs to fit 5 mL tubes and 96-well plates. |
| BioSafety II cabinet|Biological safety cabinet (INT-1100A2)|Kewaunee|1|Can be substituted with generic; internal UV light required.|
| Heatshaker | Fisherbrand incubating mini-shaker | Fisher Scientific | 1 | Can be substituted with generic; hot bath not recommend for sterility reasons. |
| Vortex | Analog vortex mixer | Fisher Scientific | 1 | Can be substituted with generic. |
|-20°C freezer|TSX high-performance -20°C manual defrost freezer |Fisher Scientific|1|Can be substituted with generic but recommend temperature display.|
| Pipettor: 1 - 10 µL | Pipetman P10 | Gilson | 1 | Can be substituted with any accurate pipettor.|
| Pipettor: 20 - 200 μL	|Pipetman P200L | Gilson |	1 | Can be substituted with any accurate pipettor.|
| Pipettor: 100-1000 μL	|Pipetman P1000	|Gilson	| 1 |Can be substituted with any accurate pipettor.|
| Microtube racks | 96-Well flipper microtube racks | Fisher Scientific | 2 | Can be substituted with generic but must fit 1.5-2.0 mL tubes. |
| 50 mL tube racks | SPL snap 50 mL tube rack (25 place) | SPL Life Sciences | 2 | Can be substituted but must fit sterivex. |
| 4-way tube racks | 4 way interlocking tube rack| Cole-Parmer | 4 | Can be substituted with generic, must fit 12 x 5 mL tubes and 50 mL tubes. |
|Trash bag holder|Bel-Art scienceware bench-top biohazard holders|Fisher Scientific|1|Can be substituted with generic.|
|Cryoboxes|TruCool hinged lid cryoboxes|VWR|4|Can be substituted with generic, but recommend set color for eDNA. Must be sterilized before use. |
| Sterile scalpal or scissors | Generic | Generic | 1 | To be used for cutting filters. Sterilize with bleach or flame or purchase pre-sterilized (gamma). |
| **Consumable equipment** |
| Quant-iT dsDNA high sensitivity kit | Invitrogen Q33232 | ThermoFisher | 1 per 1000 samples | Can substitute with Qubit quantification. |
| 5 mL luer lock syringes | BD luer lock disposable syringe| BD | 2 per sterivex | Can be subsituted with generic. Must be sterile and luer lock. |
| Sterivex/syringe caps | Male/female sterile luer caps | McKesson | 2 per sterivex | Can be substituted with generic, must be sterile and individually packaged. |
| 5 mL tubes | DNA LoBind 5 mL PCR clean centrifuge tube | Eppendorf | 1 per sterivex/25mm/45mm filter | Can be substituted with generic, must be sterile/PCR clean |
| Parafilm | Parafilm M - 5259-04LC PM996 All Purpose Laboratory Film | Parafilm | 1 | Can be substituted with generic. |
| RNase A | RNase A for Genomic DNA Systems PD090 | Omega BioTek | 10 µL per sterivex/45mm, 5 µL per 25mm filter |  |
| 96-well deep-well plates | Nunc 96-Well Polypropylene DeepWell Sample Processing & Storage Plates with Shared-Wall Technology 278752 | Thermo Scientific | 4 per filter | Can substitute. |
| 10 μL pipette tips  | TipOne RPT filter tips 10 μL graduated| USA Scientific | 96 | Can be subsituted with generic. Must be sterile and filtered. |
| 200 μL pipette tips  | TipOne RPT filter tips 200 μL graduated| USA Scientific |96 | Can be subsituted with generic. Must be sterile and filtered. |
| 1000 μL pipette tips  | TipOne RPT filter tips 1000 μL | USA Scientific |220 | Can be subsituted with generic. Must be sterile and filtered. |
| Kimwipes | Delicate task wipes | Kimtech | 5 | Can be substituted with generic. Must be lint-free.|
| Nitrile gloves | Powder free nitrile gloves | Fisher Scientific | 8 | Can be subsituted with generic nitrile gloves. Does not come sterile; must be sterilized before use.|
| Lab notebook | Durable, hardcover lab notebook | Generic | 1 | Dedicated to the lab space|
| Writing utensils | Sharpies and pens | Generic | 2 | Dedicated to the lab extraction space. Not made of wood - must be able to be wiped down with bleach/EtOH.  |
| Trash bags for BSC|Teivio 1.2 Gallon 360 Counts Strong Trash Bags|Teivio|3|Can be substituted with generic.|
| 70% EtOH | Molecular biology grade ethanol | 20 mL |  |
| 10% bleach | Hypochlorite bleach | Clorox | 10 mL| Remake every ~5 days as bleach decomposes quickly at 10% concentration. The majority is used in bottle/tube sterilization.|
| **Omega BioTek Blood and Tissue HDQ kit** | M6399 | Omega BioTek | 1 per 96 samples | See component needs below. |
| TL buffer | PD061 | Omega BioTek | 900 µL per sterivex/45mm filter, 450 µL per 25mm filter | Omega BioTek Blood and Tissue HDQ kit comes with 30 mL per 96 rxns. |
| Proteinase K  | AC116 | Omega BioTek | 100 µL per sterivex, 80 µL per 45mm, 40 µL per 25 mm filter | Omega BioTek Blood and Tissue HDQ kit comes with 2.2 mL per 96 rxns. Can be substituted with generic. |
| AL buffer | AL-1000 | Omega BioTek | 870 µL per sterivex, 1160 µL per 45mm, 580 µL per 25mm filter | Omega BioTek Blood and Tissue HDQ kit comes with 35 mL per 96 rxns. |
| HDQ Binding Buffer | HDQ-200 | Omega BioTek | 1200 µL per sterivex, 1600 µL per 45mm, 800 µL per 25mm filter | Omega BioTek Blood and Tissue HDQ kit comes with 10 mL per 96 rxns. |
| HDQ Binding beads | Mag-Bind Particles HDQ | Omega BioTek | 20 µL per sterivex/25mm, 40 µL per 45mm filter  | Omega BioTek Blood and Tissue HDQ kit comes with 2.2 mL per 96 rxns. |
| 10 mM Tris HCl pH 8.5 | Elution Buffer EB PDR048 | Omega BioTek | 100 µL per sterivex/25mm, 200 µL per 45mm filter | Omega BioTek Blood and Tissue HDQ kit comes with 60 mL per 96 rxns. |

## STANDARD OPERATING PROCEDURE

### For all filters

* Reagents from Omega BioTek Blood and Tissue HDQ kit (M6399). After lysate was prepared, extractions run on KingFisher Flex (ThermoFisher) robot using deep 96-well plates and magnet.
* Though elutions were done with 100 µL, the practical elution volume is 80 µL since the KingFisher Flex unavoidably removes some of the elution buffer when pulling the beads out. 
* DNA quantified with Quant-iT dsDNA high sensitivity kit (ThermoFisher).
* After extraction, all DNA should be stored at -20˚C for short term storage or -80˚C for long term storage. We suggest separating elution into an archival and working stock.

### For sterivex filters

1. Ethanol fraction lysis
    * Use a 5-10 mL disposable luer lock syringe to transfer the ethanol in the sterivex filters to a 5 mL tube.
    * Spin the 5 mL ethanol tubes for 10 min at 5000 x g. Decant ethanol. Place tube upside down on paper towel to dry. Place open tubes briefly under fume hood if all ethanol does not dry.
    * Add 180 µL TL buffer to pellet from ethanol tubes. Add 20 µL ProtK. Vortex to mix.
    * Place at 56˚C overnight.
2. Filter fraction lysis
    * Put the filter tilted upwards on a rack on lab bench so any remaining ethanol can drip/evaporate out.
    * Add 720 µL TL buffer and 80 µL ProtK in the open end of the sterivex filters. Cap both ends. Parafilm both ends.
    * Place on rotating unit at 56˚C overnight.
3. NEXT DAY. Use 5-10 mL disposable luer lock syringe to transfer the lysis buffer from the sterivex filter (filter fraction lysis) to the matching 5 mL tube for the same sample (ethanol fraction lysis).
4. Transfer samples to deep well plate.
5. Add 10 µL PD090 RNase A to each sample.
6. Spin plate down for 10 min at 4000 x g.
7. Continue with standard Omega kit Tissue protocol adjusted to use 3x normal lysate: Transfer 250 µL of lysate to each of three plates. Add 290 µL AL buffer to each plate. Add 400 µL HDQ buffer to each plate. Add 20 µL of HDQ binding beads to one of the plates. Load KingFisher with lysate plates and wash buffers. Run standard KingFisher protocol for kit M6399 edited to include mag-bead binding step 3 times for the 3 lysate plates. Elution in 100 µL 10 mM Tris HCl pH 8.5 (Omega EB).

### For 45 mm filters

1. Ethanol fraction
    * Decant ethanol from sample into 5 mL tube.
    * Spin the ethanol tubes for 10 min at 5000 x g. Decant ethanol. Place tube upside down on paper towel to dry. Place open tubes briefly under fume hood if all ethanol does not dry.
    * Add 200 µL TL buffer to 5 mL tube. Vortex.
3. Filter fraction
    * Pre-fill wells of a deep well collection plate with 350 µL TL buffer.
    * Cut filter in half. Add each half to separate wells of the deep well plate with TL buffer.
5.	 Add half volume of ethanol fraction buffer to one well with corresponding filter and other half of the ethanol fraction buffer to the other well for the same filter.
6.	 Add 40 µL ProtK to deep well collection plate.
7.	 Incubate at 56˚C overnight.
8.	 NEXT DAY. Proceed with standard M6399 protocol.
9.	 Spin plate down for 10 min at 4000 x g. Transfer lysate to new deep well plate with 5 µL RNase A.
10.	 Transfer 250 µL lysate to new deep well plate for two lysate plates total.
11.	 Add AL buffer/HDQ buffer to both plates. Add 20 µL HDQ binding beads to one lysate plate.
12.	 Run standard KingFisher protocol for kit M6399 edited to include mag-bead binding step 2 times for the 2 lysate plates. Elution in 100 µL 10 mM Tris HCl pH 8.5 (Omega EB).

### For 25 mm filters

1. Ethanol fraction
    * Decant ethanol from sample into 5 mL tube.
    * Spin the ethanol tubes for 10 min at 5000 x g. Decant ethanol. Place tube upside down on paper towel to dry. Place open tubes briefly under fume hood if all ethanol does not dry.
    * Add 100 µL TL buffer to 5 mL tube. Vortex.
2. Filter fraction
    * Add filter to deep well collection plate.
    * Add 350 µL TL buffer to filter wells.
3.	 Add ethanol fraction to well with corresponding filter. 
4.	 Add 40 µL ProtK to deep well plate.
5.	 Incubate at 56˚C overnight.
6.	 NEXT DAY. Proceed with standard M6399 protocol.
7.	 Spin plate down for 10 min at 4000 x g, transfer lysate to new deep well plate with 5 µL RNase A.
8.	 Transfer 250 µL lysate to new deep well plate for two lysate plates total.
9.	 Add AL buffer/HDQ buffer to both plates. Add 20 µL HDQ binding beads to one lysate plate.
10.	 Run standard KingFisher protocol for kit M6399 edited to include mag-bead binding step 2 times for the 2 lysate plates. Elution in 100 µL 10 mM Tris HCl pH 8.5 (Omega EB).

**Note:** Some 25 mm filters were stored in 2x whirlpak bags, where the ethanol ended up leaking from the internal bag for all samples and could not be used. This was noted for these samples. Only the filter was used for extraction from these samples. In this case, the filter was removed from the bag, added to a deep well collection plate with 450 µL TL buffer, 40 µL ProtK was added, and then incubated at 56˚C overnight. Continued with the rest of the 25 mm filter protocol as described. 

### Data management

* Sample naming from OME (E#) system was kept. If there were two filters, or two independent half extractions from one filter, associated with one E# sample, then they've were called replicate A and replicate B in the quantification results. If there was only one extraction, then that data is listed under replicate A.

### Quality Control

Negative controls (field blanks) were included in both cruises at the start, middle, and end of collection, and were included in the extraction plates. Samples and controls are quantified to verify DNA concentration (see Quant-iT dsDNA high sensitivity kit, linked above). Lastly, samples are PCR amplified alongside no template and positive controls.

## REFERENCES

Spens, J., Evans, A. R., Halfmaerten, D., Knudsen, S. W., Sengupta, M. E., Mak, S. S. T., Sigsgaard, E. E., & Hellström, M. (2017). Comparison of capture and storage methods for aqueous macrobial eDNA using an optimized extraction protocol: the advantage of an enclosed filter. Methods in Ecology and Evolution, 8 (5), 635-645. https://doi.org/10.1111/2041-210X.12683
