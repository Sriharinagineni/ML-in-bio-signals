Go ahead and open the project folder in Visual Studio Code, then proceed to load audio_feature.ipynb. Jupyter extension needs to be installed for running notebook cells seamlessly.
First cell would contain the data loading feature and the data extraction with voice_features_with_speaker_gender_labels.csv as output file. 
Then, the output CSV would be separated into training_data.csv and testing_data.csv. Run cell for PCA transformation.
Now save the produced PCA transformed complete data as train_pca.csv and test_pca.csv.
Then run the SVM training cell with this fitted model into train data.
SVM must be tuned through hyperparameter optimization and cross-validated to attain the best. 
Prediction by SVM should be saved in the file called predict_svm.csv and then necessary accuracy metrics should be reviewed.
The Gaussian Mixture Model will then be trained using the training data. 
Evaluate how the model performs against GMM and check the log-likelihood metrics or otherwise based on accuracy. 
Conduct t-tests for either features significance or their comparison in model performance.
Finally, check the results which include accuracy scores, cross-validation metrics, and t-test outputs.

