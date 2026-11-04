# Veterinary Notes Analyser

This notebook reads a CSV file containing records relating to possible canine lymphoma cases row by row and identifies cases which match the specific case of **"no longer in remission"**, i.e. cases where the patient was judged to be in remission in a previous assessment and, based on new cytology/histology analysis, may be relapsing. The categorisation of each record is done using a locally-hosted LLM. The reason for using an LLM for this analysis is that the veterinary reports that are used to make this judgement are unstructured data, and so require a model capable of reasoning about such data to produce useful output.

Please see `VeterinaryNotesAnalyser.ipynb` for detailed usage instructions, and `ExampleData.csv` for the expected data format and some sample veterinary notes.
