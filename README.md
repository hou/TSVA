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
```

TSVA can do tissue specific annotation for 30 different tissues and even more sub-tissues!
Please see the following list for all supported tissues so far:

    Adipose Tissue
        Adipose - Subcutaneous
        Adipose - Visceral
    Adrenal Gland
        Adrenal Gland
    Bladder
        Bladder
    Blood
        Whole Blood
        Cells - EBV-transformed lymphocytes
    Blood Vessel
        Artery - Tibial
        Artery - Aorta
        Artery - Coronary
    Brain
        Brain - Hippocampus
        Brain - Hypothalamus
        Brain - Cerebellar Hemisphere
        Brain - Nucleus accumbens
        Brain - Amygdala
        Brain - Frontal Cortex
        Brain - Substantia nigra
        Brain - Anterior cingulate cortex
        Brain - Cerebellum
        Brain - Caudate
        Brain - Spinal cord
        Brain - Putamen
        Brain - Cortex
    Breast
        Breast - Mammary Tissue
    Cervix Uteri
        Cervix - Ectocervix
        Cervix - Endocervix
    Colon
        Colon - Transverse
        Colon - Sigmoid
    Esophagus
        Esophagus - Muscularis
        Esophagus - Mucosa
        Esophagus - Gastroesophageal Junction
    Fallopian Tube
        Fallopian Tube
    Heart
        Heart - Left Ventricle
        Heart - Atrial Appendage
    Kidney
        Kidney - Cortex
    Liver
        Liver
    Lung
        Lung
    Muscle
        Muscle - Skeletal
    Nerve
        Nerve - Tibial
    Ovary
        Ovary
    Pancreas
        Pancreas
    Pituitary
        Pituitary
    Prostate
        Prostate
    Salivary Gland
        Minor Salivary Gland
    Skin
        Cells - Transformed fibroblasts
        Skin - Not Sun Exposed
        Skin - Sun Exposed
    Small Intestine
        Small Intestine - Terminal Ileum
    Spleen
        Spleen
    Stomach
        Stomach
    Testis
        Testis
    Thyroid
        Thyroid
    Uterus
        Uterus
    Vagina
        Vagina

