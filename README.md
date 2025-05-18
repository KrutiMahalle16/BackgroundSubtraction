# BackgroundSubtraction
# Background Subtraction for Motion Detection

This project implements **background subtraction** to detect moving objects in a video using Python and OpenCV. Background subtraction is a common technique in video surveillance and computer vision for detecting moving objects by separating the background from the foreground.

---
## 🧠 What is Background Subtraction?

Background subtraction is a method of segmenting out foreground objects from the background in a sequence of video frames. It helps in identifying motion or changes in scenes by detecting pixels that differ significantly from a background model.

---

## 🛠️ Technologies Used

- Python 3.x
- OpenCV (cv2)
- NumPy

---
## 🔄 Method Overview

1. Load input video.
2. Initialize background subtractor using OpenCV’s built-in algorithms:
   - `cv2.createBackgroundSubtractorMOG2()`
   - or `cv2.createBackgroundSubtractorKNN()`
3. Apply the subtractor to each frame to detect motion.
4. Use morphological operations to clean the mask.
5. Display or save the motion mask over time.

---

## 📷 Sample Output

The output video highlights moving objects with a white foreground mask against a black background. You can also draw bounding boxes around moving areas.

---

## ✅ Conclusion

This project demonstrates a practical approach to motion detection using background subtraction. It’s a foundational technique for security systems, traffic monitoring, and object tracking.

---

