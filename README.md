# End-to-End-Basic-chatbot

This is the basic chatbot built using Streamlit library for the user interface, the NLTK library for natural language processing, and the Scikit-learn library for machine learning. The chatbot is programmed to respond to various intents such as greetings, goodbyes, asking for help, and answering questions on topics such as budgeting, credit scores, and books.

A list of intents with their associated patterns and responses. It then preprocesses the data by extracting the patterns and tags from the intents list and trains a logistic regression classifier using the Scikit-learn library. The classifier uses the TfidfVectorizer to transform the text data into numerical vectors.

The chatbot function takes an input text, vectorizes it using the TfidfVectorizer, and predicts the intent using the trained classifier. It then returns a random response from the list of responses associated with the predicted intent.

The main function defines the Streamlit user interface. It displays a text input field where the user can type a message and press enter to start the conversation. The user's input is passed to the chatbot function, and the response is displayed in a text area below. If the response is "goodbye" or "bye", the conversation ends.


Preview:

![image](https://user-images.githubusercontent.com/67355055/229363301-a09746da-b165-46c8-9c5c-648b4b11f2b7.png)
![image](https://user-images.githubusercontent.com/67355055/229363335-b206518f-4141-45f7-adaa-ec8007683c01.png)
![image](https://user-images.githubusercontent.com/67355055/229363357-0bed82a2-a85a-4ed3-a13b-5f92c949b9a2.png)

