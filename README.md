# Image_classification



#### Overview:
This data science and machine learning project focuses on classifying personalities among seven prominent individuals: Elon Musk, Kareena Kapoor, Larry Fink, Lionel Messi, Dwayne Johnson, Sam Altman, and Tom Cruise. The project employs a combination of image processing, feature extraction, and machine learning techniques to identify and classify these personalities.

#### Project Structure:
UI: Contains the code for the user interface, facilitating easy interaction with the model.
Server: Python Flask server handling HTTP requests and responses.
Model: Jupyter notebooks for building and training the machine learning model.
Google_Image_Scrapping: Code to scrape images from Google for expanding the dataset.
Images_Dataset: Dataset used for model training.
Technologies Used:
Python: Core programming language for development.
Numpy and OpenCV: Used for data cleaning and image processing.
Matplotlib & Seaborn: Utilized for data visualization.
Scikit-learn (Sklearn): Employed for model building and evaluation.
Jupyter Notebook, Visual Studio Code, and PyCharm: Integrated Development Environments (IDEs) for coding.
Python Flask: Framework for building the HTTP server.
HTML/CSS/Javascript: Technologies used for designing the user interface.
#### Model Building Process:
Import Libraries: Essential libraries, including Numpy, PyWavelets, OpenCV, and Scikit-learn, are imported.

Wavelet Transformation Function: A function (w2d) is defined for wavelet transformation, a technique used for feature extraction.

Image Preprocessing and Feature Extraction: Images of celebrities are preprocessed and features are extracted, combining raw and wavelet-transformed images.

Data Preparation for Model Training: Data is organized and prepared for training the machine learning model.

Splitting the Dataset: The dataset is split into training and testing sets.

#### Model Training and Evaluation:

Support Vector Machine (SVM): Utilizing a pipeline with hyperparameter tuning using grid search.
Random Forest: Employing a pipeline with hyperparameter tuning.
Logistic Regression: Employing a pipeline with hyperparameter tuning.
Model Evaluation and Comparison: Models are evaluated on the test set, and their accuracy is compared.

Confusion Matrix and Classification Report:  SVM model give  80% accuracy.
