# IR-Ranked-Retrieval
This IR system is going to rank the top k documents of captions dataset

Ranked Retrieval on Conceptual Captions Dataset

Dataset
The Data is obtained from google conceptual captions which is used for image captioning. 
Recent Experiment Image2Tweet used this dataset.
The Dataset is attached in the folder "code".
The Dataset is named "ConceptualCaptionsDataset.xlsx"
This is a large dataset and we considered 30,000 documents of captions with their Hindi Translations
that will be retrieved with Index along with the Retrieved Caption Documents.

How to run the retrieval system:
Step 1: Go to https://colab.research.google.com/?utm_source=scs-index
Step 2: Go to Upload and select the "MutliRankRetrieval.ipynb" file in the "code" folder.
Step 3: Once the code is uploaded, In the left menu bar select files and upload the datset.
Step 4: Either leave the default path that works or copy the path of dataset in the 
df = pd.read_excel('DATASET PATH SHOULD BE HERE',header = None)
Step 5: Once the Dataset is loaded, the code gives you top K retrieved documents along with their hindi translations 
using multiple term weighting methods, and similarity evaluation methods.
