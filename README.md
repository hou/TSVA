# TSVA
A toolkit for tissue specific variant effect prediction
```
usage: tsva.py [-h] --tissue TISSUE [TISSUE ...] [--verbose] [--list] vep gtex output

positional arguments:
  vep                   VEP result file name (generated by the VEP)
  gtex                  Tissue specific RPKM (based on GTEx)
  output                output file name

optional arguments:
  -h, --help            show this help message and exit
  --tissue TISSUE [TISSUE ...]
                        which tissue to use
  --verbose             use this flag to get more details for variants
  --list                use this flag to show the full list of tissues supported so far

