This repository contains auxiliary gene packages for [SingleM](https://github.com/wwood/singlem), that are not included in the main distribution for various reasons.

First download them from this repository and extract those package(s) of interest:
```
git clone https://github.com/wwood/singlem_extra_packages.git
cd singlem_extra_packages/release1
tar xf 4.40.2013_08_greengenes_97_otus.with_euks.spkg.tar.xz
```

These auxiliary packages are used with the `pipe` command's `--singlem_packages` flag e.g.
```
singlem pipe --singlem_packages 4.40.2013_08_greengenes_97_otus.with_euks.spkg --sequences /path/to/sequences.fastq.gz --otu_table output.otu_table.csv
```
