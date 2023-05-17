# QUORA QUESTION PREDICTION

### Julian Fiorito | Ben Joens | Yok Ngammankongtangkit | Andrew Pascente | Ken Zheng | Connie Zhu

### 19 May 2023

#### How to Run

Visit [this link](https://drive.google.com/drive/folders/1_U_brwayFKBmD6pEcPf7Jpp7IfBt_Dip) to see all source files for this project. The primary ones to download are `train.csv`, `test.csv`, and `train_clean.csv`. For the data cleaning notebooks, `glove.42B.300d.txt` is required (can be found in the `glove.42B.300d` folder), as well as `LSTM.h5`.

All of these files can be added directly to this working folder, as paths are structured in this format: `./example.csv`.

#### File Descriptions

- Data Cleaning - `DataCleaning.ipynb`
- Demonstration for Presentation - `demo.ipynb`
- Random Forest - `ForestsOnCompetition.ipynb`
- GBT w/ Undersampling - `GBT_balanced.ipynb`
- Gradient Boosting Trees - `GBT.ipynb`
- Human Baseline Measurement - `Human_Baseline.ipynb`
- KNN Classifier - `KNN.ipynb`
- Logistic Regression - `LogisticRegressor.ipynb`
- Naive-Bayes - `NaiveBayes.ipynb`
- Bi-LSTM w/o Preprocessing - `Only_Embedding.ipynb`
- SVM Classifier w/ Undersampling - `SVM_balanced.ipynb`
- SVM Classifier - `SVM.ipynb`
- Bi-LSTM w/ Tokenization - `Word_Embeddings.ipynb`

Note: Bi-LSTM will produce differnet results everytime the program runs depending on the batch it generated.
