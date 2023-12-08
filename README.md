# SAR SHIP Datasets

## AIR-SAR-SHIP-DATASET
High-resolution SAR ship objection detection dataset-1.0 (AIR-SARShip-1.0) releases 31 images for its original edition. The resolution of images includes 1m and 3m, imaging mode covers both spotlight and strip, and polarization is single polarization. The scene type includes ports, islands and reefs, and seas of different grades. The target contains nearly one thousand ships with more than ten categories such as transport vessels, oil tankers and fishing boats.



In dataset, each image size is about 3000×3000 pixels, with Tiff format, single channel, 16-bit image depth. The corresponding annotation file provides the detail information, including the length and width dimensions, the category and the position of the targets.

Paper: https://radars.ac.cn/en/article/doi/10.12000/JR19097
       https://www.mdpi.com/2072-4292/13/24/5104

Dataset: https://drive.google.com/file/d/1Vf-jFGCP7o6B5vmR2fkoU270nADYlOHZ/view?usp=sharing

## Official-SSDD-Open
SAR Ship Detection Dataset (SSDD) is the first open dataset that is widely used to research state-ofthe-art technology of ship detection from Synthetic Aperture Radar (SAR) imagery based on deep learning
(DL). SSDD’s official release version has three types: (1) a bounding box SSDD (BBox-SSDD), (2) a rotatable
bounding box SSDD (RBox-SSDD), and (3) a polygon segmentation SSDD (PSeg-SSDD). One of the reason
to use this dataset was that it was following strict standards like the training-test division determination,
the inshore-offshore protocol, the ship-size reasonable definition, the determination of the densely
distributed small ship samples, and the determination of the densely parallel berthing at ports ship
samples.

The rotated annotations of the Official – SSDD dataset are in the PASCAL VOC format. The attributes that are available are (cx, cy, w, h, 𝜃, x1, y1, x2, y2, x3, y3, x4, y4) where 𝜃 ∈ [0°,90°].
The angle labels that are provided are the continuous float-type rather than the discrete int-type, which
will lead to better direction estimation accuracy

The dataset consists of 1160 SAR images with dimensions of 500×350 pixels. It includes 2358 ship
instances. The spatial resolutions of SAR images are from 1 to 15 meters per pixel. These 1160 images
were obtained from RadarSat-2, TerraSAR-X and Sentinel-1 satellites. The above 1160 images are in .jpeg
format with 24-bit color depth. Dataset images have mixed HH, HV, VV, and VH polarizations.

Paper: https://www.mdpi.com/2072-4292/13/18/3690

Dataset: https://drive.google.com/file/d/1Oe99oueVRvFpZsUBRKsA5GgNrnRGxzKk/view?usp=sharing
