# SentimentFusion: Multimodal Sentiment Analysis

SentimentFusion is a project that performs multimodal sentiment analysis using both sentence-level and word-level features from images and their captions. This project leverages BERT for sentence-level features and ResNet-50 for image features, and integrates them using a multimodal architecture to achieve over 90% accuracy on both training and test datasets.

## Dataset
We used the COCO Captions dataset for this project. You can download the images and captions CSV file from [this link](https://drive.google.com/drive/folders/1d9iLyCVUYm6yLxUZcW1zMCneWcOcIeaj?usp=sharing).

## Model Architecture
- **Sentence-Level Model**: Uses BERT for text features and ResNet-50 for image features.
- **Word-Level Model**: Uses Count Vectorizer with n-grams for text features and ResNet-50 for image features.

## Results
Both models surpassed 90% accuracy on both train and test data with smooth convergence of loss.

## How to Run
- Clone or download this repository and just run the jupyter notbook file
- Yes its that simple 🧁
## Contributing

Contributions are welcome! Please fork the repository and submit a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
