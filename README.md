# ToolNet-Mechanical-Tool-Classifier-with-PyTorch
In this assignment, I developed a neural network model using PyTorch to classify images of mechanical tools into one of eight categories, such as hammer, wrench, and pliers. The project was designed to reinforce my understanding of neural networks by implementing both a fully connected (ANN) and a convolutional neural network (CNN) and comparing their performance.

I began by constructing a feedforward neural network from scratch, writing the full training loop including data loading, batching, forward pass, loss calculation, and backpropagation using PyTorch. I worked with a dataset of mechanical tool images and applied standard data preprocessing and augmentation techniques to improve generalization.

Throughout the training process, I experimented with various hyperparameters such as learning rate, batch size, number of hidden layers, and epochs. I monitored both training and validation losses over time to evaluate convergence behavior and detect signs of overfitting or underfitting. I also split the dataset into training, validation, and test sets to ensure the model's performance was measured reliably.

After training the ANN, I built a simple CNN to observe how convolutional layers impact feature extraction and classification accuracy. The CNN significantly outperformed the fully connected network, highlighting the effectiveness of localized feature learning for image data.

Overall, this project helped me gain hands-on experience with model training, evaluation, and debugging in PyTorch. It deepened my understanding of core machine learning principles such as generalization, model complexity, and the importance of hyperparameter tuning.
