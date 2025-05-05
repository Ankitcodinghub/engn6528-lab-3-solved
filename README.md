# engn6528-lab-3-solved
**TO GET THIS SOLUTION VISIT:** [ENGN6528 Lab 3 Solved](https://www.ankitcodinghub.com/product/engn6528-lab-3-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;100060&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;2&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (2 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;ENGN6528 Lab 3 Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 138px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            5/5 - (2 votes)    </div>
    </div>
<div class="page" title="Page 1">
<div class="layoutArea">
<div class="column">
This is CLab-3 for ENGN6528. The goal of this lab is to help you familiar with, and practice:

<ul>
<li>Basic multi-view camera geometry, camera calibration. They are the basic building blocks for 3D visual reconstruction systems.</li>
<li>DLT method for two-view homography estimation.
Note, however, in all the lab task descriptions given below, we by default use Matlab as the preferred language. You are free to choose Python if you are more comfortable with Python. If you have not used Matlab or Python before, this lab is an opportunity to get you to quickly familiar with basic language usages of Matlab/Python for image processing and computer vision.

Special Notes:
</li>
</ul>
<ol>
<li>Each computer lab has three weeks. For the first week, students are expected to work on the lab assignment by yourselves. Tutors/Lab instructors will provide basic supervision in the following two weeks when students can discuss the potential questions with tutors.</li>
<li>Your Lab assignment will be marked based on the overall quality of your Lab Report in PDF format. The report is to be uploaded to Wattle site before the due time, which is usually on the Sunday evening of Week-3 session of your lab (22nd May, 2021).</li>
<li>It is normal if you cannot finish all the tasks within the two 2-hour sessions — these tasks are designed so that you will have to spend more time in order to finish all the tasks including finishing your Lab report. This suggests that, before attending the third lab session (in Week-3 session of each CLab), you must make sure that you have almost complete 80% of the assignment.</li>
</ol>
Academic Integrity

You are expected to comply with the University Policy on Academic Integrity and Plagiarism. You are allowed to talk with / work with other students on lab and project assignments. You can share ideas but not code, you should submit your own work. Your course instructors reserve the right to determine an appropriate penalty based on the violation of academic dishonesty that occurs. Violations of the university policy can result in severe penalties.

</div>
</div>
</div>
<div class="page" title="Page 2">
<div class="layoutArea">
<div class="column">
Task-1: 3D-2D Camera Calibration (15 marks) (Acknowledgement: Lab material courtesy of Professor. Du Huynh of UWA).

Camera calibration involves finding the geometric relationship between 3D world coordinates and their 2D projected positions in the image.

Four images, stereo2012a.jpg, stereo2012b.jpg, stereo2012c.jpg, and stereo2012d.jpg, are given for this CLab-3. These images are different views of a calibration target and some objects. For example, the diagram below is stereo2012a.jpg with some text superimposed onto it:

(Do not directly use the above image for your camera calibration work

as it has been scaled for illustration. Use the original (unlabelled) image files provided.)

On the calibration target there are 3 mutually orthogonal faces. The points marked on each face form a regular grid. They are all 7cm apart.

Write a Matlab function with the following specification

Function to perform camera calibration Function C = calibrate(im, XYZ, uv)

Input: im: is the image of the calibration target.

XYZ: is a Nx3 array of XYZ coordinates of the calibration target points. uv: is a N x 2 array of the image coordinates of the calibration target

points.

Outputs: C: is the 3 x 4 camera calibration matrix.

The variable N should be an integer greater than or equal to 6.

This function should also plot the uv coordinates onto the image of the calibration target. It also projects the XYZ coordinates back into image coordinates using the calibration

</div>
</div>
</div>
<div class="page" title="Page 3">
<div class="layoutArea">
<div class="column">
matrix and plots these points too as a visual check on the accuracy of the calibration process.

Lines from the origin to the vanishing points (namely, world coordinate system) in the X, Y and Z directions are overlaid on the image.

The mean squared error between the positions of the uv coordinates and the projected XYZ coordinates is also reported.

Generally, we ask you to implement a function: MATLAB user:

function C = calibrate(im, XYZ, uv)

Python user:

def calibrate(im, XYZ, uv) return C

From the 4 supplied images (stereo2012a.jpg, stereo2012b.jpg, stereo2012c.jpg, and stereo2012d.jpg), choose any image to work on. Use the suggested right-hand coordinate system shown in the diagram above and choose a sufficient number of calibration points on the calibration target.

Store the XYZ coordinates in a file so that you can load the data into Matlab and Python (You can choose your preferred datatype, for instances, mat in MATLAB and numpy array in Python) and use them again and again. Note that each image can be calibrated independently, so you can choose different calibration points to calibrate each image. Neither do the numbers of calibration points need to be the same for your chosen images.

The uv coordinates can be obtained using the MATLAB function ginput. If one invokes ginput as follows:

&gt;&gt; uv = ginput(12) % e.g., to digitise 12 points in the image

and digitises a series of points by clicking with the left mouse button, then uv will be a matrix containing the column and row coordinates of the points that you digitised.

(As for Python users, you can get matplotlib.pyplot.ginput to get uv coordinates. The operation is similar with that in MATLAB) https://matplotlib.org/3.1.1/api/_as_gen/matplotlib.pyplot.ginput.html

After the above operation, the variable uv should be a 12 × 2 matrix, each row of which should contain the coordinates of one image point.

Note: You need to ensure that, for each image, the numbers of 3D and 2D calibration points are the same. For example, if your uv variable is a 12 × 2 matrix, then your XYZ variable should be a 12 × 3 matrix. Also, the points should appear in the same order in these two matrices.

Use the DLT algorithm to solve the unknown camera calibration matrix of size 3×4. (Refer to lecture Notes and textbook:

Multiple View Geometry in Computer Vision Section 7 (page 178),

</div>
</div>
</div>
<div class="page" title="Page 4">
<div class="layoutArea">
<div class="column">
Hints

(1) In writing your code you may need to ‘reshape’ a 2D vector into a 1D vector. You can use the function reshape or np.reshape (in MATLAB and Python respectively) to reshape a matrix to arbitrary dimensions.

(2) You can save your calibration matrices using Matlab’s save command. For

example, the command

&gt;&gt; save mydata im1 im2 calibPts uv1 uv2 C1 C2% (please do not use commas between variable names)

will save your variables im1 im2, calibPts, uv1, uv2, C1, and C2 in a file

called mydata.mat. At a later date you can load this data into the memory using the

command:

&gt;&gt; load mydata

The variables im1 im2, calibPts, uv1, uv2, C1, and C2 will then be restored in your workspace.

Python users would handle the saving and loading problem by np.save and np.load. https://docs.scipy.org/doc/numpy/reference/generated/numpy.save.html https://docs.scipy.org/doc/numpy/reference/generated/numpy.load.html

For Task-1, you should include the following in your Lab-Report PDF file:

<ol>
<li>List calibrate function in your PDF file. [3 marks]</li>
<li>List the image you have chosen for your experiment, and display the image in
your PDF file. [0.5 mark]
</li>
<li>List the 3×4 camera calibration matrix P that you have calculated for the
selected image. Please visualise the projection of the XYZ coordinates back

onto image using the calibration matrix P. [2 marks]
</li>
<li>Decompose the P matrix into K, R, t, such that P = K[R|t], by using the
following provided code (vgg_KR_from_P.m or vgg_KR_from_P.py). List the

results, namely the K, R, t matrices, in your PDF file. [1.5 marks]
</li>
<li>Please answer the following questions:
– what is the focal length of the camera? [1 mark]

– what is the pitch angle of the camera with respect to the X-Z plane in the
</li>
</ol>
world coordinate system? (Assuming the X-Z plane is the ground plane, then the pitch angle is the angle between the camera’s optical axis and the ground-plane.) [2 marks]

6. Please resize your selected image using buitin function from matlab or python to (H/2, W/2) where H, and W denote the original size of your selected image. Using the interface function, (ginput in Matlab, and matplotlib.pyplot.ginput in Python) to find the uv coordinates in the resized image. [1 mark]

a. Please display your resized image in the report, list your calculated 3×4 camera calibration matrix P’ and the decomposed K’, R’, t’ in your PDF file. [2 marks]

</div>
</div>
</div>
<div class="page" title="Page 5">
<div class="layoutArea">
<div class="column">
b. Please analyse the differences between 1) K and K’, 2) R and R’, 3) t and t’. Please provide the reasoning when changes happened or there are no changes. [2 marks]

