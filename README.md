# Car Classification with EfficientNetV2

This project classifies images of different car models using the pre-trained EfficientNetV2-B3 architecture via TensorFlow Hub. The model was trained and evaluated on a custom dataset consisting of 10 car classes. All development and experiments were conducted using Google Colab, which provided a convenient cloud-based environment with GPU support.

## Dataset

- The dataset consists of 610 images across 10 car brands/models.
- Split: 70% training, 15% validation, 15% testing.
- The dataset has been added to the repository.

## Model

- Feature extractor: [EfficientNetV2 B3 (TF Hub)](https://www.kaggle.com/models/google/efficientnet-v2/TensorFlow2/imagenet1k-b3-feature-vector)

## Performance

- **Test Accuracy**: 85.7%
- Evaluation includes:
  - Accuracy and loss graphs
  - Confusion matrix
  - Classification report (precision, recall, f1-score, support)
 
## Requirements

- `tensorflow>=2.11.0`
- `tensorflow-hub`
- `matplotlib`
- `seaborn`
- `scikit-learn`
- `numpy`
