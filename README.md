# DS-Unit-4-Sprint-1-NLP

2020.01.22 Submission 4 - MLP Classifier with Spacy embeddings
Multi-Layer Perceptron Classifier, test data: 0.7444987775061125
MLPClassifier(solver='adam', 
                alpha=1e-5,
                hidden_layer_sizes=(16, 2),
                random_state=1)

2020.01.22 Submission 3 - Random Forest Classifier with SpaCy embeddings, not parameter tuning
    random forest classifier, test data: 0.7444987775061125

2020.01.22 Submission 2 - TFIDF, Linear SVC, Random Forest Classifier
    grid search best score, test data: 0.7212713936430318
    grid search best parameters:
                                {'clf__max_depth': 20,
                                'svd__n_components': 100,
                                'vect__max_df': 0.25,
                                'vect__min_df': 5}


2020.01.22 Submission 1 - TFIDF, Linear SVC, more tuning
    grid search best score, test data: 0.7469437652811736
    grid search best parameters:
                                {'clf__C': 0.5,
                                'clf__penalty': 'l2',
                                'vect__max_df': 0.75,
                                'vect__max_features': 20000,
                                'vect__min_df': 2}


2020.01.19 Submission 0 - TFIDF(max/min df,) Linear SVC
    grid search best score, test data: 0.7531416983950807
    grid search best parameters:
                                { vect__max_df': 0.75,
                                'vect__max_features': 20000,
                                'vect__min_df': 2}

Baseline = majority class % = 0.704918