VisionGPT2 - Image Captioning using Vision Transformers and GPT-2

Overview
VisionGPT2 is a hybrid image captioning model that combines the power of Vision Transformers (ViT) for image feature extraction and GPT-2 for generating natural language descriptions.
The model bridges the gap between computer vision and natural language processing by generating accurate, coherent, and context-aware captions for input images.
This project was tested using BLEU score as the evaluation metric and achieved a high BLEU score of 0.4877, indicating the effectiveness of cross-modal learning in image captioning tasks.

Features

Image feature extraction using Vision Transformer (ViT)

Text generation using GPT-2 language model

Evaluation using BLEU score

Coherent and context-aware caption generation

Technologies Used

Python

TensorFlow and Keras

Transformers (Hugging Face)

Vision Transformer (ViT)

GPT-2

NumPy, Pandas, Matplotlib

How It Works

Input image is passed through a pre-trained Vision Transformer to extract high-level image features

Extracted features are fed into the GPT-2 decoder as context

GPT-2 generates the image caption word-by-word based on the visual context

Dataset
The model is trained and evaluated using the COCO dataset

Evaluation
The performance of the model is evaluated using BLEU score
Achieved BLEU score: 0.4877

Applications

Assistive technology for visually impaired users

Image indexing and search

Automated content creation

Social media caption generation

Challenges

Training large models like ViT and GPT-2 together requires high computational resources

Handling alignment between visual and textual modalities

Future Work

Fine-tuning on domain-specific datasets

Integrating reinforcement learning for improved caption quality

Exploring multilingual caption generation

Contact
Jagadeesh Maddi
B.Tech CSE (AI), Bennett University
