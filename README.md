Multi View 3D Reconstruction

This repository contains the reports for the work done during my internship at IISc, Bangalore (May-July 2017 and Nov-Dec 2017).  

For multi-view 3D reconstruction, we use the 'Iterative Closest Point (ICP)' algorithm. Errors in the angle and axis of rotation are analysed on synthetic and real-world datasets. The method is compared with Point Cloud Library's inbuilt ICP algorithm. Further, a simple version of the algorithm has also been implemented in python.

We next perform feature based 3D reconstruction. This method relies on feature matching and performs better than ICP which is matches points based on the geometric distance between them. Fast Feature Point Histogram (FPFH) features are computed for each point cloud followed by feature matching and prediction of homography using Umeyama's method. Motion averaging is done to find a minimal solution. For further analysis, we use MAICP (Motion Averaged ICP) which uses the ICP algorithm to find transformations followed by a motion averaging step. 

Best results are achieved with the motion averaged feature based 3D reconstruction algorithm. 
