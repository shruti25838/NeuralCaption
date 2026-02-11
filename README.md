# NeuralCaption

About the Project
This project builds an Image Caption Generator that automatically describes images in natural language. It uses deep learning with CNNs for image feature extraction and LSTMs for text sequence generation. The model is trained on the Flickr8k dataset, which contains 8,000 images with 5 captions each.


Features

VGG16 pre-trained CNN for feature extraction

LSTM network for generating captions word by word

Fusion of image + text features for accurate captioning

Evaluation using BLEU Score

Implementation and training environment: Kaggle

Results

BLEU-1 Score: 0.544

BLEU-2 Score: 0.319

Generates meaningful captions aligned with visual context

Dataset

Flickr8k (8,000 images, 5 captions each)

Download: Kaggle – Flickr8k Dataset

Libraries Used

numpy

matplotlib

keras

tensorflow

nltk

Neural Network Architecture

VGG16 → CNN for image feature extraction

LSTM → Sequence model for caption generation

CNN-LSTM Fusion → Combines image + text features for prediction

Video Tutorial

Complete step-by-step walkthrough available here:
YouTube Tutorial

Future Work

Train on larger datasets (MSCOCO, Flickr30k)

Improve evaluation with METEOR, ROUGE, or CIDEr

Add beam search for more fluent captions

Contributing

Pull requests and suggestions are welcome. If you’d like to extend the project, open an issue or fork the repo.


“Teaching machines to see and speak the world, one caption at a time.”
