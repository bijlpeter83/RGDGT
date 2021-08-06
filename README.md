# RGDGT
R markdown scripts to calculate ratios and evaluate isoprenoidal and branched Glycerol Dialkyl Glycerol Tetraethers and branched Glycerol Monoalkyl Glycerol Tetraether data for paleotemperature and paleoenvironmental reconstructions.

This folder was published on Github as supporting material in Bijl et al., 2021 CPD. Please cite this paper when the contents of this folder is further used.

You will see next to this readme file 2 folders and 1 extra file.

1. The folder /vignettes contains three R markdown scripts. It depends on your dataset and your aims which of the three scripts you need.

* If you have only integrated the 6 isoprenoidal (GDGT-0, GDGT-1, GDGT-2, GDGT-3, cren and cren’) and 3 branched (Ia, IIa, IIIa) GDGTs, and only want to evaluate isoprenoidal GDGTs for a reliable TEX86-based paleotemperature reconstruction, use “RGDGT_TEXBIT.rmd”.
* If you have integrated the 6 isoprenoidal and 7 branched (Ia, Ib, Ic, IIa, IIb, IIc, IIIa) GDGTs (either with or without 5’ and 6’ methyl branched GDGTs separated) and would like to evaluate both TEX86 and MBT’ for reliable paleothermometry, choose “RGDGT_isobrGDGT.rmd”.
* If you have integrated the 6 isoprenoidal, 7 branched GDGTs (either with or without 5’ and 6’ methyl branched GDGTs separated) and the brGMGTs and would like to evaluate TEX86 and MBT’ for reliable paleothermometry, and see what your H-shaped GMGTs do in your record, choose “RGDGT_isobrGDGT_brGMGT.rmd”.

2. The folder /data contains: (i) the modern soil/peat (“soildata.csv”; Dearing Crampton-Flood et al., 2020) and (ii) the Paleogene brGDGT data (“paleobr.csv", from Hollis et al., 2019 and Sluijs et al., 2020), which are used by the RGDGT scripts to plot your data against. (iii) data files from ODP site 1172 ("1172 OG.csv", "Bayesian1172.csv", "Dino1172_grouped.csv", "Dino1172_raw.csv", "Dinodiversity.csv", "pollenMAT1172.csv", "1172UK.csv"), and for convenience to those not familiar with R markdown (iv) a csv file containing GDGT, GMGT abundances, ratios, outlier criteria and TEX86 and MBT-based temperature reconstructions of ODP Site 1172 ("1172_OG_INDICES_OUTLIERS.csv".

3. License. The R markdown scripts provided here are under CC0 license, the data are under a CC-BY 4.0 license. If you use these datasets, cite the appropriate research articles.

5. file "ODP1172OG_PALY.zip contains GDGT/GMGT and dinocyst data published in Bijl et al., 2021 CPD in review.


These scripts are very much in development still and will be with new data and information coming out. Feel free to respond, suggest, augment, adapt and revise to your needs, but we strongly encourage you to maintain the level of openness and explanatory nature of the original script. And we would like you to cite Bijl et al., 2021 CPD or the final paper.
