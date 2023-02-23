# RNAseq-Pipeline
RNAseq Data Processing Pipeline


This scipt performs quality control and mapping of sequencing reads. It intakes .gz file and trim 15 bases (based on fastQC) from 5' end and 5 bases from 3' end (read length of 100 bases). In the next step, it runs star mapping to the genome and generate read count files.
