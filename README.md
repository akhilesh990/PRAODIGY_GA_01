# PRAODIGY_GA_01
GPT-2 Fine-Tuning for Text Generation
Features

Fine-tunes GPT-2 using Trainer API

Supports custom text datasets

Saves fine-tuned model checkpoints

Uses accelerate for optimized training

Installation

Ensure you have Python 3.8+ installed. Then, install the required dependencies:

pip install -r requirements.txt

Dataset

Place your training data in a text file named custom_data.txt in the root directory. The file should contain plain text, with each line representing a training sample.

Training the Model

Run the training script:

python train.py

Model Checkpoints

The fine-tuned model is saved in ./gpt2-finetuned/.

Dependencies

See requirements.txt for necessary packages.
