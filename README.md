<<<<<<< HEAD


# EmotionTalk 

> An Interactive Chinese Multimodal Emotion Dataset With Rich Annotations.

[![Python](https://img.shields.io/badge/python-3.9+-blue.svg)]()
[![Project Page](https://img.shields.io/badge/Project-Website-blue.svg)](https://github.com/NKU-HLT/EmotionTalk)

---


## 📖 Overview

We propose EmotionTalk, an interactive Chinese multimodal emotion dataset with rich annotations. This dataset provides multimodal information from 19 actors participating in dyadic conversational settings, incorporating acoustic, visual, and textual modalities. It includes 23.6 hours of speech (19,250 utterances), annotations for 7 utterance-level emotion categories (happy, surprise, sad, disgust, anger, fear, and neutral), 5-dimensional sentiment labels (negative, weakly negative, neutral, weakly positive, and positive) and 4-dimensional speech captions (speaker, speaking style, emotion and overall). The dataset is well-suited for research on unimodal and multimodal emotion recognition, missing modality challenges, and speech captioning tasks. To our knowledge, it represents the first high-quality and versatile Chinese dialogue multimodal emotion dataset, which is a valuable contribution to research on cross-cultural emotion analysis and recognition. Additionally, we conduct experiments on EmotionTalk to demonstrate the effectiveness and quality of the dataset. It will be open-source and freely available for all academic purposes. The dataset and codes will be made available at [EmotionTalk](https://github.com/NKU-HLT/EmotionTalk).

## 🚀 Getting Started
### Environment

```shell
conda env create -f environment.yml
```

## 🤗 Dataset Download

You can access the Emotiontalk dataset on HuggingFace Datasets:

[https://huggingface.co/datasets/BAAI/Emotiontalk](https://huggingface.co/datasets/BAAI/Emotiontalk)

### Tool
openface_win_x64  (https://drive.google.com/file/d/1-O8epcTDYCrRUU_mtXgjrS3OWA4HTp0-/view?usp=share_link  -> tools/openface_win_x64)

You need to follow the steps to run in EmotionTalk/run.sh. 

Please refer to run.sh for more details.

## 🙏 Acknowledgements

This project builds upon prior work from the [zeroQiaoba/MERTools](https://github.com/zeroQiaoba/MERTools) repository. We thank them for their contributions! 
