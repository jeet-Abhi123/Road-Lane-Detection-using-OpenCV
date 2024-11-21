# Road-Lane-Detection-using-OpenCV

I have implemented this without any machine learning model, this was done using openCV libraries and concepts from computer vision


https://github.com/user-attachments/assets/be03d0fc-8395-43a6-a6da-0d6ce3f9121a

**Methodology :**
Step 1) Applied Gaussian Blur to remove any noise in the image
Step 2) Applied masking to detect edges in the specified region of interest
Step 3) Then applied Canny edge detection 
Step 4) Hough Transform to detect lines and draw them
Step 5) Hyperparameter Tuning : Adjusting the threshold values of the hough transform and canny edge to detect properly


