# scpcaData package

This is an R data package that contains pre-processed single cell data in formats expected by [scpcaTools](https://github.com/AlexsLemonade/scpcaTools/).

Data are processed with [`alevin-fry`](https://github.com/COMBINE-lab/alevin-fry), [`kallisto bustools`](https://www.kallistobus.tools/) and [`cellranger`](https://support.10xgenomics.com/single-cell-gene-expression/software/pipelines/latest/what-is-cell-ranger), using workflows from https://github.com/AlexsLemonade/alsf-scpca/tree/main/workflows

Sample data used is from a small 10X Genomics sample data set for invasive ductal carcinoma, available for download from the 10X website:
https://support.10xgenomics.com/single-cell-gene-expression/datasets/6.0.0/Breast_Cancer_3p_LT

Description from 10X website
> 750 Sorted Cells from Human Invasive Ductal Carcinoma, 3’ LT v3.1 <br>
> Single Cell Gene Expression Dataset by Cell Ranger 6.0.0 <br>
> Invasive Ductal Carcinoma cells from a female donor aged 65 were obtained by 10x Genomics from Discovery Life Sciences.
>
> Libraries were prepared following the Chromium Next GEM Single Cell 3' LT Reagent Kits v3.1 (Dual Index) User Guide (CG000399) and sequenced on Illumina NovaSeq 6000. <br>
> Sequencing Depth: 62,379 mean reads per cell <br>
> Paired-end, dual indexing Read 1: 28 cycles (16 bp barcode, 12 bp UMI) i5 index: 10 cycles (sample index) i7 index: 10 cycles (sample index) Read 2: 90 cycles (transcript)
>
> This dataset is licensed under the [Creative Commons Attribution](https://creativecommons.org/licenses/by/4.0/) license.
