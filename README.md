# 16S_SangerBlast_HU: Shell script for 16S sanger seq results.
### BLASTs against rhizobia isolated at MPIPZ, rhizobia obtained from public stocks, and AtSphere root isolates.
### MultiFASTA file containing all sequencing results is required
originally by  
Ryohei Thomas Nakano, 04.02.2017  
last modified: 01.12.2023  
nakano@mpipz.mpg.de; rtnakano@sci.hokudai.ac.jp  
usage  
./blast_16S.sh [full path of data directory]  
(Example: ./blast_16S.sh /biodata/dep_psl/grp_psl/ThomasN/seq_results/11106756571-1  
_sequence data should be stored in the ${ID}.fasta file, where ${ID} is the name of your directory (the last part of your full path)_

--

Required:
- NCBI blast https://blast.ncbi.nlm.nih.gov/doc/blast-help/downloadblastdata.html
- mafft https://mafft.cbrc.jp/alignment/software/
- R https://www.r-project.org/
- R package "stringr" https://stringr.tidyverse.org/
