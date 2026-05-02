# Audio-Signal-Processing
This project focuses on detecting specific audio signals from raw audio input using a lightweight and efficient approach. Instead of relying on heavy deep learning models, the system uses signal processing techniques to identify patterns in audio data under constrained conditions.

## Approach
- Preprocess audio input  
- Extract features (MFCC / Spectrogram)  
- Apply sliding window analysis  
- Detect signals using similarity + threshold  

## Why This Approach
- Works with limited data  
- Efficient and interpretable  
- Suitable for real-world constraints  

## Limitations
- No ground truth → no F1 evaluation  
- Sensitive to noise  
- Requires threshold tuning  

## Tech Stack
Python, NumPy, Librosa  

## Author
Sundaram Singh
