# Point_Cloud_Single_Photo
A simple implementation of a way to get a field of points from a single photo.

This notebook was used for various tests in the development of a solution for predicting the results of plastic surgery for breast augmentation. Including to determine the main development vector, as well as the possibility of using non-standard or segenerated images for further training of the main model.
To obtain depth from the base image, in this work it was decided to use midas, because in tests it showed the best results for close-up images.
In view of the task, the resulting field of dots was deliberately not returned to normal colors and was not cleared of "noisy" dots, since this was not necessary.

P.S. The repository may be updated.
