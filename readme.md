Comparison of Traditional ML models and LSTM model

Combined Data.csv 
Consists of more than 90000 statements mapped to 11 different emotions(status)

.env file to use Gemini API key safely (added to Github for project submission purposes)

1. Crosscheck the data file path so that it can use Combined Data.csv correctly

2. Using Linear_SVC_model_implemtentation_and_testing.ipynb 
    i. It has initial data cleaning, visualization parts and defining status(emotion) classification and sentiment analysis functions.
    ii. A chatbot function to run a chatbot in terminal output cell which holds conversation history and you can type your messages from the ide search bar or terminal consoles.
    iii. Gradio interface for a better UI which answers in UI with the predicted sentiment and status mentioned in the answer

Using RandomForestClassifier_testing.ipynb
Testing accuracies using RandomForestClassifier to compare with other models.

Sequential_model_LSTM_test.ipynb
    i. Crosscheck the file path and remove the r if necessary.
    ii. Embedding Layer: Embedding layer for text input.
        First LSTM Layer: LSTM layer with output returned at each timestep.
        Dropout Layer: Dropout for regularization.
        Second LSTM Layer: LSTM layer.
        Dense Layer: Fully connected layer with ReLU activation.
        Dropout Layer: Dropout for regularization.
        Output Layer: Output layer with softmax activation.
    iii. Running epochs and using early stopping to avoid overfitting.