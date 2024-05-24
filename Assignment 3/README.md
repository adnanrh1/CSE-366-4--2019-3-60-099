This script outlines a comprehensive approach to building, training, and evaluating two CNN models for image classification. It begins with data preprocessing and augmentation using TensorFlow's `ImageDataGenerator`, enhancing the training set with various transformations.

The script defines two models: a custom CNN and a modified ResNet50. The custom CNN is built from scratch with convolutional, pooling, dense, and dropout layers, and is compiled with the Adam optimizer and categorical crossentropy loss. The ResNet50 model employs transfer learning, adding custom layers to a pre-trained ResNet50 base, and is similarly compiled.

Both models are trained for 10 epochs using augmented image batches, with accuracy and validation accuracy tracked throughout. A plotting function visualizes these metrics, illustrating the models' performance over time. After training, the models are evaluated on the validation set, and their final accuracy scores are printed.

The script effectively demonstrates the process of data augmentation, custom model building, and transfer learning, providing insights into the performance of each approach in a deep learning workflow.
