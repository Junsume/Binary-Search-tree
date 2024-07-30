# A utility function to search a given key in BST
### 1. Raisin Dataset

**Description**: This dataset is used to classify raisin varieties (Kecimen and Besni) grown in Turkey based on various morphological features extracted from their images. Images of the raisins were obtained using Computer Vision Systems (CVS) and underwent preprocessing to extract the features.

**Features**:
- **Area**: The area of the raisin.
- **Perimeter**: The perimeter length of the raisin.
- **Major Axis Length**: The length of the major axis of the raisin.
- **Minor Axis Length**: The length of the minor axis of the raisin.
- **Eccentricity**: The eccentricity of the raisin's shape.
- **Convex Area**: The area of the convex hull surrounding the raisin.
- **Extent**: The ratio of the raisin's area to the area of its bounding box.

**Classes**:
- **Kecimen**: Labelled as 0
- **Besni**: Labelled as 1

**Source**: UCI Machine Learning Repository

**Author**: "Dr. Ilker Ozdemir"

**Link**: 
- https://www.kaggle.com/datasets/nimapourmoradi/raisin-binary-classification


### 2. Sonar Dataset

**Description**: The Sonar dataset contains data collected by bouncing sonar signals off a metal cylinder and rocks at various angles and under various conditions. The goal of this dataset is to classify the objects as either rocks or metal cylinders based on the returned sonar signals. Each instance in the dataset is a collection of 60 numeric values that represent the energy of the sonar signal in different frequency bands. This dataset is often used for binary classification problems to test various machine learning algorithms.

**Features**:
- **Feature 1 to Feature 60**: Each of these features is a numeric value that represents the energy of the sonar signal in a specific frequency band. These values range from 0 to 1 and capture the strength of the returned signal at various frequencies.

**Classes**:
- **Rock**: Labelled as 'R'
- **Mine (Metal Cylinder)**: Labelled as 'M'

**Source**: UCI Machine Learning Repository

**Author**: "Dr. R. Polikar"

**Link**: 
- https://archive.ics.uci.edu/ml/datasets/Connectionist+Bench+(Sonar,+Mines+vs.+Rocks)


### 3. Cats and Dogs Dataset

**Description:**
The Cats and Dogs dataset contains images of cats and dogs, designed for binary classification problems in computer vision. This dataset is especially useful for training models to distinguish between these two types of animals.

**Features:**
- The dataset comprises images of cats and dogs.
- Each image is labeled as either containing a cat or a dog.

**Classes:**
- Cat
- Dog

**Source:**
- Huggingface Datasets
    
**Author:**
- Jeremy Elson, John (JD) Douceur, Jon Howell, Jared Saul.

**Link:**
- https://huggingface.co/datasets/microsoft/cats_vs_dogs.


### 4. SpamAssassin Spam Dataset

**Description:**
The SpamAssassin dataset consists of a collection of email messages used for testing spam filtering systems. The dataset includes both spam and non-spam emails, making it suitable for binary classification tasks where the goal is to distinguish between spam and non-spam emails.

**Features:**
- The dataset contains two columns in the CSV file:
  - **Text Column:** Contains the email data, including headers, subjects, and message content.
  - **Target Column:** Indicates whether the email is classified as spam (1) or not spam (0).

**Classes:**
- Spam
- Not Spam

**Source:**
- The dataset was obtained from the Apache Public Datasets and was cleaned and organized into a CSV format for convenience.

**Author:**
- Apache SpamAssassin Project.

**Link:**
- https://www.kaggle.com/datasets/ganiyuolalekan/spam-assassin-email-classification-dataset                              


### 5. Wine Quality Dataset

**Description:**
The Wine Quality dataset consists of physicochemical tests performed on red and white wines. It is used for classifying wine quality, and can be adapted for binary classification by grouping wines into high and low quality based on a quality threshold.

**Features:**
- The dataset includes features such as:
  - Fixed acidity
  - Volatile acidity
  - Citric acid
  - Residual sugar
  - Chlorides
  - Free sulfur dioxide
  - Total sulfur dioxide
  - Density
  - pH
  - Sulphates
  - Alcohol

**Classes:**
- High Quality
- Low Quality (binary classification can be performed by setting a quality threshold).

**Source:**
- The dataset was collected from wine samples in Portugal and is available from the UCI Machine Learning Repository.

**Author:**
- Paulo Cortez, António C. S. Costa.

**Link:**
- https://archive.ics.uci.edu/ml/datasets/wine+quality                                                                                                                                               
