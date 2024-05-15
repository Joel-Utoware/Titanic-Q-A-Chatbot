# Titanic Q&A Chatbot 
Made as my capstone project during my time at **Digital Futures**. My goal was to create a chatbot that reads the text from the [Titanic](https://en.wikipedia.org/wiki/Titanic) wikipedia page and outputs answers to the user's questions. The answers are given  depending on the f1 score of the models response, meaning a higher score means that a sentence starter used in the answer feels like the chatbot is confident. On the othe hand a very low score and the chatbot will say it could not get an answer. This project allowed me to test what I learnt about Natural Language processing.

## Method
- Transfer learning ( fine tuning already made models to the data you want to use) was used to complete this project.
- The models were sourced from [Hugging face](https://huggingface.co):
- The fastest model was chosen for the chatbot
