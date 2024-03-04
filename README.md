# Large-Scale Selfie Video Dataset (L-SVD): A Benchmark for Emotion Recognition

## $${\color{red}\text{We are releasing the dataset in batches}}$$
## Validated Batch 1 and 2: [Google Drive](https://drive.google.com/drive/folders/1alXjtSisiDHY3akoReIU6V2AzbvW0rau?usp=sharing) or [HuggingFace(Recommend)](https://huggingface.co/datasets/peiranli0930/L-SVD)<br/>  $${\color{navy}\text{Note: Please specify your Contact Info and Affiliation(s) when requesting access}} $$



## Welcome to L-SVD

L-SVD is a comprehensive and meticulously curated video dataset designed to revolutionize the field of emotion recognition. With over 20,000 short video clips, each precisely annotated to reflect a wide range of human emotions, L-SVD serves as a pivotal resource at the confluence of Cognitive Science, Psychology, Computer Science, and Medical Science. Our dataset is crafted to advance research and applications within these dynamic fields, offering an unparalleled tool for innovation and discovery.

**[Github Repository](https://github.com/PeiranLi0930/L-SVD)** <br/>  **[HuggingFace Dataset](https://huggingface.co/datasets/peiranli0930/L-SVD)** <br/> **[Papers With Code](https://paperswithcode.com/dataset/l-svd)**

### Why L-SVD?

Drawing inspiration from the transformative ImageNet, L-SVD aims to establish itself as a cornerstone in the domain of emotional AI. We provide the global research community with a dataset characterized by its detailed labeling and uniform processing standards, ensuring high-quality video data for cutting-edge research and development.

#### Key Features 
- **Rich Emotional Annotations**: L-SVD encompasses a spectrum of eight emotions—Anger, Contempt, Disgust, Enjoyment, Fear, Sadness, Surprise, and Neutral. Each emotion is annotated with unparalleled precision, providing a robust foundation for emotion recognition algorithms.
- **Uniform Video Quality**: To facilitate algorithm development and testing, all videos within L-SVD maintain consistent hue, contrast, and brightness, ensuring a standardized quality baseline across the dataset.
- **Community-Driven Expansion**: L-SVD is in a state of continuous growth, with contributions from the global community enriching the dataset's diversity and depth.

### Dataset Features

- **Comprehensive Emotional Spectrum**: Our dataset offers a wide-ranging exploration of human emotions, each meticulously labeled to support precise recognition and analysis.
- **Optimized for Research Excellence**: Through careful pre-processing, L-SVD sets a benchmark for training data quality, offering high fidelity and uniformity across all clips.
- **Global Participation**: We warmly invite researchers and practitioners worldwide to contribute to L-SVD, fostering a diverse and expansive dataset.

## How to Contribute

Your contributions are essential to the growth and success of L-SVD. To contribute, please follow the instructions to upload your data [HERE](https://drive.google.com/drive/folders/1s-Ar6O2g-IYYXheRkO01FHiuGykjSeX6?usp=sharing). We will review and validate the labels within a few days of submission.

Join us in advancing the fields of Machine Learning and Deep Learning! After submitting your data, please email [ME](mailto:pli258@wisc.edu) with the details of your submission, including filepaths, modalities, affiliations, and GitHub Username. We look forward to acknowledging your valuable contributions on our homepage.  

## Getting Started

Our dataset, L-SVD, is shared via Google Drive, enabling easy access and collaboration. The dataset is released in batches, ensuring ongoing updates and expansions.

To access L-SVD, please visit [U-SVD](https://drive.google.com/drive/folders/1alXjtSisiDHY3akoReIU6V2AzbvW0rau?usp=sharing) and submit a request including your Contact Information and Affiliations. This process ensures a collaborative and secure environment for all users.

Thank you for your interest in L-SVD. Together, we can push the boundaries of emotion recognition research and development.

### Usage Example

```python
# Example code to load the L-SVD dataset

import emotionnet

# Load dataset
dataset = emotionnet.load('/path/to/emotionnet')

# Loop through the dataset
for video in dataset:
    frames, emotions = video['frames'], video['emotions']
    # Insert your model training or evaluation code here
```


### Citation
If you use L-SVD in your academic or industry research, please cite it as follows:

```bibtex
@misc{emotionnet2023,
  title={L-SVD: A Comprehensive Video Dataset for Emotion Recognition},
  author={Peiran L, Linbo T, Xizheng Y. University of Wisconsin Madison},
  year={2024},
  publisher={\url{https://github.com/PeiranLi0930}},
  journal={*},
  howpublished={\url{https://github.com/PeiranLi0930/emotionnet}},
}
```

### License
L-SVD is released under the [BSD-3-Clause license](LICENSE).

### Contact
For support or further inquiries, please contact us at [pli258@wisc.edu](mailto:pli258@wisc.edu).

### Acknowledgments
We acknowledge the collective efforts of all contributors from the University of Wisconsin Madison's Computer Science Department and the global research community. Your insights and contributions are shaping the future of emotion recognition technology.
