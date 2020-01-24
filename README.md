# DoCAI

## Abstract:

DoCAI (Document Conversational AI) is an AI-powered document analyzing tool and question-answering chatbot. Given a URL address, document or free text, DoCAI analysis them, answers questions in the context of the document and provides insights like topic distribution of the document using Natural Language Processing. Any user/professional referring a large set of documents on a daily basis can leverage DoCAI to quickly go through and assimilate large amounts of information.

## Question Answer Bot:

The very important component of DoCAI is the Question Answer chatbot. Given a document or context, the bot will answer for the respective question from the document.

For question answering chatbot, I am using Stanford Question Answering Dataset (SQuAD).

### STEP 0:

It is very important to understand the dataset and visualize insights in data before building the model.
Please run the Dataset Analysis notebook to pre-process data and analyze insights from the dataset.

### STEP 1:
The initial step is to convert the SQuAD JSON data into Pandas Dataframe. 

### STEP 2:
The second step is to preprocess text and convert tokens into word embeddings.

### STEP 3:
This is the final step. In this stage, multiple neural machine comprehension question answer models are developed using RNN, LSTM, Transformers and BERT etc.

## Insights generated by DoCAI:

Insights given by DoCAI include topic distribution of documents (https://github.com/kaushikData/Document-Classification-Using-Wikipedia-Data) and sentiment of documents.
