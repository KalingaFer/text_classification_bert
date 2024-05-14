
### Unzip the dataset
### Open BERT_toxic_Text_classification_model.ipynb
### Change the file path
`df1 = pd.read_csv('drive/MyDrive/Bert_learn/train.csv',encoding='utf8')`

### toxic_classification_BERTandBiLSTM_models notebook
Toxicity comment classification by using BERT and BiLSTM model
train more epochs to get good accuracy
`hist = model.fit([X_train_id, X_train_mask], 
                 y_train, 
                 validation_data=([X_test_id, X_test_mask], y_test),
                 epochs=1,
                 batch_size=64)`

