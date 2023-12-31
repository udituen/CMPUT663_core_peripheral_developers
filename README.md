# CMPUT663_core_peripheral_developers
This project leverages Bertopic and GPT3 to identify topics prevalent between core and peripheral developers. We utilized a dataset containing conversations between developers and ChatGPT obtained from DevGPT (MSR challenge '23) to make our findings.
## Requirements
The dependencies and libraries needed to reproduce our results are contained in the requirements.txt file
Generate a personal access token from GitHub with scope : 'repo' to enable mining of repositories.

## Reproducing the results
1. The processed_data_all.json (stored on the drive linked in the report) contains the data set after processing to remove duplicates and non-english data points
2. Run the Core_developer_category.ipynp script to automatically classify the developers within the dataset into the Core group and Peripheral Group. The 'Answer' from the conversation between ChatGPT and the Core developers will be read into core_convo_1.json and the Prompts from the conversation will be read into core_prompt_1.json. The 'Answer' from the conversations between ChatGPT and the Peripheral developers will be read into peripheral_convo_1.json and the 'Prompts'  from the conversation will be read into Peripheral_prompt_1.json
3. To reproduce the topic modeling and evaluation result, upload the dataset obtained from the previous step in the same directory as the topic_modeling.ipynb file. Then, run all cells.
4. Results will be displayed once each cell completes running.
