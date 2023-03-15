# 记录炼丹时踩的坑

## Models9

### [StyleGAN](https://github.com/pphui8/StyleGAN.pytorch)
#### trained datasets
1. CelebA - 2days  

2. Anime_face(failed) - 5h  



### [StyleGAN2](https://github.com/pphui8/stylegan2-pytorch)
#### trained datasets
1. Anime_face  
1.1 prepare data using ```./prepare_data.py```  
1.2 prepare dataset: ```python prepare_data.py --out ./pdata/ --size 128,256 dataset```  
1.3 execute: ```python train.py ./pdata/```  
1.4 file structure requirement of dataset:
```
root
|- class1
|   |- img1
|   ....
|- class2
|   |- img1
...
```  


## Datasets

### [CelebA](http://mmlab.ie.cuhk.edu.hk/projects/CelebA.html)
> 256 x 256

### [Anime_face](https://paperswithcode.com/dataset/anime-face-dataset-by-character-name)
> img with classes  
> 96 x 96 (remember to resize it)