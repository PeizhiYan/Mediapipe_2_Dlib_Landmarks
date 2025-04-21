# Mediapipe to Dlib Face Landmarks Conversion

## [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

This tool converts Mediapipe's 478 face landmarks into Dlib's 68 face landmarks.

I created this tool because many projects still rely on Dlib's 68 landmarks format, while others use Mediapipe's face detector. To enable code reuse between both sides, this tool provides a practical solution.

## Flame-Head-Tracker
- This code is part of ```flame-head-tracker```: https://github.com/PeizhiYan/flame-head-tracker

## Install
```
pip install .
```

## Usage

```
from mediapipe2dlib.mp2dlib import convert_landmarks_mediapipe_to_dlib

# Convert Mediapipe dense landmarks to Dlib sparse landmarks
lmks_mp2dlib = convert_landmarks_mediapipe_to_dlib(lmks_mp)
```

## Example

![Alt text](./assets/example.jpeg)
