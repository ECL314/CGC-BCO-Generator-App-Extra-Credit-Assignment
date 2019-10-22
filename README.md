# CGC-BCO-Generator-App-Extra-Credit-Assignment

This GitHub repository contains two BCO's that were generated using the new BioCompute Object (BCO) Composer app on the Cancer Genomics Cloud (CGC) powered by Seven Bridges.  

The BCO Composer app, which uses the R Studio portal on the CGC, enables users to create a BCO from one of the many workflows from the CGC Public Apps Gallery or from a run task.  The benefit of using the BCO Composer app is that stored information (e.g. workflow description & execution steps), written in Common Workflow Language (CWL), is automatically extracted and populated in the respective BCO fields. 

In this GitHub repository, the tophat2_2019_10_21_23_59_18.bco.json BCO was created from the CGC public app TopHat2.  (This BCO contains only the information that was automatically extracted and written to the appropriate BCO fields by the BCO Composer app.)  

The rna-seq-alignment-tophat_2019_10_22_05_03_50.bco.json BCO was created from the CGC workflow RNASeq Alignment- TopHat.  (In addition to the information that was automatically extracted and written to the appropriate BCO fields by the BCO Composer app, this BCO also contains information that was manually entered into the BCO fields that could not be filled by the information parsed from CWL.)
