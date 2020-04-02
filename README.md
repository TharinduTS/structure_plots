# guide from - found very useful
http://evomics.org/learning/population-and-speciation-genomics/2018-population-and-speciation-genomics/angsd-activity-admixture-population-structure/

# structure_plots
mapped all the data and created  Bam files as in
https://github.com/TharinduTS/allofraseri.md/blob/master/README.md


Then copied the merged Bam files to computecanada/graham

# If you have multiple Bam files, you can easily create a file with the list of files and their paths using
```bash
find $BAMFOLDER |  grep bam$ > all.files
```
# Loading angsd/0.929

Before loading angsd/0.929 on computecanada, had to load following
```bash
module load nixpkgs/16.09
module load gcc/7.3.0
module load nixpkgs/16.09
module load intel/2018.3
```

Then load ANGSD
```bash
module load angsd/0.929
```

# calculate GLs from all the BAM files using ANGSD by running the following command in the terminal