Task-2: Two-View DLT based homography estimation. (10 marks)

A transformation from the projective space P3 to itself is called homography. A homography is represented by a 3×3 matrix with 8 degree of freedom (scale, as usual, does not matter)

The goal of this task is to the DLT algorithm to estimate a 3×3 homography matrix.

Pick any 6 corresponding coplanar points in the images left.jpg and right.jpg and get their image coordinates.

In doing this step you may find it useful to check the Matlab function ginput.

Calculate the 3×3 homography matrix between the two images, from the above 6 pairs of corresponding points, using DLT algorithm. You are required to implement your function in the following syntax.

Function to calculate homography matrix

H = homography (u2Trans, v2Trans, uBase, vBase)

Usage: Computes the homography H applying the Direct Linear Transformation Inputs: u2Trans, are vectors with coordinates u and v of the transformed image

v2Trans: point (p’)

</div>
</div>
</div>
<div class="page" title="Page 6">
<div class="layoutArea">
<div class="column">
Outpus: H:

</div>
<div class="column">
is a 3×3 Homography matrix

</div>
</div>
<div class="layoutArea">
<div class="column">
uBase, are vectors with coordinates u and v of the original base vBase: image point p

</div>
</div>
<div class="layoutArea">
<div class="column">
In doing this lab task, you should include the followings in your lab report:

<ol>
<li>List your source code for homography estimation function and display the two images and the location of six pairs of selected points (namely, plotted those points on images). [5 marks]</li>
<li>List the 3×3 camera homography matrix H that you have calculated. [2 mark]</li>
<li>Warp the left image according to the calculated homography. Study the factors
that affect the rectified results, e.g., the distance between the corresponding points, e.g the selected points and the warped ones. [3 mark] (Note: you can use buitin image warping functions in matlab and python.)

====================== End of CLab-3 ====================
</li>
</ol>
</div>
</div>
</div>
