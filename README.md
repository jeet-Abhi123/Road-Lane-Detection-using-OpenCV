# Road-Lane-Detection-using-OpenCV

I have implemented this without any machine learning model, this was done using openCV libraries and concepts from computer vision


![Screenshot 2024-12-27 231210](https://github.com/user-attachments/assets/9b95828b-02ae-4dcc-b805-c2c4c51c2452)


## **Methodology :** <br>
## Step 1) Applied Gaussian Blur to remove any noise in the image <br>

![Screenshot 2024-11-21 221143](https://github.com/user-attachments/assets/be6e613e-faaa-42c3-b69d-a37eba7d032d)


 ## Step 2) Applied masking to detect edges in the specified region of interest <br>

![Screenshot 2024-11-21 221203](https://github.com/user-attachments/assets/193b317e-5fee-47e6-9f6a-1f68a6d63e9a)


## Step 3) Then applied Canny edge detection <br>

![Screenshot 2024-11-21 221213](https://github.com/user-attachments/assets/786afb42-6067-4189-ad84-0fc23bffa114)


## Step 4) Hough Transform to detect lines and draw them  <br>

![Screenshot 2024-11-21 221224](https://github.com/user-attachments/assets/6cb46c65-cd6b-422e-a99f-650a78fa9feb)


## Step 5) Hyperparameter Tuning : Adjusting the threshold values of the hough transform and canny edge to detect properly <br>


