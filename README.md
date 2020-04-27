# Named Entity Recognizer
Extracts domain entities, mainly named entities. The major element is a highly accurate Named Entity Recognitizer for real-world data on Sports.  
To give an insight into different NER models, we use FIFA World Cup 2018 as an event to formulate our ideas.  
  
## Dataset:
The compressed dataset alongwith the datasets used for annotating.  
There are 530k Tweets related to FIFA World Cup 2018.  
  
## Annotated Dataset:
The code and required annotated dataset for 530k Tweets on FIFA World Cup 2018. The dataset has each of them POS tagged, and also tagged by NER.  
  
## Accuracy Checker
The code for checking the accuracy of the different NER models.
  
## Approaches:
The codes for several different approaches in Named Entity Recognition.  
### Pure POS Approach
Naive approach of NER to simply POS(Part-Of-Speech) tag and if the tag is NNP, a proper noun, it is tagged as a named entity.  
### NLTK Approach
Directly use NLTK to find named entities.  
The extracted named entities for the dataset is given in compressed form.  
### n-gram Frequency
The n-gram frequency approach extracts the frequent n-grams which are nouns.  
The dataset may be in CSV or text format. The relative path of dataset w.r.t. script should be given in the notebook.  
If not in CSV format, keep the first line as header.  
### Deep Learning
A Machine Learning approach using TensorFlow and modern Deep Learning algorithms.  
NER.ipynb is the complete notebook.  
NER_deep_learning.ipynb only has the deep learning part for quick experimentation and additions.  
