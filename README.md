## Welcome to my georeferencing project Pages

You can access the doxygen documentation on https://bledem.github.io/georeferencing/html/index.html
This presents all the functions and class I used to geo-reference images taken from high-altitude UAV with feature matching with already geo-referenced images (manually by the user or with existing dataset).

This is an extract of the library I coded (from CG1 to CG6). The code is not public. 

The strategy used is based on homography computation to guess the successive tranformation between the images and between the world frame of reference and the UTM coordinates.

With these codes, every pixels were attributed a UTM or lat/lon longitudes and enabled to localize all the photo and area taken by the drone. 
