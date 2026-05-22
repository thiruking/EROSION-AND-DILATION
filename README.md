# Implementation of Erosion and Dilation

## Aim

To implement Erosion and Dilation using Python and OpenCV.

---

## Objective

The objective of this experiment is to perform basic morphological operations such as erosion and dilation on an image using OpenCV.

---

## Software Required

- Python 3.x
- OpenCV (`cv2`)
- NumPy
- Matplotlib
- Jupyter Notebook / VS Code

---

## Theory

Morphological operations are image processing techniques used to process binary and grayscale images based on their shapes.

### Erosion
Erosion removes pixels from the boundaries of foreground objects. It reduces the thickness of white regions in an image.

### Dilation
Dilation adds pixels to the boundaries of foreground objects. It increases the thickness of white regions in an image.

These operations are commonly used in noise removal, shape extraction, and image preprocessing.

---

## Algorithm

### Step 1:
Import the required libraries such as OpenCV, NumPy, and Matplotlib.

### Step 2:
Create or read the input image.

### Step 3:
Create a structuring element (kernel) using NumPy.

### Step 4:
Apply erosion operation using `cv2.erode()`.

### Step 5:
Apply dilation operation using `cv2.dilate()` or morphological gradient operation.

### Step 6:
Display the original image, eroded image, and dilated image.

---

## OpenCV Functions Used

| Function | Purpose |
|---|---|
| `cv2.putText()` | Create text image |
| `cv2.erode()` | Perform erosion |
| `cv2.dilate()` | Perform dilation |
| `cv2.morphologyEx()` | Apply morphological operations |
| `np.ones()` | Create kernel |
| `plt.imshow()` | Display image |

---

## Expected Output

The program produces the following outputs:

- Original text image
- Eroded image
- Dilated image

---

## Applications

- Noise removal
- Object boundary extraction
- Shape analysis
- Image preprocessing
- Character recognition
- Medical image processing

---

## Result

Thus, the text image is successfully processed using erosion and dilation operations in Python and OpenCV.

---

## Developed By

**Name:**  THIRUMALAI K

**Register Number:** 212224240176