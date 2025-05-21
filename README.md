# Decision Tree Classification on Social Network Ads Dataset

This project demonstrates how to apply the **Decision Tree Classification** algorithm on the Social Network Ads dataset using Python and scikit-learn. It includes data preprocessing, model training, prediction, evaluation, and visualization of decision boundaries for both training and test sets.

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

Visualizations include clear decision boundaries on:
- Training set
- Test set

The confusion matrix and accuracy score are printed to evaluate the model.

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
   python decision_tree_social_ads.py
   ```

## 📂 Project Structure

```
decision-tree-social-ads/
│
├── decision_tree_social_ads.py   # Main Python script
├── Social_Network_Ads.csv        # Dataset file
├── README.md                     # Project documentation
└── CONTRIBUTING.md               # Open contributions guidelines
```

## 🤝 Contributing

Want to improve the project or add new features? Please read the [CONTRIBUTING.md](CONTRIBUTING.md) file for details on how to get started.

## 📄 License

This project is open-source and available under the [MIT License](LICENSE).
