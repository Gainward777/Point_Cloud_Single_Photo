# Point_Cloud_Single_Photo

<a href="https://colab.research.google.com/github/Gainward777/Point_Cloud_Single_Photo/blob/main/PointCloud.ipynb" target="_parent"><img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/></a></br>
A simple implementation of a way to get a field of points from a single photo.

This notebook was used for various tests in the development of a solution for predicting the results of plastic surgery for breast augmentation. Including to determine the main development vector, as well as the possibility of using non-standard or segenerated images for further training of the main model.</br>
To obtain depth from the base image, in this work it was decided to use midas, because in tests it showed the best results for close-up images.</br>
In view of the task, the resulting field of dots was deliberately not returned to normal colors and was not cleared of "noisy" dots, since this was not necessary.</br>
Since there were not very many images to check, this task was solved quite quickly by hand. However, with a large number of images, it is possible to automate the process by marking a small dataset and teaching a simple detector to find deviations in the desired zones in the depths.

P.S. The repository may be updated.
