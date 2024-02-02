# EmoVideoNet: A Comprehensive Video Dataset for Emotion Recognition


# $${\color{red}\text{Now our dataset preparation has been finished}}$$ 
# $${\color{red}\text{We are on the Final Step: Label Validation}}$$ 
# $${\color{blue}\text{Specific Usage and Way to Contribute Will be Specified Later !}} $$

## Welcome to EmoVideoNet

EmoVideoNet is an extensive and rigorously curated video dataset aimed at transforming the field of emotion recognition. This dataset features more than 5,000 short video clips, each carefully annotated to represent a range of human emotions. EmoVideoNet stands at the intersection of Cognitive Science, Psychology, Computer Science, and Medical Science, providing a unique tool for both research and application in these fields.

### Why EmoVideoNet?

Inspired by the revolutionary ImageNet, EmoVideoNet aspires to be a benchmark in the emotional AI space, offering meticulously labeled and consistently processed video data to the global research community.

- **Rich Emotional Annotations:** Our dataset encompasses a spectrum of eight emotions—Anger, Contempt, Disgust, Enjoyment, Fear, Sadness, Surprise, and Neutral—each annotated with precision.
- **Uniform Video Quality:** We ensure uniform hue, contrast, and brightness across all videos to provide a standard quality baseline for algorithm development.
- **Exponential Growth and Community Driven:** EmoVideoNet is rapidly expanding, with new contributions regularly enhancing the depth and breadth of the dataset.

### Dataset Features

- **Detailed Emotional Range:** EmoVideoNet covers a broad array of emotional states, meticulously labeled for accurate recognition.
- **Pre-Processed for Excellence:** All clips are pre-processed to ensure high fidelity and uniformity, setting a high standard for training data quality.
- **Inviting Global Contributions:** We encourage contributions from researchers and practitioners around the world to help grow and diversify the dataset.

### How to Contribute

Contributions are vital for EmoVideoNet to thrive. For instructions on how to contribute, please visit our [contribution guidelines](#).

### Getting Started

For information on how to access and use EmoVideoNet for your research or applications, please consult our [usage documentation](#).

### Usage Example

```python
# Example code to load the EmoVideoNet dataset

import emotionnet

# Load dataset
dataset = emotionnet.load('/path/to/emotionnet')

# Loop through the dataset
for video in dataset:
    frames, emotions = video['frames'], video['emotions']
    # Insert your model training or evaluation code here
```

### Citation
If you use EmoVideoNet in your academic or industry research, please cite it as follows:

```bibtex
@misc{emotionnet2023,
  title={EmoVideoNet: A Comprehensive Video Dataset for Emotion Recognition},
  author={Peiran L, Linbo T, Xizheng Y. University of Wisconsin Madison},
  year={2024},
  publisher={\url{https://github.com/PeiranLi0930}},
  journal={*},
  howpublished={\url{https://github.com/PeiranLi0930/emotionnet}},
}
```

### License
EmoVideoNet is released under the [BSD-3-Clause license](LICENSE).

### Contact
For support or further inquiries, please contact us at [pli258@wisc.edu](mailto:pli258@wisc.edu).

### Acknowledgments
We acknowledge the collective efforts of all contributors from the University of Wisconsin Madison's Medical Science Center Computer Vision Group and the global research community. Your insights and contributions are shaping the future of emotion recognition technology.
