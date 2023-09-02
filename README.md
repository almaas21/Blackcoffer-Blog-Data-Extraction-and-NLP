# Blackcoffer-Blog-Data-Extraction-and-NLP
The objective of this assignment is to extract textual data articles from the given URL and perform text analysis to compute variables that are mentioned in Objective.doc. An Input.xlsx contains columns URL_ID and URL. Extract the article from the rows through URL_ID and save the extracted article in a text file with URL_ID as its file name. 

Instructions
Locate the BlackCoffer Assigment.py file in the provided directory. Execute the script using a Python interpreter. This can typically be done by opening a command-line interface or terminal, navigating to the directory containing the script, and entering the command: python BlackCoffer Assigment.py

Once the script completes its execution, a folder named “extracted_articles” will be created. This folder will contain articles extracted from URL_ID. Each article will be saved with a name corresponding to its URL_ID. It is worth noting that two articles don’t exist, namely 11668 and 17671.4, resulted in Error 404, so their respective files will be empty.

Following the extraction process, a folder named “processed_articles” will be generated. Inside this folder, you'll find text files named after their respective URL_IDs. These text files will contain dictionaries. Each dictionary will consist of keys that correspond to the columns in Output.xlsx, and their associated values.

Ensure that the Output Data Structure.xlsx file is present in the same directory as the script and input files. The output file will be appended with values extracted from the dictionaries in the processed_articles folder.

The Output Data Structure.xlsx file is the desired output of the script. It will be updated with the values obtained from the dictionaries in the processed_articles folder. Please ensure that this file is available in the working directory alongside the Input.xlsx file.
