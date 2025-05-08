# Emotion-Based Face Filter
A Computer Vision tool using OpenCV for face detection and FER for emotion recognition (~70% accuracy). Applies custom filters (e.g., smiley for "happy") and displays emotion at the bottom. Inspired by Snapchat filters.

## Features
- Face detection with Haar Cascade Classifier.
- Emotion recognition (happy, sad, angry) with FER.
- Emotion-specific overlays and bottom text display.

## Results
- Happy face → Green circle, "Emotion: happy"
- Sad face → Blue teardrop, "Emotion: sad"

## Setup
- Run in Google Colab with OpenCV and FER.
- Requires `haarcascade_frontalface_default.xml`.

## Demo
<table>
  <tr>
    <td align="center">
      <img src="filtered_happy.png" alt="Happy" width="300"/><br/>
      <strong>Emotion: Happy (0.99)</strong>
    </td>
    <td align="center">
      <img src="filtered_sad.png" alt="Sad" width="300"/><br/>
      <strong>Emotion: Sad (0.65)</strong>
    </td>
  </tr>
</table>
