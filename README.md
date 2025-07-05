# video-dehazing-ml
Machine Learning based Video Dehazing using OpenCV 
# Video Dehazing Using Machine Learning

This project focuses on enhancing video clarity by removing haze from video frames using machine learning techniques. The system processes video input, extracts individual frames, applies both traditional and deep learning-based dehazing methods, and reassembles the frames into a clear output video.

## 📌 Features

- Frame extraction and reconstruction using OpenCV
- Image dehazing using:
  - Traditional dark channel prior (DCP)
- Evaluation metrics: PSNR (Peak Signal-to-Noise Ratio) and SSIM (Structural Similarity Index)

## 🔧 How It Works

1. **Video Processing**:
   - Input video is split into frames.
   - Each frame is preprocessed (resizing, normalization).

2. **Dehazing Techniques**:
   - **Traditional**: Uses image processing methods like DCP and histogram equalization.
   - 
3. **Reconstruction**:
   - Processed frames are combined back into a video.

4. **Evaluation**:
   - The dehazed frames are compared with ground truth using PSNR and SSIM.

## 🧪 Results
 Significant improvements were observed in visibility and sharpness.

## 📂 Folder Structure

