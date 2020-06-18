# retina_image_segment

Here CNN based segemntation of Fundus Images is done to get the hard exudates for detection of diabetic retinopathy. The dataset used is IDRiD containing 81 fundus images.

32 x 32 patches were made for for each image and the state of central pixel was assigned as the target output.


8 layer CNN was made to classify central pixel of image patches and the finally the patch classifiers were put together.

![IDRiD_55predicted](https://user-images.githubusercontent.com/32814143/85037023-75f48980-b1a2-11ea-9a7e-fd193a4c7dac.png)


