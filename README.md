# A 3D CNN Model with Multi-Feature Fusion for Enhancing Human Emotion Recognition from Speech

This repository contains the source code for the thesis titled **"A 3D CNN MODEL WiTH MULTi‑FEATURE FUSiON FOR ENHANCiNG HUMAN EMOTiON RECOGNiTiON FROM SPEECH"**. The thesis was presented and published at the 6th International Conference on Communication and Computational Technologies (ICCCT 2024) at Rajasthan Institute of Engineering and Technology, Jaipur, India.

## Abstract

Human emotion recognition from speech has significant applications in various fields such as human-computer interaction, mental health monitoring, and customer service. This project presents a novel 3D Convolutional Neural Network (CNN) model incorporating multi-feature fusion to enhance the accuracy of emotion recognition from microphone-captured speech data.

## Features

- Developed a 3D CNN Classifier to identify emotions from speech data.
- Utilizes MFCC, chroma shift, and mel-spectrogram features, forming a 3D tensor for detailed emotional cue analysis.
- Demonstrated superior accuracy compared to state-of-the-art models.

## Installation

To run this project, you will need to have Python and the necessary libraries installed. You can install the required libraries using:

```bash
pip install -r requirements.txt
```

## Dataset

The dataset used for training and evaluation is available on Kaggle. You can access it from this [link](https://www.kaggle.com/datasets/uwrfkaggler/ravdess-emotional-speech-audio).

## Usage

To train the model, run:

```bash
python train.py
```

To evaluate the model, run:

```bash
python evaluate.py
```

## Results

Our 3D CNN model introduces a novel approach by incorporating three distinct feature extraction techniques—MFCC, chroma shift, and mel-spectrogram—stacked along the Z-axis, forming the third dimension. This approach resulted in improved accuracy for human emotion recognition from speech.

## Kaggle Link

For more details and to access the notebook, visit the [Kaggle notebook](https://www.kaggle.com/code/hamadismail/ravdess-humanemotionrecognition-3d-cnn).

## Publication

**This work was published at:**

- 6th International Conference on Communication and Computational Technologies (ICCCT 2024)
- Rajasthan Institute of Engineering and Technology, Jaipur, India

<!--
## Citation

If you use this code in your research, please cite our paper:

```bibtex
@inproceedings{your_paper_citation,
  title={A 3D CNN Model with Multi-Feature Fusion for Enhancing Human Emotion Recognition from Speech},
  author={Your Name and Co-authors},
  booktitle={6th International Conference on Communication and Computational Technologies (ICCCT 2024)},
  year={2024},
  address={Jaipur, India}
}
```

## License

This project is licensed under the MIT License - see the LICENSE file for details.

-->

## Acknowledgments

We would like to thank the organizers of ICCCT 2024 and the Rajasthan Institute of Engineering and Technology for their support.
