# Mushroom Edibility Project

## National University ANA500

## Elijah C Walker

## Prof. E Rodriguez

This is a four part data science project using Python (Jupyter Notebook), Pandas, Numpy, Matplotlib, Scikit-Learn, and Tensorflow intended to define the characteristics most definitive of mushrooms that are either poisonous or edible. Using machine learning algorithms, predictive models are made to define which characteristics are the greatest indicators of the mushrooms edibility. As the other parts of the project are created, this repo and README.md file will grow to contain further information and charts.

The dataset can be found here:
https://www.kaggle.com/datasets/uciml/mushroom-classification

## Micro-Project 1

Step 1: Acquire

-   Find a data analytics problem and supporting dataset
-   Import data and libraries
-   Outline an approach for analysis
-   Define the null and alternative hypothesis
-   Develop a flowchart to support the approach
-   Pseudocode

Step 2: Prepare

-   Perform exploratory data analysis
-   Preprocess data as needed
-   Gain an understanding of the data
-   Manipulate data into a state for algorithms

## Micro-Project 2

Step 3: Analyze and Visualize

-   Implement algorithms (Naive Bayes and Logistic Regression)
-   Create supporting visualizations
-   Determine coefficient weights and other meaningful influencers to the outcome

Step 4: Report

-   Report results

## Micro-Project 3

Step 3 (Revisited):

-   Implement additional algorithms for classification and compare models
-   Check feature importance of the entire dataset

Step 4 (Revisited):

-   Update results section reflective of new models

Step 5: Act

-   Discussion on how results and the analysis are relevant to the data and mycology fields


## Micro-Project 4

In this phase, we delve into the implementation of a neural network for mushroom classification using TensorFlow and Keras. The primary objective is to enhance predictive accuracy and explore advanced techniques. The neural network architecture incorporates multiple hidden layers with dropout regularization to prevent overfitting. Here's an overview of the key steps undertaken:

### Acquire and Prepare Data

- Imported the mushroom dataset.
- Encoded categorical variables using one-hot encoding and label encoding.
- Split the data into training and testing sets.

### Building the Neural Network

- Designed a neural network model using Keras' Sequential API.
- Leveraged ReLU activation for hidden layers and sigmoid activation for the output layer.
- Incorporated dropout layers to improve generalization.

### Model Compilation and Training

- Compiled the model using the Adam optimizer and binary cross-entropy loss.
- Trained the model on the training data and validated its performance using a validation split.

### Evaluation and Visualizations

- Evaluated the model's performance on the test dataset.
- Achieved a test loss of 0.0209 and a test accuracy of 99.57%.

The implementation of this neural network marks the culmination of our micro-project. It underscores the potential of deep learning techniques in significantly enhancing the accuracy of mushroom classification. By integrating dropout regularization, the model effectively mitigates overfitting, showcasing its robustness in generalizing to new, unseen data.

The remarkable test accuracy of 99.57% underscores the success of our model in effectively distinguishing between edible and poisonous mushrooms.
