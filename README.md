# Protein_Identification_NLP

### Question/Problem statement:

- I aim to be help the research community in identifying structure and function of a newly discovered protein from the corresponding amino acids sequence using natural language processing. The amino acids sequence is the languge for living cell to understand proteins properties.  
#### Data Description: 
The dataset is a collection of previously discovered protein sequence and each instance represents an identification of one protein or a fragment:
- structureId: instance ID (string).
- classification: the classes of proteins (string).
- residueCount: the number of amino acid residue in the sequence (int).
- sequence: a sequnce of letters corresponding to amino acids - there are 20 distinct AAs making up the sequences with various combinations and length(string).
- data size is (346325, 4)
### Tools: 
- Programs: Python, Jupyter Notebook, KNIME or orange 3.
- Libraries: pandas, keras.preprocessing.text, numpy, sklearn, keras.models, nltk.
- Functions: CountVectorizer, RegexpTokenizer, confusion_matrix, Sequential, Conv1D.
### MVP: 
The goal of this project is to train several classification/clustering models to help the research community in classifying unknown functionality of a protein based on the AA sequence level.
### Source: 
http://www.rcsb.org/pdb/
