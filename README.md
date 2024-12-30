# Tokenization-Stemming-and-POS-Tagging-with-Natural-Language-Processing-Techniques
This repository focuses on essential text preprocessing steps critical for natural language processing (NLP) tasks. It provides a comprehensive exploration of tokenization, stemming, and parts-of-speech (POS) tagging using Python-based NLP libraries. These techniques enable efficient text analysis and lay the foundation for advanced NLP workflows.



### Key Components
1. **Tokenization**:
   **The sentence**: Textual information in the world can be broadly categorized into two main types: facts and opinions. Facts are objective expressions about entities, events, and their properties. Opinions are usually subjective expressions that describe people’s sentiments, appraisals, or feelings toward entities, events, and their properties. 
   - Implementation of multiple tokenization methods, including:
     - **Split Function**: A straightforward approach using whitespace as delimiters.
     - <img width="769" alt="Screenshot 2024-12-30 at 11 49 40 AM" src="https://github.com/user-attachments/assets/fd25591a-6cd3-4bd8-a3cc-a7c23eaeaa02" />
     
     - **Regular Expressions**: Enhanced tokenization by defining patterns for word boundaries.
     - <img width="759" alt="Screenshot 2024-12-30 at 11 50 13 AM" src="https://github.com/user-attachments/assets/89c1b830-ce9d-48ad-adbf-a39b91f736c6" />
     <img width="792" alt="Screenshot 2024-12-30 at 11 51 18 AM" src="https://github.com/user-attachments/assets/a66cba72-f799-4324-b9f7-766c9902a5a2" />


     - **NLTK's Word Tokenizer**: A linguistically informed approach that accounts for punctuation and contractions.
     - <img width="762" alt="Screenshot 2024-12-30 at 11 51 46 AM" src="https://github.com/user-attachments/assets/5e7d9ff1-bb3a-4745-8d7a-8beb4b6754bd" />

3. **Stop Word and Punctuation Removal**:
   - Demonstrates the removal of low-value words (e.g., "the", "and") and punctuation using NLTK’s stop word corpus and custom regex functions.
   - Highlights the impact of stop word filtering on text analysis tasks such as sentiment analysis and topic modeling.
<img width="760" alt="Screenshot 2024-12-30 at 11 52 30 AM" src="https://github.com/user-attachments/assets/23256a25-3f4e-42d0-9808-320d67dbf186" />
<img width="801" alt="Screenshot 2024-12-30 at 11 53 28 AM" src="https://github.com/user-attachments/assets/c1d1cd05-394c-4c6a-879d-abc5b877a686" />
<img width="772" alt="Screenshot 2024-12-30 at 11 53 50 AM" src="https://github.com/user-attachments/assets/273cc34a-e519-492a-9cb1-0661c971e476" />

4. **Stemming**:
   - Implementation of various stemming techniques to reduce words to their root forms:
     - **Regular Expression Stemmer**: Uses pattern matching to strip common suffixes.
     - <img width="759" alt="Screenshot 2024-12-30 at 11 55 17 AM" src="https://github.com/user-attachments/assets/0f738f92-41c0-449c-ad56-6fd3fda8ebbd" />

     - **Porter Stemmer**: A rule-based linguistic approach for precise root word identification.
     - <img width="786" alt="Screenshot 2024-12-30 at 11 55 30 AM" src="https://github.com/user-attachments/assets/5a0d4e62-9280-4249-8623-a20af0e76bcc" />

     - **Lancaster Stemmer**: An aggressive algorithm for shorter stems.
     - <img width="764" alt="Screenshot 2024-12-30 at 11 55 43 AM" src="https://github.com/user-attachments/assets/a8c06196-79f2-4589-8821-cedcb0d7e9c6" />


5. **Parts-of-Speech (POS) Tagging**:
6. **The sentence**: The big black dog barked at the white cat and chased away.
   - Comparison of different POS tagging methods:
     - **NLTK**: A robust tagger based on the Penn Treebank tag set for detailed grammatical categorization.
     - <img width="767" alt="Screenshot 2024-12-30 at 11 56 55 AM" src="https://github.com/user-attachments/assets/ffcbcfc9-1a37-4b5a-9025-2beda8e1d2fc" />

     - **TextBlob**: A simpler yet effective tagger for basic analysis.
     - <img width="753" alt="Screenshot 2024-12-30 at 11 57 08 AM" src="https://github.com/user-attachments/assets/6aba2432-b770-46d8-96d6-e4f6e25a19ac" />

     - **Regular Expression Tagger**: A lightweight approach relying on predefined patterns.
     - <img width="758" alt="Screenshot 2024-12-30 at 11 57 21 AM" src="https://github.com/user-attachments/assets/736303e6-e402-4803-b7e7-df9519fafe57" />

7. **Syntactic Analysis**:
   - Parse tree generation using NLTK and context-free grammars (CFG) to visualize and analyze sentence structure.
   - Illustrates the hierarchical syntactic relationships between words in a sentence.
   - <img width="758" alt="Screenshot 2024-12-30 at 11 58 04 AM" src="https://github.com/user-attachments/assets/f1f9d7d5-67e5-4182-aedf-7bb664051ce4" />


### Value Proposition
By combining these text preprocessing techniques, this module establishes a strong foundation for NLP tasks like sentiment analysis, text classification, and semantic understanding. The insights provided by tokenization, stemming, and POS tagging empower machine learning models to work with cleaner, more structured text data.

### Use Cases
- Preprocessing raw text for sentiment analysis and predictive modeling.
- Enhancing information retrieval systems with better word matching and contextual understanding.
- Building foundational tools for complex NLP tasks like named entity recognition (NER) or text summarization.

