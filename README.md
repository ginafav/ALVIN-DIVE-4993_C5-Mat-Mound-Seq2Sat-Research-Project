# ALVIN-DIVE-4993_C5-Mat-Mound-Seq2Sat-Research-Project
The goal of this project is to investigate the diversity dynamics of Asgard archaea within the "Japan" Beggiatoa Mat, here the focus is on Asgard archaea variations based on the sequencing coverage. 

# READ PROCESSING
- **FastQC:**
    - Performed a quality control check on sequencing reads
- **Tools & Methods:**
    - FASTQC
- **Output Summary**
    - Samples have adapters attached
    - GC content contains skewed or multiple broad peaks
    - Presence of overrepresented sequences in some samples
    - **FASTP:**
    - This removed poor quality reads and adapter sequences
    - **FASTQC:**
    - This was performed on the FASTP output, to confirm the read quality
