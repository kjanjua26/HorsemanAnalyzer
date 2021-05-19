<p align="center">
  <img src="/logo/banner.png"/>
</p>
<hr>

# HorsemanAnalyzer :musical_note:
A mac-based song analyzer application built to classify and play songs based on your mood.

## Version 1.0
The first version contains the option to classify and play songs based on mood (currently there are three moods to choose from: happy, sad, romantic).
The goal is to learn a classifer to classify songs into one of the three moods and then play a song that is a closest match (in terms of signal distance). I am using Dynamic Time Wraping (DTW) to compute the signal distance.

### Features

1. Maintain a local library of songs and work on that :+1:
2. Eventually plan on dyanmic functioning directly on Youtube, or perhaps running a backend storage server somewhere (Pi or so?)
3. Extract features (MFCCs) :+1:
4. Learn a classifier to categorize songs into three moods: happy, sad, romantic
5. Peform DTW on the library and fetch similar songs

