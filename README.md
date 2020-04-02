# structure_plots
mapped all the data and created a merged Bam file as in
https://github.com/TharinduTS/allofraseri.md/blob/master/README.md
(removed creating VCF part from the last filtering and crating VCF pipeline)

Then copied the merged Bam file to computecanada/graham

If you have multiple Bam files, you can easily create a file with the list of files using
```bash
find $BAMFOLDER |  grep bam$ > all.files
```
