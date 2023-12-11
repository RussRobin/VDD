# VDD: Varied Drone Dataset
This is the official repo for VDD: Varied Drone Dataset for Semantic Segmentation. Please feel free to contact us: russ000robin@gmail.com.


## Download Links

This Dataset is only for non-commercial use. 

**VDD**: 
- [Google Drive](https://drive.google.com/drive/folders/1rbhGbkDmtVuZAd3dPUi9MnEGxBmI-cHE?usp=sharing)
- [Baidu Cloud](https://pan.baidu.com/s/10zB_PM_8dGIm0HE_6BzNwQ)(PWD:vdd0)

**Our annotation of UDD**
We newly annotated UDD dataset to fit with our dataset, thus it can be trained/tested together with VDD. Source images of UDD are offered in its official website: https://github.com/MarcWong/UDD
- [Google Drive](https://drive.google.com/drive/folders/1Xt7r2p8xmHTlZINU4cBxENuDvTDYJcVr?usp=sharing)
- [Baidu Cloud](https://pan.baidu.com/s/1RdDGOvkPbKKvf0hlhiVcmQ)(PWD:1bv3)
Instructions:
1. UDD provides source images, ground truth (png files with values 0~5) and metadata. Replace their ground truth files with ours.
2. Our annotations are based on UDD-6. There are slight differneces in UDD-5, UDD-6 and M1.

**Our annotation of UAVid**
We also contribute to the annotations of UAVid(https://uavid.nl/). Our annotations can be accesses via:
- [Google Drive](https://drive.google.com/drive/folders/1WVVOjVQaHIMZlhzSdlemTd-S55PWa3Qm?usp=sharing)
- [Baidu Cloud](https://pan.baidu.com/s/1wjWZxx6rXGiOKnk-FqAu_g?pwd=2kve)(PWD:2kve)
Instructions: 
1. Our annotations can be found in ‘VDD_Labels’ folder, and colormaps are in ‘VDD_Colormap’ folder.

**MMSegmentation confifs**
- [Google Drive](https://drive.google.com/drive/folders/1799udtcNwbCHejy42MEx7L_JqRVvB9Hk?usp=share_link)
We provide config files based on MMSegmentation. Please first go to https://github.com/open-mmlab/mmsegmentation and download source codes for MMSegmentation. You may then add our uploaded files to corresponding paths in MMSegmentation.




## Introduction

VDD is a dataset featuring varied scenes, camera angles and weather/light conditions of UAV images. We provide 400 pixel-level annotated images with high resolution. Images are categorized into 7 classes: Wall, Roof, Road, Water, Vehicle, Vegetation and Others.

Open space image shown below briefly demo ‘Varied’: scene details(vary because of change of season), camera angles and light/weather conditions vary. We view this as a special way to do data augmentation. Please refer to our paper for details.

**Scene variance**

Many typical scenes are included in VDD dataset: 
* Municipal residential zones, villas, school and college buildings, and hospitals
* highways and roads, 
* Facilities like gyms cantenn and libraries
* Natural scenes: rivers, lakes and mountains
* Rural areas: villages and farm fields

**Time & Light condition variance**

The example images are taken in spring and summer, where light conditions and vegetation changes. There is also a set of photos of the same object but taken at morning and evening respectively.

**Camera angle variance**

Photos are taken with fixed camera angles: 30, 60 and 90(bird view) degrees.



**Citation**
Available soon.

**Terms of use**

VDD: Varied Drone Dataset is made freely available to academic and non-academic entities for non-commercial purposes such as academic research, teaching, scientific publications, or personal experimentation. Permission is granted to use the data given that you agree:

That the dataset comes “AS IS”, without express or implied warranty. Although every effort has been made to ensure accuracy, the authors (AVAILABLE SOON) do not accept any responsibility for errors or omissions.
That you include a reference to the Semantic Drone Dataset in any work that makes use of the dataset. For research papers or other media, refer to our paper: AVAILABLE SOON

That you do not distribute this dataset or modified versions. It is permissible to distribute derivative works in as far as they are abstract representations of this dataset (such as models trained on it or additional annotations that do not directly include any of our data) and do not allow to recover the dataset or something similar in character.

That you may not use the dataset or any derivative work for commercial purposes as, for example, licensing or selling the data, or using the data with a purpose to procure a commercial gain.

That all rights not expressly granted to you are reserved by the authors (AVAILABLE SOON).
