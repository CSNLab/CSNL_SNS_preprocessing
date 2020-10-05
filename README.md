# SNS2_preprocessing

This repo contains helper functions for preprocessing social network datasets from the dorm study at Time 1 (SNS1) as well as all steps for preprocessing the social network raw dataset obtained during time 2 (SNS2).

Helper functions from Time 1:
- Edgelist Generator from a wide dataset
- Transcriptions text file generator from Excel dataset
- Filter script to filter dataset from csv file containing long ID string from Firebase output
- Name normilizer that anonymizes names from a CSV

Final outputs contains the following CSVs in an anonymized format for SNS2:
- Edgelist of all ego-alter pairs with boolean identifying name generator alter was entered
- Likert and loneliness ratings from time 2
- Third party relationships

NOTE: To protect the anonymity of study participants, two methods have been removed and all output has been cleared. Raw CSV datasets cannot be provided.
