# AlphaSoup-Mod13
Neural Network Model

# 💼 Venture Funding with Deep Learning: Decoding Startup Success 🚀
![Alt text](Module%20Challenge%2013/Resources/DeepLearningO.png)
Welcome, risk management aficionados! 🕵️‍♀️ You've landed at Alphabet Soup, a venture capital firm that's at the forefront of funding future unicorns. 🦄 Every day, we're flooded with funding applications from promising startups. However, selecting the most viable ones requires some magic — and that's where you come in!

You're tasked to conjure a model that predicts whether applicants will be successful if funded by Alphabet Soup. Sounds exciting, right? The business team has assembled a CSV containing data on more than 34,000 organizations funded over the years. By harnessing this data, and with your deep learning wizardry, you'll create a binary classifier model to predict startup success. 🧠⚙️

## 🚀 Your Mission:
The roadmap for this exciting project is:

- Prepare the data for a neural network model.
- Compile and evaluate a binary classification model using a neural network.
- Optimize the neural network model.

## 🧹 Prepare the Data for a Neural Network Model
Let's roll up our sleeves and prep the data:

- Ingest the **applicants_data.csv** file into a Pandas DataFrame. Eye the DataFrame for categorical variables to encode and potential features and target variables.
- Banish the “EIN” (Employer Identification Number) and “NAME” columns from the DataFrame, they're irrelevant to our mission.
- Encode the dataset’s categorical variables using **OneHotEncoder**, then store the encoded variables in a new DataFrame.
- Enlist the original DataFrame’s numerical variables to the DataFrame with the encoded variables.
  - 📌 Hint: Use the Pandas **concat() **function to bring together the datasets.

- Forge the features **(X)** and target **(y) **datasets from the preprocessed data. The "IS_SUCCESSFUL" column will define the target dataset, with remaining columns shaping the features dataset.
- Split the features and target sets into training and testing datasets.
- Employ scikit-learn's **StandardScaler** to scale the features data.
![Alt text](Module%20Challenge%2013/Resources/DeepLearningX.png)
## 🤖 Compile and Evaluate a Binary Classification Model Using a Neural Network
Time to unleash the power of TensorFlow! Design a binary classification deep neural network model to predict the success of Alphabet Soup-funded startups.

- Create a deep neural network using TensorFlow's Keras. Contemplate the number of inputs before defining the number of layers or neurons on each layer.
    - 📌 Start with a two-layer deep neural network model using the **relu** activation function for both layers.
- Compile and fit the model using the **binary_crossentropy** loss function, the adam optimizer, and the accuracy evaluation metric.
    - 📌 Start with a moderate number of epochs, such as 20, 50, or 100.
- Evaluate the model using the test data to appraise the model’s loss and accuracy.
- Save your model as an HDF5 file named **AlphabetSoup.h5**.

## 🛠️ Optimize the Neural Network Model
Now for the fun part, model optimization! Aim to improve your model's accuracy. Remember, no success is a failure as long as you're learning and iterating.

- Forge at least three new deep neural network models (original + 2 optimization attempts). Strive to improve on your initial model’s predictive accuracy.
    - 📌 You can try adjusting the input data, adding more neurons or hidden layers, using different activation functions, or tweaking the number of epochs.
- Once your models are ready, reveal the accuracy scores for each model and compare the outcomes.
- Save each of your models.
![Alt text](Module%20Challenge%2013/Resources/DeepLearningZ.png)