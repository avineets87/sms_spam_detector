# SMS Spam Classifier

This project demonstrates how to build a simple SMS spam classifier using Python and the scikit-learn library. It utilizes a pipeline with TF-IDF vectorization and Linear Support Vector Classification to predict whether a given text message is spam or not.

## How it works

1. The code imports necessary libraries, including pandas, scikit-learn, and Gradio.
2. It loads a dataset of SMS messages labeled as spam or ham.
3. It defines a function `sms_classification` to train the model using the dataset.
4. It defines a function `sms_prediction` to predict the classification of a new text message.
5. It creates a Gradio interface to allow users to input text messages and see the predictions.

## How to use

1. Make sure you have the required libraries installed: pandas, scikit-learn, and Gradio.
2. Run the notebook cells to load the data, train the model, and launch the Gradio interface.
3. Enter a text message in the input textbox of the Gradio interface.
4. Click the "Submit" button to see the prediction.

## Example usage

Here are some examples of text messages and their predicted classifications:

- "You are a lucky winner of $5000!" - Not spam
- "You won 2 free tickets to the Super Bowl." - Not spam
- "You won 2 free tickets to the Super Bowl text us to claim your prize." - Spam
- "Thanks for registering. Text 4343 to receive free updates on medicare." - Spam


## Contributing

Contributions are welcome! If you find any issues or have suggestions for improvement, please open an issue or submit a pull request.

## License

This project is licensed under the MIT License.
