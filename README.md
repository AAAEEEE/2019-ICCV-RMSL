# Reciprocal Multi-Layer Subspace Learning for Multi-View Clustering
This is the Matlab implementation of [Reciprocal Multi-Layer Subspace Learning for Multi-View Clustering, published in ICCV 2019](http://openaccess.thecvf.com/content_ICCV_2019/papers/Li_Reciprocal_Multi-Layer_Subspace_Learning_for_Multi-View_Clustering_ICCV_2019_paper.pdf). 
Contact: Ruihuang Li (liruihuang@tju.edu.cn)

## Paper
* We propose a method to hierarchically identify the underlying cluster structure of high-dimensional data by constructing reciprocal multi-layer subspace representations.
* Based on reconstruction, we learn the latent representation by enforcing it to be close to different view-specific subspace representations, which implicitly co-regularizes subspace structures of all views to be consistent to each other.
* With the introduction of neural networks, more general relationships among different views will be explored.
<img src='img/overview.jpg' width="800px">

## Example Results
<img src='img/tsne.jpg' width="800px">

## Data
In this example, we load ORL and BBCSport datasets. The former contains 400 face images of 40 distinct subjects, from which 3 types of features are extracted. The latter is a collection of 544 documents associated with 2 views taken from sports articles in 5 topical areas.

## Run
* First of all, run initial.m to generate a group of view-specific subspace representations as the initialization.

* Second, run demo_FMR.m 

## Cite
Please cite following papers if you use this code in your own work:
```
@InProceedings{Li_2019_ICCV,
author = {Li, Ruihuang and Zhang, Changqing and Fu, Huazhu and Peng, Xi and Zhou, Tianyi and Hu, Qinghua},
title = {Reciprocal Multi-Layer Subspace Learning for Multi-View Clustering},
booktitle = {The IEEE International Conference on Computer Vision (ICCV)},
month = {October},
year = {2019}
}
```
