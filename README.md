# Image-Captioning

Image captioning with visual attention

To accomplish this, we will use an attention-based model, which enables us to see what parts of the image the model focuses on as it generates a caption.

We will downloads the dataset using url, preprocesses and caches a subset of images using Inception V3, trains an encoder-decoder model, and generates captions on new images using the trained model.

In this we will train a model on a relatively small amount of data—the first 30,000 captions for about 20,000 images (because there are multiple captions per image in the dataset).

