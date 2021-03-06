# NoAmpTools v0.15.0
Tools for QC-ing and Plotting outputs from PacBio's NoAmp protocol.  These tools require the following libraries to run successfully:

* matplotlib >= 2.0
* numpy >= 1.11
* pandas >= 0.20
* pbcore >= 1.2
* seaborn >= 0.8

## NoAmpYieldDiagnostic
Using NoAmp sequence data aligned to HG19, summarize and plot the number and fraction of ZMWs on-target
> **USAGE:**  python  NoAmYieldDiagnostic.py OUTPUT_PREFIX ALIGN_BAM_PBI

## NoAmpSequelLoadingDiagnostic
Using NoAmp sequence data aligned to HG19, summarize the location, contents, and ends for possible loading effects.
> **USAGE:**  python  NoAmpSequelLoadingDiagnostic.py OUTPUT_PREFIX HG19_FASTA ALIGN_BAM_PBI SCRAPS_BAM

## RepeatAnalysisPlots
Plot the distributions of evidence, by barcode and by target locus, as generated by Repeat-Analysis on NoAmp sequence data
> **USAGE:**  python  RepeatAnalysisPlots.py REPEAT_ANALYSIS_FASTQ REPEAT_ANALYSIS_ZMWS_CSV [REPEAT_ANALYSIS_ZMWS_CSV ...]
