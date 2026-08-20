# Image Smoothing and Sharpening Using OpenCV

## Aim

To write a Python program using OpenCV to apply different smoothing filters (Averaging, Weighted Averaging, Gaussian, Median) and sharpening filters (Laplacian Kernel and Laplacian Operator) for image enhancement, and display each result separately along with the original image for comparison.

---

## The program performs the following operations:

- Read and display an input image  
- Apply Averaging filter  
- Apply Weighted Averaging filter  
- Apply Gaussian filter  
- Apply Median filter  
- Apply Laplacian sharpening using kernel  
- Apply Laplacian operator  
- Display all outputs for comparison  

---

##  Software Used

- Anaconda – Python 3.7  
- Jupyter Notebook / VS Code  
- OpenCV (cv2)  
- NumPy  
- Matplotlib  

---

##  Algorithm

### Step 1:
Import the required libraries: OpenCV, NumPy, and Matplotlib.

### Step 2:
Read the input image (e.g., `image.jpg`).

### Step 3:
Convert the image from BGR to RGB format for display.

### Step 4:
Apply Averaging Filter using `cv2.blur()`.

### Step 5:
Apply Weighted Averaging Filter using a custom kernel with `cv2.filter2D()`.

### Step 6:
Apply Gaussian Filter using `cv2.GaussianBlur()`.

### Step 7:
Apply Median Filter using `cv2.medianBlur()`.

### Step 8:
Apply Laplacian Sharpening using Kernel with `cv2.filter2D()`.

### Step 9:
Convert image to grayscale and apply Laplacian Operator using `cv2.Laplacian()`.

### Step 10:
Display all filtered images using a grid layout for comparison.

---

##  Developed By

- **Name:** VEDHA M 
- **Register No:** 212225230292

---

##  Output

### Smoothing Filters

- Averaging filter produces blurred image
-  <img width="891" height="429" alt="image" src="https://github.com/user-attachments/assets/4845aaec-25d6-437f-a73b-283ba3798f47" />
- Weighted averaging provides smoother result with less distortion
- <img width="873" height="392" alt="image" src="https://github.com/user-attachments/assets/c7855f2d-c4d5-4695-9323-ec3678549888" />
- Gaussian filter preserves edges better while reducing noise
-  <img width="886" height="406" alt="image" src="https://github.com/user-attachments/assets/ad63ef74-2b01-4cd4-b8bf-ab32898acc4c" />
- Median filter removes salt-and-pepper noise effectively
- <img width="870" height="423" alt="image" src="https://github.com/user-attachments/assets/1f01ba57-aa0a-4f90-aff9-f03d919707cc" />
  

###  Sharpening Filters

- Laplacian kernel enhances edges and fine details
- <img width="878" height="398" alt="image" src="https://github.com/user-attachments/assets/ee21e172-d00d-40f8-a35f-1f8fb777d9fb" />
- Laplacian operator detects edges clearly in grayscale
- <img width="877" height="371" alt="image" src="https://github.com/user-attachments/assets/7eaa1b9c-bb1f-4334-9b00-077cacfa7303" />
---

##  Result

Thus, smoothing filters and sharpening filters are successfully implemented using OpenCV.

The smoothing filters reduce noise and improve image quality, while sharpening filters enhance edges and details for better feature extraction.
