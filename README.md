# BSP_2023
Data is organized as follows:
```bash
.
├── analysis
│   ├── dogmaseq-dig
│   │   ├── ATA-737K-arc-v1_rc.txt
│   │   ├── ATA-737K-arc-v1.txt
│   │   ├── atac
│   │   │   └── cellatlas_info.json
│   │   ├── atac_subsam
│   │   │   └── cellatlas_info.json
│   │   ├── protein
│   │   │   └── cellatlas_info.json
│   │   ├── protein_feature_barcodes.txt
│   │   ├── rna
│   │   │   └── cellatlas_info.json
│   │   ├── RNA-737K-arc-v1.txt
│   │   ├── rna_subsam
│   │   │   └── cellatlas_info.json
│   │   ├── spec_joint_subsam.yaml
│   │   ├── spec_joint.yaml
│   │   ├── tag
│   │   │   └── cellatlas_info.json
│   │   └── tag_0419_feature_barcodes.txt
│   └── notebooks
│       ├── make_data.ipynb
│       └── subsam.ipynb
└── LICENSE
```

The _cellatlas_ command used to process the specific dataset is found in the _cellatlas_info.json_. The two notebooks load data processed with _cellatlas_ to perform analysis.
