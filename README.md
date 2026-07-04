![logo_ironhack_blue 7](https://user-images.githubusercontent.com/23629340/40541063-a07a0a8a-601a-11e8-91b5-2f13e4e6b441.png)

# Project I | Deep Learning: Image Classification with CNN

## Task Description

Students will build a Convolutional Neural Network (CNN) model to classify images from a given dataset into predefined categories/classes.

## Datasets (pick one!)

1. The dataset for this task is the CIFAR-10 dataset, which consists of 60,000 32x32 color images in 10 classes, with 6,000 images per class. You can download the dataset from [here](https://www.cs.toronto.edu/~kriz/cifar.html).
2. The second dataset contains about 28,000 medium quality animal images belonging to 10 categories: dog, cat, horse, spyder, butterfly, chicken, sheep, cow, squirrel, elephant. The link is [here](https://www.kaggle.com/datasets/alessiocorrado99/animals10/data).

## Assessment Components

1. **Data Preprocessing**
   - Data loading and preprocessing (e.g., normalization, resizing, augmentation).
   - Create visualizations of some images, and labels.

2. **Model Architecture**
   - Design a CNN architecture suitable for image classification.
   - Include convolutional layers, pooling layers, and fully connected layers.

3. **Model Training**
   - Train the CNN model using appropriate optimization techniques (e.g., stochastic gradient descent, Adam).
   - Utilize techniques such as early stopping to prevent overfitting.

4. **Model Evaluation**
   - Evaluate the trained model on a separate validation set.
   - Compute and report metrics such as accuracy, precision, recall, and F1-score.
   - Visualize the confusion matrix to understand model performance across different classes.

5. **Transfer Learning**
    - Evaluate the accuracy of your model on a pre-trained models like VGG16/MobileNetV2/ResNet18... (pick one an justify your choice)
    - Perform transfer learning with your chosen pre-trained models i.e., you will probably try a few and choose the best one.

5. **Code Quality**
   - Well-structured and commented code.
   - Proper documentation of functions and processes.
   - Efficient use of libraries and resources.

6. **Report**
   - Write a concise report detailing the approach taken, including:
     - Description of the chosen CNN architecture.
     - Explanation of preprocessing steps.
     - Details of the training process (e.g., learning rate, batch size, number of epochs).
     - Results and analysis of models performance.
     - What is your best model. Why?
     - Insights gained from the experimentation process.
   - Include visualizations and diagrams where necessary.
   
 7. **Model deployment**
     - Model deployment is optional but highly recommended (we'll show you some options)


## Submission Details

- Deadline for submission: end of the week or as communicated by your teaching team.
- Submit a public repo that includes:
  1. Python code files (`*.py`, `ipynb`) containing the model implementation and training process (include all the files that you consider relevant).
  2. A data folder with 5-10 images to test the deployed model/app if hosted somewhere else other than your laptop (strongly recommended! Not a must have)
  3. A Readme file documenting the approach, results, and analysis.
  4. Any additional files necessary for reproducing the results (e.g., requirements.txt).

## Additional Notes

- Students are encourage to experiment with different architectures, hyper-parameters, and optimization techniques.

