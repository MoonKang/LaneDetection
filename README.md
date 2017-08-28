# LaneDetection

Lane Detection project can be decomposed into three sections.

### 1. Grayscale, Blur, Canny Edge
### 2. Utility functions: Masking, Drawing lines, Applying lines to image
### 3. Hough Transform

### 1. Grayscale, Blur, Canny Edge
Use of color to detect lanes faces a multitude of problems, as lanes are not always the same color and different lighting conditions (day, night, etc) can cause misdetections. To overcome, I have firstly grayscaled and blurred the image slightly to reduce color sensitiveness. 

Then, I applied canny edge techniques to measure change of gradients and identify edges of objects. 
![Alt text](images/canny_image.jpeg)
