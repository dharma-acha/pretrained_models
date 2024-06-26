## Pretrained models VGG 16 ResNet DenseNet

### Overview
In this project, we apply transfer learning using pre-trained models to classify images from the Food-11 dataset. Transfer learning leverages the knowledge learned by a pre-trained model on a large dataset and adapts it to the Food-11 dataset, which contains images of food in 11 categories.

### Steps
#### Data Preparation:

* Load and preprocess the Food-11 dataset.
* Normalize images and split the dataset into training, validation, and testing sets.
#### Model Selection:

* Utilize three pre-trained models from PyTorch: ResNet, VGG, and DenseNet.
* Replace the final layer of each pre-trained model to match the number of classes in the Food-11 dataset.
#### Parameter Tuning:

* Fine-tune the parameters of each model.
* Experiment with different learning rates, batch sizes, and epochs to optimize performance.
#### Training and Evaluation:

* Train each model on the Food-11 dataset.
* Evaluate the performance of each model using metrics such as accuracy, precision, recall, and F1 score.
* Compare the results of the different pre-trained models.

### Technologies Used
1. Python
2. PyTorch
3. Matplotlib
4. NumPy

### Contact

If you have any questions or comments, feel free to contact me on [Email](mailto:achadharma333@gmail.com)

