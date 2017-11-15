# All-in-one Mapping Tool

Development of an all-in-one mapping tool for Skeletonema

* (Quality control? May not be possible to automate this step...)

1. Map reads to reference genomes
  * Skeletonema and known associated bacteria
  * Could be tied to an input file listing the species and locations of reference genomes
    * [Name] \t [Location of reference to map to]
  * Should this use techniques from Alvar's script or be made from scratch?
  * **If this is to be a Python script, must determine how to call other programs, e.g. Bowtie2, from within Python**

2. Report mapping statistics
  * % mapping to Skeletonema reference
  * % mapping to each bacterial species
  * % unknown
  * Print to an output file, possibly take name from input file
    * "X% of reads mapped to the [Name] reference"

3. Deal with intermediate files
  * Option whether to retain or delete?
    * Possible flags to selectively retain or delete?
