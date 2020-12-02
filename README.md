# fishguts

## Guide to Files

### FishGutsCode.Rmd
This is the R markdown file that contains all the code to create figures and go from fastq files to phyloseq object

### TrimScript.Rmd
This file contains the code to use cutadapt for removal of primer phasing. Use the FbarcodeTrims.fasta for the mapping file for the forward reads and the RbarcodeTrims.fasta for the reverse read

### Phyloseq objects and other misc. files
The phyloseq object used for the analysis is saved as ps.RDS and contains the tree information that is within the seqtree.RDS and Fish_placement.tog.relabelled.tre.gz files. the fish-tank_data.csv files can be used to calculate bray-curtis distance. 
