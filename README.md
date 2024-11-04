**MULTI-CLASS GENRE CLASSIFICATION**
Automatic genre classification has long captivated researchers in Music Information Retrieval (MIR), seeking techniques to unravel the complex tapestry of musical diversity. We aim to delve into the intricacies of audio feature extraction and music genre classification by utilizing Spotify's rich array of audio features and a diverse dataset.

Objective1 : is it possible to classify songs into genres with just audio features
Objective2 : what can these audio features tell us about the distinctions between genre

KEY STEPS 
1. Outlier Detection, removal and Correlation Analysis
2. Data Preparation
3. Modeling - Decision Tree, Random Forest, and XGBoost
4. Model Evaluation
5. Variable Importance Analysis

Results: MODEL ACCURACY
RANDOM_FOREST 70%
DECISION_TREE 52%
XGBOOST 70%

Inference:
- The feature"acousticness" seems to have the higher importance for the decision_tree model, while it has relatively lower importance for the random_forest and xgboost models.
- The feature "energy" appears to be moderately important for the random_forest and xgboost models but has lower importance for the decision_tree model.

Genre Accuracy:
- Random Forest has the highest accuracy of 78.5% in classifying ‘edm’ genre, which is a bit higher compared to decision tree and xgboost models.
- Xgboost model has the highest accuracy among all models of 50.3% in classifying ‘pop’ genre.

Future:
• Investigate more advanced ensemble techniques by using stacking or blending strategies to further improve classification accuracy.
• Leveraging pre-trained models or transfer learning approaches
