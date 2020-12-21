# Image-Processing-for-Lung-Cancer-Detection

In this project, I tried to implement image processing algorithms for lung cancer detection usig matlab on Computer Tomography(CT) scan images.

The CT scan images that I used is obtained from http://www.via.cornell.edu/lungdb.html. 

Basically there are three steps in image processing that I used as follows:
1. Gabor filter for image enhancement
2. Marker controlled watershed with masking for image segmentation
3. Binarization for image classification

In binarization I have calculated number of black pixels in segemented area which later compared with threshold value. Threshold value is obtained by researchers by calculating average number of black and white pixels in segemented area.
There is no metrics performance due to restriction of image label class.

To run the program, you need matlab and image processing library in your matlab. You can use one sample image that I uploaded. For another image you can download from http://www.via.cornell.edu/lungdb.html. Image processing based detection of lung cancer on CT scan images

References:

[1] Lung Cancer Database, Available at: https://eddie.via.cornell.edu/cgibin/datac/signon.cgi
    (For getting CT scan images)

[2] “Non-Small Cell Lung Cancer”, Available at:   http://www.katemacintyrefoundation.org/pdf/non-small-cell.pdf, Adapted from National Cancer Institute (NCI) and Patients Living with Cancer (PLWC). 
    (For studying about lung cancers)

[3] Gonzalez R C and Woods R E 2008 Digital Image Processing Upper Saddle River (New Jersey: Prentice Hall)

[4] T. F. Chan and L. A. Vese, "Active contours without edges," in IEEE Transactions on Image Processing, vol. 10, no. 2, pp. 266-277, Feb. 2001, doi: 10.1109/83.902291.
    (For image segementation)
[5] Allaoui A E and Nasri M 2012 Medical Image Segmentation by Marker Controlled Watershed and Mathematical Morphology 1LABO MATSI, ESTO, B.P 473, University Mohammed I OUJDA, Maroko

[5] Kajal N et al 2015 Early Detection of Lung Cancer Using Image Processing Technique: Review International Journal of
Advent Research in Computer and Electronics (IJARCE) 2(2), E-ISSN: 2348-5523


Flow chart which are used

1. Basic flow of the project 

![image](https://user-images.githubusercontent.com/68813874/102759102-ae676100-4399-11eb-8aff-03f809cba1c9.png)

2. Detailed flow chart 

![image](https://user-images.githubusercontent.com/68813874/102759183-c9d26c00-4399-11eb-8a85-01e494466249.png)

Input image which is used 

![image](https://user-images.githubusercontent.com/68813874/102759292-ebcbee80-4399-11eb-98cd-db7b75d5bbd2.png)

Image after image enhancement using Gabor filter

![image](https://user-images.githubusercontent.com/68813874/102759360-04d49f80-439a-11eb-9fe1-7df0f5ea683f.png)

Image after image segmentation using active contour based segmentation

![image](https://user-images.githubusercontent.com/68813874/102759427-1ddd5080-439a-11eb-832d-708e7101ccc9.png)

Final output image

![image](https://user-images.githubusercontent.com/68813874/102759481-3188b700-439a-11eb-9c56-fef13b74a4c5.png)

Final output you will see in matlab

![Screenshot (154)](https://user-images.githubusercontent.com/68813874/102760719-f7b8b000-439b-11eb-9a42-b8dd09abf49b.png)


