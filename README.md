# 🎙️ Speaker Recognition System using MATLAB GUI

This project is a **MATLAB App Designer GUI** for real-time speaker identification. It allows:
- Adding and managing a voice database
- Recording and testing voices
- Applying various noise levels (SNR)
- Reconstructing signals using interpolation methods
- Visualizing frequency spectra and MFCCs
- Tracking recognition accuracy with TP/FP stats

## 🚀 Features
- 🎤 Real-time voice recording from microphone
- 📁 Voice database with dynamic speaker management
- 📈 Signal plotting (Original & Reconstructed)
- 🔊 Add controlled noise (10/20/30 dB)
- 🔧 Signal reconstruction: ZOH, FOH, Spline
- 🧠 MFCC feature extraction
- ✅ True Positive / False Positive tracking
- 🧪 Speaker verification and accuracy evaluation

## 🖼️ Sample Output (Screenshot)
![GUI Screenshot](18e7fb57-ec7d-4140-b134-1533877418a6.png)

## 🛠 Technologies Used
- MATLAB App Designer (GUI)
- Signal Processing Toolbox
- Audio Toolbox
- Vector Quantization (VQ)
- MFCC feature extraction

## 📂 Files Included
- `gui.m` – Main app code
- `name_database.mat` – Stores audio samples and speaker info
- `feedback_metrics.mat` – Stores TP/FP counts
- `recognition_stats.mat` – Accuracy tracking
- `.wav` files – Saved recordings

## 📦 How to Run
1. Open MATLAB.
2. Load `gui.m` and run it.
3. Interact with the GUI:
   - Add voice samples
   - Run speaker identification
   - Apply noise and reconstruction
   - View plots and recognition stats

## 📊 Accuracy Output
Displayed in the GUI:
Speaker Identified: Ahsan
Distance: 0.27
Feedback: Correct (TP)
TP: 3 | FP: 0 | Accuracy: 100.00%
