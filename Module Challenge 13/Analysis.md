# 🚀 Venture Funding with Deep Learning

Our journey began at Alphabet Soup, a venture capital firm where we were tasked with creating a model that predicts whether applicants will be successful if funded by Alphabet Soup. The business team provided us with a CSV containing more than 34,000 organizations that have received funding from Alphabet Soup over the years. Our mission was to use this data to create a binary classifier model that will predict whether an applicant will become a successful business. 

## 🔧 Data Preparation

Our first task was to prepare the data for use on a neural network model. We used Pandas and scikit-learn’s `StandardScaler()` to preprocess the dataset. We read the `applicants_data.csv` file into a Pandas DataFrame, dropped irrelevant columns, encoded categorical variables using `OneHotEncoder`, and scaled the features data. We then split the features and target sets into training and testing datasets.

## 🧠 Model Compilation and Evaluation

Next, we used TensorFlow to design a binary classification deep neural network model. The model was designed to use the dataset’s features to predict whether an Alphabet Soup-funded startup will be successful. We compiled and fit the model using the `binary_crossentropy` loss function, the `adam` optimizer, and the `accuracy` evaluation metric. We then evaluated the model using the test data to determine the model’s loss and accuracy.

## 🎛️ Model Optimization

We made two attempts to optimize the model to improve the model's accuracy. We tried adjusting the input data, adding more neurons to a hidden layer, adding more hidden layers, using different activation functions for the hidden layers, and adjusting the number of epochs in the training regimen. Despite these efforts, we didn't achieve a significant improvement in accuracy.

## 📊 Results

We evaluated the model loss and accuracy metrics using the evaluate method and the test data. The results were displayed for each model, and we compared the results of the original model with the two optimized models.

## 📝 Conclusion

The process of predicting the success of venture-funded startups using deep learning is a complex task. It involves careful data preparation, model creation and optimization, and result evaluation. Despite the challenges, this project provided valuable insights into the potential of deep learning in venture funding decisions.

## 🔗 [Link to the Detailed Analysis](https://drive.google.com/file/d/1IfCOwNmGCpLWl9WToz6mRR2ZORtZ8OvG/view?usp=sharing)
# 🎉 End of Analysis 🎉
