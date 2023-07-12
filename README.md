# Emoji-Sentiment-prediction-using-LSTM
📢 Attention, everyone! 🎉🎓

🔍 I'm thrilled to share an exciting student project that focuses on sentiment analysis using LSTM (Long Short-Term Memory), a powerful neural network architecture for natural language processing (NLP). 💬🤖

📊 In this project, I embarked on a journey to understand and interpret the sentiments expressed in text data. By leveraging LSTM, I aimed to build a robust sentiment analysis model capable of categorizing text into positive, negative, or neutral sentiments. 📈✨

📚 To kick things off, I obtained a labeled training dataset from the "train_emoji.csv" file, which was loaded into a pandas DataFrame. After preprocessing the data by removing unnecessary columns, I prepared it for training. 📊🔍

🔗 The next step was to employ the "glove.6B.50d.txt" file, containing pre-trained GloVe word embeddings. These embeddings capture the semantic information of words, which greatly enhances the model's understanding of textual content. 🌐📝

🧠 By utilizing the pre-trained GloVe embeddings, I transformed the text data into embedding vectors using a custom function called "get_embedding_matrix_for_data()". This process involved converting words into numerical representations that LSTM can process effectively. 🔢📈

💻 With the data prepared, I constructed an LSTM-based neural network using the Keras library. The model architecture included LSTM layers, dropout regularization to prevent overfitting, and dense layers for classification. 🏗️🤝

🌟 After compiling the model with appropriate loss and optimization functions, I trained it using the training data and evaluated its performance. I monitored metrics such as accuracy to gauge how well the model learned to classify sentiment. 📊🎯

✨ Once the model was trained and evaluated, I used the "test_emoji.csv" dataset for validation. The text data in the testing dataset underwent the same preprocessing steps, and sentiment predictions were made using the trained LSTM model. 🧪🔍

🔢 The project concluded with an examination of the model's performance on the testing dataset. By comparing the predicted sentiment labels with the ground truth labels, I assessed the accuracy of the sentiment analysis model. 📈🔍

🌐 Throughout this project, I delved into the exciting realms of AI, ML, and NLP, uncovering powerful techniques like LSTM and pre-trained embeddings. The project showcases the potential of deep learning in understanding and interpreting human emotions expressed through text. 💡💬

🌐 Stay tuned for more updates as I continue to unravel the remarkable potential of AI and ML in deciphering the intricacies of human language and sentiment! 📊💡

#StudentProject #SentimentAnalysis #LSTM #NLP #ExcitingDiscoveries
