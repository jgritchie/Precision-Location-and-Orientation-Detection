# Precision-Location-and-Orientation-Detection
Determine location and orientation of a standard square or rectangle in two dimensions using a camera and computer vision. This was programmed using the language Python, with the help of openCV, an open source computer vision library.

##Getting Started
Be sure to have a python2.0+, a capable IDE installed, and openCV installed

##Get it running
Choose an image with a distinct square image preferably with a plain background. This will make it easier to identify the contours of the square. The square being a different color helps to distinguish itself. After the image has been chosen, Shift + Right click the image and choose "Copy as Path". Use the cv.imread function to load in the image. You can change the foward slashes (\) to back slashes (/) or you can insert a "r" to ignore the foward slashes as I have.

##Results
If the program is able to find the square and the contours of such square, it should output a number of results. This includes the center of the square using two different methods, the angle of orientation, and the accuracy of the center in microns. The output of the

('4 points of square', array([[[254, 170]],

       [[218, 180]],

       [[228, 217]],

       [[265, 206]]]))
('Center using 4 corner points', [241.25, 193.25])
('Center using points inside sqaure and number of points used', [241.07718814610612, 193.39972432804961, 1451.0])
('Angle of Orientation', 14.588918732874532)
('Center in microns', 35.11029353600984)

#Acknowledgments
Aric Sanders' mentorship and guidance
Adrian Rosebrock's Document Scanner tutorial at pyimagesearch.com
