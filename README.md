# SketchSense — Drawing Classifier 🖍️

SketchSense is a machine-learning project that classifies drawings into predefined
categories. It is designed as an educational project for exploring and comparing
several classification algorithms.

## Classification algorithms

- Linear SVC
- K-Nearest Neighbors
- Logistic Regression
- Decision Tree
- Random Forest
- Gaussian Naive Bayes
- Multi-layer Perceptron

## Features

- A Tkinter-based interface for collecting and classifying drawings
- Train new classifiers or load a previously saved model
- Scikit-learn-based experimentation with multiple classifiers

## Installation

1. Clone this repository:

   ```bash
   git clone https://github.com/Pratham11520/-Project-.git
   cd -Project-
   ```

2. Create and activate a virtual environment (recommended).

3. Install the dependencies:

   ```bash
   pip install -r requirements.txt
   ```

## Usage

Run the classifier GUI from the repository root:

```bash
python main.py
```

### Typical workflow

1. Enter a project name and three class names when prompted.
2. Draw an example and click the button for its matching class. Repeat this for
   every class so the model has training data.
3. Click **Train Model** after collecting at least one example per class.
4. Draw a new example and click **Predict** to see the model's category.
5. Use **Save Model** or **Save Everything** to keep your work, and **Load
   Model** to reuse a saved classifier.

Use **Change Model** to cycle through the available classifiers and compare how
they perform on the same drawing data.
