# Avalinguo-Audio-Dataset: Dataset for Speaker Fluency Level Classification 
 
The **Avalinguo Audio Dataset** is a labeled collection of 1424 audio recordings of non-native English speaking persons. 

This audio set is suitable for performing speaker fluency level classification. The audio recordings are categorized into 3 fluency classes arranged from low to high level. The audios were recording according to the next requirements:

- Spontaneous (non-scripted) conversations
- Random conversation topics
- Audios recorded with low-to-no background noise

**Audio file details:**
```
- Total 1420 audio files
- 5s non-overlapped segments
- Categorized into three fluency classes: low, intermediate, and high
- ~2 hours of recordings
- 450 audio clips per class (aprox.)
- Sample rates ranging from 22050 Hz to 48000 Hz
- Mono and multi-channel
- MP3 format
```

Fluency levels have been defined as:

- **Low fluency**: Person can understand frequently used expressions and give basic personal information. Person can talk about simple things on familiar topics but still speaks with unnatural pauses.
- **Intermediate fluency**: Person Can deal with common situations, for example, traveling and restaurant ordering. Describes experiences and events and is capable of giving reasons, opinions or plans. Can still make some unnatural pauses.
- **High fluency**: Can speak without unnatural pauses (no hesitation), doesn’t pause long to find expressions. Can use the language in a flexible way for social, academic, and professional purposes.

Clips have been manually gathered from three sources:

- Friends/Family recordings
- Language Center from Tecnológico de Monterrey (ITESM)
- Public Youtube Audios


## Download
The dataset can be downloaded here : ![](https://drive.google.com/drive/folders/1RBfbE6ya6ZOsjKJb80vgbxfzhzYC4iiH?usp=sharing)

The audios can also be individually downloaded in the **audio files** folder.
 
## Audio features extracted
- MFCC
- ZCR
- Spectral Flux
- Root Mean Square Energy

## Classifiers implemented 
- Support Vector Machine (SVM)
- Random Forest (RF)
- Convolutional Neural Network (CNN)
- Multilayer Perceptron (MLP)
- Recurrent Neural Network (RNN)

## Accuracies obtained 
**Note**: out of 1424 audio clips from the Avalinguo Audioset, with 30% test data, the reached accuracies are the following:
- SVM: 94.39%
- RF: 93.45%
- MLP: 92.52%
- CNN: 92.75% 
- RNN: 89.01%

