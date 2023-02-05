# Proteomics for Bioinformatics: Mass Spectrometry

## Knowledge Covered in this directory:

  * Overview mass spectrometry 
  * Evaluation + Interpretation of Spectra through **Protein Prospector**, **Mascot**, **Prowl**
  * Overview of instrumentation: MALDI, Ionspray
  * Choosing Resolution for Analysis
  * Mass Spectrometry Applications, Limitations & Troubleshooting

### Overview mass spectrometry 
1. Mass spect has high sensitivity requiring small volumes
2. Many molecules can be measured at once, fractionation ay help analysis (via chromatography)
3. Direct Link between readout (mass) and genome. Since 20 amino acids are known, we can translate the DNA sequences into protein sequences. 

**Basic Principle**
 * Mass Spec. Relies on mass:charge (m/z) ratio (sometimes abbreviated as TH, for Thomson)
 * Note: Avg mass of amino acid is 100Da. 
 * We may see different peaks around a main peak due to isotopes-usually due to H,C, or N isotopes. The natural abundance of isotopes influences the ratio of peaks we expect to see. 
 * When looking at multiple peaks from the same species the *mono isotopic mass* or *average mass* is reported
  * *Mono isotopic mass* refers to mass of isotopic peak whose elemental composition is based on the most abundant isotopes of those elements. Mono isotopic peak is not always the most intense peak. Each peak is shifted by the difference in C12 and C13 isotopes. Usually mono isotopic mass is used to report information on peptides. 

### Evaluation + Interpretation of Spectra through **Protein Prospector**, **Mascot**, **Prowl**
**How to evaluate data**
 * Sensitivity: Minimum amount of analyte detected at a specific confidence interval
 * Resolution: Differences in chemical composition lead to different distribution of isotopic peaks. Different molecules could have the same apparent mass and give rise to the same peak. Resolution is the half width at half height (informs on peak symmetry)
 * Accuracy: Expressed in ppm. The limit of accuracy is determined by the resolution of the measurement, the calibration of the instrument and the amount of sample
**Applications of Mass Spec**
1.Top down: use full proteins. We analyze intect proteins when we know sequence but want to analyze post-translational modifications
2.Bottom up: Use peptide fragments of proteins. Most instruments work better on smaller ranges. This method relies on specific enzyme cut sites to narrow down the possible peptides that are seen. **PMF** is the peptide mass fingerprint which is the ist off masses of peptides taht are seen for a signle protein. 
3.Middle down: Lose larger peptides (more than 15 aa). 
4.MS-MS: Use larger peptides in MS/MS approaches-usually used for mixtures. Also called Tandem or MS2.
