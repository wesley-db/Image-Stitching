# Image-Stitching
This code is an upgraded version of my image stitching homework from my computer vision class. In this version, the code to crop the dark spots was improved, and a smoothing feature was included.

The new cropping function took on a different approach than the original code, which was pre-given by my instructors. Instead of looking at the contour of the image, my code looked at the edges of the warped images to determine where to crop. As for the smoothing feature, it is not part of the original code. Multi-band blending was introduced briefly in the class, and I decided to implement it out of curiosity. It also reuses a function to create the Laplacian and Gaussian pyramids from my first homework in the same class.

Disclaimer: I modified the code so that people who copy and paste my work couldn't get a full score for the same assignment.

**Instruction**<br>
The images of the room and the mountain can be downloaded by running the code in the data sections.<br>
If you want to use your pictures, the following must be followed:
01. The image file names must be in ascending order, with the leftmost image having the lowest value and the rightmost image having the highest value.
02. To improve the chance of a successful panorama, pictures must be taken with auto-focus turned off; this ensures that the camera settings remain constant for all images.

<br>**Comparison Gallery**<br>
<p>
<em>Source Images</em>
<img  src="https://github.com/wesley-db/Image-Stitching/blob/main/mountainOrg.png">
</p>
<p>
<em>Original Code Result</em><br>
<img width=700 src="https://github.com/wesley-db/Image-Stitching/blob/main/mountain.png">
</p>
<p>
<em>Improved Code Result</em><br>
<img width=700 src="https://github.com/wesley-db/Image-Stitching/blob/main/mountain2.png">
</p>
<p>
<em>Source Images</em>
<img height=500 src="https://github.com/wesley-db/Image-Stitching/blob/main/roomOrg.png">
</p>
<p>
<em>Original Code Result</em><br>
<img width=700 src="https://github.com/wesley-db/Image-Stitching/blob/main/room.png">
</p>
<p>
<em>Improved Code Result</em><br>
<img  src="https://github.com/wesley-db/Image-Stitching/blob/main/room2.png">
</p>

**More Results**<br>
