# audio-deepfake
A PyTorch implementation of Dessa's audio DeepFake detection model.

Audio deepfakes are a new class of misinformation superspreaders and are often used to defraud people and companies. Compared to visual deepfakes, these are significantly harder to detect due to limited training data as well as the significant amount of preprocessing that must be done on the data to extract meaningful temporal features. This model is trained on the AVS spoof dataset and reported 75% validation accuracy.
