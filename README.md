# image-captioning-transduction-models
We *implement* RNNS(vanilla, LSTM) and use them  to train a model that can generate novel captions for images.

We have used Microsoft COCO dataset which has become the standard testbed for image captioning. The dataset consists of 80,000 training images and 40,000 validation images, each annotated with 5 captions written by workers on Amazon Mechanical Turk.

MobileNet is used for image feature extraction. For vanilla RNN and LSTM, we use the pooled CNN feature activation.

Please check notebook file for detailed explanation of overall process.
