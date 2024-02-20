# image-caption-generator
This project is an image caption generator using deep learning techniques. It takes an image as input and generates a descriptive caption for it.

# Features:
Generates captions for uploaded images.

Pre-trained model based on ResNet architecture.

Uses vocabulary for generating diverse and fluent captions.

# Files:

after.html: Displays the generated caption after submission.

app.py: Main application logic, handling image upload and caption generation.

base.html: Base template for other HTML files.

contact.html: Contact page information.

file.jpg: Example image. You can replace this with your own images.

generate.html: Form for uploading images and generating captions.

index.html: Main landing page.

mine_model_weights.h5: Pre-trained model weights.

mine_vocab.npy: Vocabulary used for caption generation.

resnet.zip: ResNet pre-trained model archive.

style.css: Stylesheet for the website.


# Getting Started:

1.Clone this repository.

2.Install required dependencies: pip install -r requirements.txt.

3.Download pretrained models: ResNet from https://discuss.pytorch.org/t/trouble-getting-pretrained-resnet152-to-classify-images-properly/20073 (extract to 'resnet' folder).

4.Run the app: python app.py.

5.Upload an image and click "Generate Caption" to see the result.
