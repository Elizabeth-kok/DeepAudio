# Build a deep audio classifier with Python and Tensorflow

Working with audio data
1. Convert Audio data to Waveform (numerical representation) using Python
2. Transform waveform to spectrogram, Convolution Neural Network can process spectrogram and classify them
- Convert the audio wave to image representation , later on we will be able to use Image classification techniques to count the Capuchin density
3. Perform sliding window classification > Classifying Capuchin Bird Calls (count the number of specific audio detection within that clip)
4. Outcome is binary > 1 Bird Calls detected ; 0 Bird Calls not detected

Dataset
1. From Kaggle > https://www.kaggle.com/datasets/kenjee/z-by-hp-unlocked-challenge-3-signal-processing

Step 1
1. Load Audio Data
2. Create Tensorflow Dataset
3. Determine average length of a capuchin call

- When converting spectrogram, we want to ensure that we capture what is effectively a full capuchin call
- When we slice through our bigger clip, we capture the entire/majority of the call
- To ensure good predictions


