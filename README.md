# eDNA_Classification
Environmental DNA, also known as eDNA, is a mitochondrial DNA that is released
by the organism in the environment and can be collected through samples of water, soil,
sediments, leftovers, and e.t.c. Some of the applications of eDNA classification are to find
invasive species, monitor pollution, research taxonomy, etc. In this project, I will be using
supervised machine learning techniques to classify eDNA with its respective families. I will
also use an unsupervised machine learning technique to group sequences based on their
similarities.

### About the Dataset 
The dataset I used for this project was gathered from the MitoFish database, a
comprehensive and standardized fish mitochondrial genome database. The data extracted
from the database is in a .tsv file and has well-structured columns. This helped easily convert
the dataset into a pandas dataframe for further data analysis and classification. The only
column I am interested in for this project is the sequence column and the family that
represents the sequence.
