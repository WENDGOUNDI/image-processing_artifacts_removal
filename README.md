# Image Processing Artifacts Removal
In this work, we are using image processing method via OpenCV to remove artifacts on images. The Lock3D face dataset infrared images contain artifacts causes by the devices used to captute the infrared images. Training a model with such noise can impact the result. Therefore a special preprocessing step should be applied. 

# Process
1. Apply thresholding
2. Save mask from thresholding
3. Apply inpaintaing according to the image mask
4. Recover proper images

# Results
![result_1](https://user-images.githubusercontent.com/48753146/155949509-4139d95b-4b7d-4ce5-8b9c-1ce15189081b.png)
![result_2](https://user-images.githubusercontent.com/48753146/155949500-3a82a663-9d5e-4768-8430-ae96b637f8ca.png)
