# L4R_NLB Dataset
Dataset for machine learning for railway, which is based on footage from a Norwegian TV format that documents the train ride between Trondheim and Bodø in four different seasons. For more details please refer REFERENCE TO PAPER.

## Structure of Dataset tree
The dataset is split into four parts according to the season the images were taken. For each part images and annotations are provided in separate directories. The annotations are json files containing the image coordinates of tracks and switches and also a list of tags describing the scene. Addidtionally there is a camera matrix, which is needed to cerrectly create the masks from the json annotations or visualize the annotations with the tool Labels4Rails. Please note that images are not provided on github due its memory limit, but can be downloaded from Zenodo PROVIDE LINK. However, annotations might be more up to date on github.

```bash
Dataset_root
├── L4R_NLB_fall
│   ├── images
│   │   ├── nlb_fall_000000.png
│   │   ├── nlb_fall_.......png
│   │   └── nlb_fall_nnnnnn.png
│   ├── annotations
│   │   ├── nlb_fall_000000.json
│   │   ├── nlb_fall_.......json
│   │   └── nlb_fall_nnnnnn.json
│   └── camera
│       └── camera.yaml
|
├── L4R_NLB_spring
│   ├── images
│   │   ├── nlb_spring_000000.png
│   │   ├── nlb_spring_.......png
│   │   └── nlb_spring_nnnnnn.png
│   ├── annotations
│   |   ├── nlb_spring_000000.json
│   |   ├── nlb_spring_.......json
│   |   └── nlb_spring_nnnnnn.json
│   └── camera
│       └── camera.yaml
|
└── L4R_NLB_summer
│   ├── images
│   │   ├── nlb_summer_000000.png
│   │   ├── nlb_summer_.......png
│   │   └── nlb_summer_nnnnnn.png
│   ├── annotations
│   |   ├── nlb_summer_000000.json
│   |   ├── nlb_summer_.......json
│   |   └── nlb_summer_nnnnnn.json
│   └── camera
│       └── camera.yaml
|
└── L4R_NLB_winter
    ├── images
    │   ├── nlb_winter_000100.png
    │   ├── nlb_winter_.......png
    │   └── nlb_winter_nnnnnn.png
    ├── annotations
    |   ├── nlb_winter_000100.json
    |   ├── nlb_winter_.......json
    |   └── nlb_winter_nnnnnn.json
    └── camera
        └── camera.yaml
```
