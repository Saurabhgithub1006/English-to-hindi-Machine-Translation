# English-to-hindi-Machine-Translation

![Image](https://github.com/Saurabhgithub1006/English-to-hindi-Machine-Translation/blob/main/Images/Hello.jpeg?raw=true)

 [Dataset Link : https://www.cfilt.iitb.ac.in/iitb_parallel/]


## Description: 
The IIT Bombay English-Hindi corpus contains parallel corpus for English-Hindi as well as monolingual Hindi corpus collected from a variety of existing sources and corpora developed at the Center for Indian Language Technology, IIT Bombay over the years. This page describes the corpus. This corpus has been used at the Workshop on Asian Language Translation Shared Task since 2016 the Hindi-to-English and English-to-Hindi languages pairs and as a pivot language pair for the Hindi-to-Japanese and Japanese-to-Hindi language pairs.




![Encoder -Decoder](https://github.com/Saurabhgithub1006/English-to-hindi-Machine-Translation/blob/main/Images/1_R-Ul_DUk74cj79bPr5UalQ.gif?raw=true)






## Problem Statement: 
You are provided with a large dataset of language pairs, parallelly in English and Hindi: you have to perform a step-by-step NLP approach to translate English to Hindi after splitting the dataset into train-test-validation sets.



![Image](https://github.com/Saurabhgithub1006/English-to-hindi-Machine-Translation/blob/main/Images/Screenshot%20(309).png?raw=true)




## Project Overview
This project involves the translation of English sentences to Hindi using the IIT Bombay English-Hindi corpus.

# Dataset
* Source: IIT Bombay English-Hindi corpus.
* Description: Contains parallel corpora for English-Hindi and monolingual Hindi corpus collected from a variety of existing sources and corpora developed at the Center for Indian Language Technology, IIT Bombay.
* Usage: This corpus has been used at the Workshop on Asian Language Translation Shared Task since 2016 for the Hindi-to-English and English-to-Hindi language pairs and as a pivot language pair for the Hindi-to-Japanese and Japanese-to-Hindi language pairs.
# Objective
To perform a step-by-step NLP approach to translate English to Hindi after splitting the dataset into train, test, and validation sets.

# Approach
## Data Splitting:

Split the dataset into training, testing, and validation sets.
## Model Development:

Developed a Neural Machine Translation (NMT) model to translate English sentences to Hindi sentences.
Utilized an Encoder-Decoder LSTM Model with seq2seq architecture to solve many-to-many sequence problems, where both inputs and outputs are divided over multiple time steps.
Training:

Trained the model using the training dataset.
## Evaluation:

Evaluated the model performance using the BLEU score metric.
Results
BLEU Score: Achieved a BLEU score of 37 for the translated output.
# Conclusion
The developed NMT model effectively translates English sentences to Hindi, demonstrating a significant performance with a BLEU score of 37.


