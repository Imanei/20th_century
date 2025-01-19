# Task Overview
This project consists of two main parts:
## 1. Data Cleaning
In the first part, I focused on cleaning the text data to ensure consistency and accuracy. This involved:
1. Standardizing country names: The country names in the text were adjusted to match how they are recognized by the Named Entity Recognition (NER) model used in Spacy. For example, 'United States' was inconsistent, while 'the United States' was reliably detected, so I made this change.
2. Removing unnecessary characters: All extraneous punctuation, numbers, and the word 'the' before country names were removed.
3. Updating the country list: I updated the list of countries to account for outdated country names (such as those for countries that no longer exist) and adjusted the names of countries that had multiple words, like 'China, The People's Republic of' becoming 'China'.
4. Trimming extra spaces: I made sure there were no extra spaces around the country names so they would match exactly with the recognized entities.
   
The cleaned data was then saved and added to the project folder
### Explore the ipynb Notebook part 1:
You can explore the full code in the [Notebook](./Scripts/NLP and Network Analysis Part 1.ipynb)

## 2. NER Processing and Data Export
In the second part of the task, I used the cleaned text data to create a Named Entity Recognition (NER) model and followed these steps:
1. Created an NER object: I used the text file to create a NER object with Spacy, which identifies entities like country names in the text.
2. Split the sentence entities: I split the entities detected by the NER model into individual sentence-level entities.
3. Filtered entities by country list: I filtered the recognized entities, retaining only those that were present in my cleaned country list.
4. Created a relationships dataframe: I organized the relevant country relationships into a structured dataframe.
5. Exported the dataframe: Finally, I saved and exported the dataframe, making it available for further analysis.
   
This part of the task focused on extracting useful insights and exporting the results in a manageable format.
### Explore the ipynb Notebook part 2:
You can explore the full code in the [Notebook](./NLP and Network Analysis Part 2.ipynb)

