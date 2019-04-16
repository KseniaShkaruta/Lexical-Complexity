# "Impact of ASR on Alzheimer's Disease Detection” - Lexical-Complexity
Code for the expanded version of research paper "Impact of ASR on Alzheimer's Disease Detection: All Errors are Equal, but Deletions are More Equal than Others" Aparna Balagopalan, Ksenia Shkaruta, Jekaterina Novikova -  under submission to Interspeech'19. Expanded version to be submitted to IJCA ’19.

Calculation of a word lexical complexity score for words in manual speech transcripts from the DementiaBank, large publicly accessible dataset of pathological speech. Lexical score dictionary was used from mounicam GitHub account. Score scale is from 1 representing "very simple" to 6 - "very complex".

## Getting Started
Code was written in Python in Jupyter Labs. 
You can install from here (conda is recommended): https://jupyterlab.readthedocs.io/en/stable/getting_started/installation.html

### Prerequisites
You will need the following Python libraries:
- pandas
- json
- statistics
- re

You will need the following files:
- lexicon.tsv -  (https://github.com/mounicam/lexical_simplification/blob/master/word_complexity_lexicon/lexicon.tsv)
