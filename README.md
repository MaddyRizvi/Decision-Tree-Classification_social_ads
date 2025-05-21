# Decision Tree Classification on Social Network Ads Dataset

This project demonstrates how to apply the **Decision Tree Classification** algorithm on the Social Network Ads dataset using Python and scikit-learn. It includes data preprocessing, model training, prediction, evaluation, and visualization of decision boundaries for both training and test sets. **This project can be easily adapted to work with other datasets** containing different or additional independent variables.

## 📁 Dataset

The dataset used is `Social_Network_Ads.csv`, which contains information such as:

- Age
- Estimated Salary
- Purchased (Target variable)

## 🔧 Technologies Used

- Python 3.x
- NumPy
- Pandas
- Matplotlib
- scikit-learn

## 🚀 Features

- Data preprocessing (splitting and scaling)
- Model training using Decision Tree Classifier
- Evaluation using confusion matrix and accuracy score
- Visualization of decision boundaries for both training and test sets

## 🧠 Algorithm Used

The Decision Tree Classifier is trained using the 'entropy' criterion (information gain).

## 📊 Results

The model's performance is evaluated using both visual and quantitative methods:

### ✅ Decision Boundary Visualizations

**Training Set:**

![Training Set](https://github.com/user-attachments/assets/76fa441c-a689-4c70-a1e4-e010bb11d7cc)

**Test Set:**

![Test Set](https://github.com/user-attachments/assets/0ae07154-283e-4961-b3a3-cef154646437)

### ✅ Evaluation Metrics

- Confusion Matrix
- Accuracy Score

These metrics help assess how well the Decision Tree Classifier performs on unseen data.


## 🛠️ Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/MaddyRizvi/Decision_Tree_Classification-social-ads.git
   cd decision-tree-social-ads
   ```

2. Install dependencies:
   ```bash
   pip install numpy pandas matplotlib scikit-learn
   ```

3. Run the script:
   ```bash
   python decision_tree_classification.py
   ```

## 📂 Project Structure

```
decision-tree-social-ads/
│
├── decision_tree_classification.py   # Main Python script
├── Social_Network_Ads.csv        # Dataset file
├── README.md                     # Project documentation
└── CONTRIBUTING.md               # Open contributions guidelines
```

## 🤝 Contributing

Want to improve the project or add new features? Please read the [CONTRIBUTING.md](CONTRIBUTING.md) file for details on how to get started.

## 📄 License

This project is open-source and available under the [MIT License](LICENSE).
