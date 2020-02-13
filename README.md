# Mi-Seq analysis workflow using BRB-Seq tools
The script contains the workflow to analyse the results barcoded samples of Mi-Seq.

*Lidia Lipinska, Postdoc at the University of Warsaw*

## Main two appraches:
   A. Alignment of fastq file containing all samples with different barcodes (here 12 barcodes), and usage of BRB-Seq CreateDGEMatrix to demultiplex the samples according barcodes and analyse them in the one step -- to obtain data frames with reads per genes and umis per genes.
   

   B. Demultiplexing the samples according the barcodes at first, alignment of separated samples, and analysis them.
   
   
The analysis is based on reaserch article: Alpern, D., Gardeux, V., Russeil, J. et al. BRB-seq: ultra-affordable high-throughput transcriptomics enabled by bulk RNA barcoding and sequencin. Genome Biol 20, 71 (2019)

Github repository: https://github.com/DeplanckeLab/BRB-seqTools
