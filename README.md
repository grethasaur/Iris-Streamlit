# Iris Flower Classification App

This simple web application predicts the species of an iris flower based on its features using a pre-trained machine learning model.

**App link here:** <https://iris-app-etmuptmn94pvi2usmsvb9x.streamlit.app/>

## Overview

The app is built using Python and Streamlit, utilizing a machine learning model trained on the famous Iris dataset. Users interact with the app by adjusting sliders corresponding to features such as sepal length, sepal width, petal length, and petal width. The model then predicts the species of the iris flower based on these inputs.

## Iris Dataset Background

The Iris dataset is a classic dataset used in machine learning and statistics. It consists of 150 samples of iris flowers, each with four features: sepal length, sepal width, petal length, and petal width. The goal is to classify the iris flowers into one of three species: Setosa, Versicolor, or Virginica based on these features.

## App Structure

- **`app.py`:** Contains the main code for the Streamlit web application.
- **`model.pkl`:** Pre-trained machine learning model serialized using pickle.
- **`requirements.txt`:** File listing all the dependencies for easy installation.

## Libraries Used

- **Streamlit:** Used for creating the web interface and handling user input.
- **Pandas:** For handling data and input processing.
- **NumPy:** Essential for efficient numerical computations and array handling.
- **Scikit-learn:** Used for the pre-trained machine learning model.

## License

This project is licensed under the GNU General Public License - see the [LICENSE](LICENSE) file for details.
