# Text Summarization Using BART

## Aim
To perform abstractive text summarization on a given text data using the BART model.

## Data Description
The data used is from the curation base repository, which has a collection of 40,000 professionally written summaries of news articles, with links to the articles themselves. The data is cloned from GitHub. Then data is downloaded in the form of a CSV file and has the following features:
* Article titles – title for the texts
* Summaries – summary for each text
* URLs – the URL links
* Dates
* Article conte

## Tech Stack
1. Language: Python
2. Libraries: pandas, seaborn, matplotlib, sklearn, transformers ➢ Environment – Google Colab


## Approach
1. Import the dataset from the dataset library and load a subset of the dataset.(To get an overview of the summarised data)
2. Clone the repository.
3. Download the article titles, summaries, URLs, and dates (a CSV file)
4. Createanewenvironment,install the requirements and scrape the data.
5. Change the runtime to GPU.
6. Import the required packages and libraries.
7. Create a class function for the dataset.
8. Create a class function for the BART data loader.
9. Create an abstractives ummarization model class function.
10. Create a BART tokenizer
11. Define the data loader
12. Read and prepare the data.
13. Perform train test split.
14. Create the main class that runs the ‘BARTForConditionalGeneration’ model and tokenizer as an input.
15. Define the trainer class and then fit the model.
16. Perform the BART summarization using the pre-trained model. 17.Understand the concept behind the BART evaluation metric – Rouge.
