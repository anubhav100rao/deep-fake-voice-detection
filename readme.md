# Deep fake voice detection

## Introduction
This project is a part of our mini project at IIIT Allahabad. The goal of this project is to detect deep fake voices under Dr. Ramesh Kumar Bhukya.


## Dataset
The dataset used for this project is [ASVspoof 2021](https://www.asvspoof.org/index2019.html) dataset. The dataset contains 4 types of data:
1. `train` - This folder contains the training data. It contains 2 folders `flac` and `wav`. The `flac` folder contains the audio files in flac format and the `wav` folder contains the audio files in wav format. The `flac` folder is used for training the model.
2. `dev` - This folder contains the development data. It contains 2 folders `flac` and `wav`. The `flac` folder contains the audio files in flac format and the `wav` folder contains the audio files in wav format. The `flac` folder is used for testing the model.
3. `eval` - This folder contains the evaluation data. It contains 2 folders `flac` and `wav`. The `flac` folder contains the audio files in flac format and the `wav` folder contains the audio files in wav format. The `flac` folder is used for testing the model.
4. `meta` - This folder contains the metadata of the audio files. It contains 3 files `ASVspoof2019.LA.cm.train.trn.txt`, `ASVspoof2019.LA.cm.dev.trl.txt` and `ASVspoof2019.LA.cm.eval.trl.txt`. These files contain the metadata of the audio files in the `train`, `dev` and `eval` folders respectively. The metadata contains the file name, the type of the audio file and the label of the audio file. The label of the audio file is either `bonafide` or `spoof`.

