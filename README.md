# boolean-retrieval-system

## Overview

The Boolean Retrieval System is a project designed for processing and retrieving information from Persian books and English movie summaries by queries. The project is divided into three main parts:

1. **Text Preprocessing:**
   - Tokenization
   - Normalization
   - Stemming
   - Stop words removal

2. **Inverted Index Creation:**
   - Utilizes the dictionary-posting concept
   - Orders items based on their repetition in documents

3. **Boolean Retrieval Model:**
   - Implements a matrix to store representation of tokens in documents in binary format
   - Allows users to input queries in a specified format for retrieval
  
## Datasets

The required datasets for this project are available, and you can download them directly in Google Colab. The links to the datasets are provided in the notebook.

## Usage

To use the Boolean Retrieval System, follow these steps:

1. **Data Preprocessing:**
   - Ensure your datasets are in the correct format (Persian books and English movie summaries).
   - Run the preprocessing script to tokenize, normalize, stem, and remove stop words.

2. **Inverted Index Creation:**
   - Run the script to generate the inverted index based on the processed data.

3. **Boolean Retrieval:**
   - Execute the Boolean Retrieval script.
   - Enter queries in the specified format
   - Receive a list of document indices where the tokens appear.

## Query Model

- `dot`: Represents logical AND.
- `!`: Represents logical NOT.
- `+`: Represents logical OR.

### Query Example
`city+!church.taxi+!six`

## Contact Us
We're excited to hear from you! If you have any questions, suggestions, or need assistance, don't hesitate to reach out.
Feel free to contact us via email at:

- noorbakhsha1@gmail.com.

- neg.jaafari@gmail.com
  
We're here to help and would love to hear about your experience using this project.

## Note

This project is implemented in Google Colab


