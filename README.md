# Maize Tassels Counting from Unmanned Aerial Vehicle (MTC-UAV)

This repository hosts the MTC-UAV dataset associated with our work:

**TasselNetV3: Explainable Plant Counting With Guided Upsampling and Background Suppression**

[Hao Lu](https://sites.google.com/site/poppinace/)<sup>1</sup>, Liang Liu<sup>1,</sup>, Ya-Nan Li<sup>2</sup>, Xiao-Ming Zhao<sup>3</sup>, Xi-Qing Wang<sup>3</sup>, Zhi-Guo Cao<sup>1</sup>

<sup>1</sup>School of Artificial Intelligence and Automation, Huazhong University of Science and Technology, China

<sup>2</sup>School of Computer Science and Engineering, Wuhan Institute of Technology, China

<sup>3</sup>Crop Functional Genomics and Molecular Breeding, College of Biological Science, China Agricultural University, China

IEEE Transactions on Geoscience and Remote Sensing, 2021

## Highlights
- over 400 maize cultivars
- 70,870 manually annotated instances
- 306 images with 5472x3648 image resolution
- 12.5-meter-height nadir imaging view

## Download
The MTC-UAV dataset can be downloaded from: 

[Google Drive (3.8 GB)](https://drive.google.com/file/d/1sNc8dzrcmC3lGifPtW_mddwcWb3YulnR/view?usp=sharing)

## Path Structure
Suppose that the dataset is placed in the `./data` folder, the path structure should look like:
````
$./data/maize_tassels_counting_uav_dataset
├──── images
│       ├──── DJI_0002.JPG
│       ├──── DJI_0007.JPG
│       ├──── ...
├──── labels
│       ├──── DJI_0002.csv
│       ├──── DJI_0007.csv
│       ├──── ...
├──── train.txt
├──── val.txt
````
- `train.txt` and `val.txt` record the train/val split used in the experiments.

## Citation
If you find this work or code useful for your research, please cite:
```
@article{lu2021tasselnetv3,
  title={TasselNetV3: Explainable Plant Counting With Guided Upsampling and Background Suppression},
  author={Lu, Hao and Liu, Liang and Li, Ya-Nan and Zhao, Xiao-Ming and Wang, Xi-Qing and Cao, Zhiguo},
  journal={IEEE Transactions on Geoscience and Remote Sensing},
  year={2021}
}
```

## Permission
This dataset is only for academic purposes. Contact Hao Lu (hlu@hust.edu.cn) or Zhiguo Cao (zgcao@hust.edu.cn) for the commerial use of the model.
