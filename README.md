# Image-Processing-for-Lung-Cancer-Detection

In this project, I tried to implement image processing algorithms for lun cancer detection usig matlab on Computer Tomography(CT) images.

The CT images that I used is obtained from http://www.via.cornell.edu/lungdb.html. 

Basically there are three steps in image processing step that we used as follows:
1. Gabor filter for image enhancement
2. Marker controlled watershed with masking for image segmentation
3. Binarization for image classification

In binarization I have calculated number of black pixels in segemented area which later compared with threshold value which is obtained by researchers by calculating average number of black and white pixels in segemented area.
There is no metrics performance due to restriction of image label class.

To run the program, you need matlab. You can use one sample image that I uploaded. For another image you can download from http://www.via.cornell.edu/lungdb.html. Image processing based detection of lung cancer on CT scan images

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
