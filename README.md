## igemmunich2018
# sequ-into - A straightforward desktop app for third generation sequencing read analysis



#### Description
Third generation sequencing techniques rapidly evolved as a common practice in molecular biology. Great advances have been made in terms of feasibility, cost, throughput, and read-length. However, sample contamination still poses a big issue: it complicates correct, high-quality downstream analysis of sequencing data and usage in medical applications. Furthermore, it might be unclear weather the sequenced reads represent the intended target. To address these issues we developed a cross-platform desktop application: Sequ-Into. Reads originating from unwanted sources are detected and summarized by a comprehensive statistical overview, but can also be filtered and exported in standardized FASTQ-format to facilitate custom evaluation of experimental findings. This holds also true for an evaluation weather the reads consist of the intended source, and allows for a positive selection of those reads who do. Sequ-Into creates a straightforward user experience by fusing an intuitive graphical-user-interface with state-of-the-art long-read alignment software.

The app was implemented in the context of our iGEM project, where several DNA purification protocols were evaluated with Sequ-Into and thus allowed iterative engineering cycles leading to a so far unreached purification of up to 96% (bases sequenced) in our probes. To read more about Phactory, please follow this link: http://2018.igem.org/Team:Munich



#### Features
- investigate FASTQ or FAST5 format files
- start calculations for several experiments in parallel
- examine single files or many files at once
- map your read files to default E.Coli K12 genome
- map your read files to your own references and save them in the app for future use
- map your read files against DNA as well as against RNA references
- get an statistical overview on the results that is also visualized
- save only those extracted reads you need for your further analysis (reads that either aligned, or didn't align to the chosen reference)   



#### Employed Software and Modules
- Graphmap
- HTSeq
- Electron
- Material-UI

#### Acknowledgement
Electron React Biolerplaite
