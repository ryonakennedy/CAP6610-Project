# CAP6610-Project

## Install Dependencies ##
* Python3
* librosa
* matplotlib
* pandas
* opencv-python
* pydub

## Install Tools ##
* ffmpeg

## Setup ##
1. Clone repository
```
git clone https://github.com/ryonakennedy/CAP6610-Project
```
2. Change to working directory from clone
```
cd CAP6610-Project
```
3. Create folder for music files used to extract features from
```
mkdir Dataset
```
4. Copy music files into Dataset folder retaining music folder hierarchy
```
Dataset
├── Not_Progressive_Rock
└── Progressive_Rock_Songs
Dataset/Not_Progressive_Rock/
├── Other_Songs
└── Top_Of_The_Pops
```
## Usage ##
For extracting features from sound files
```
./ExtractFeatures.py
```
