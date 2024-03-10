## Retina Image Segmentation

Here CNN based segemntation of Fundus Images is done to get the hard exudates for detection of diabetic retinopathy. The dataset used is IDRiD containing 81 fundus images.

32 x 32 patches were made for for each image and the state of central pixel was assigned as the target output.


8 layer CNN was made to classify central pixel of image patches and the finally the patch classifiers were put together.

Ground truth :
![IDRiD_55_EX](https://user-images.githubusercontent.com/32814143/85129505-d93cf500-b250-11ea-8773-fe66e55a1428.png)

Predicted with 32x32 patch size :
![IDRiD_55predicted](https://user-images.githubusercontent.com/32814143/85037023-75f48980-b1a2-11ea-9a7e-fd193a4c7dac.png)


