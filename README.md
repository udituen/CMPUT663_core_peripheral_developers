# CMPUT663_core_peripheral_developers
This project leverages Bertopic and GPT3 to identify topics prevalent between core and peripheral developers. We utilized a dataset containing conversations between developers and ChatGPT obtained from DevGPT (MSR challenge '23) to make our findings.
## Pre-processing the data

## Reproducing the results
1. The processed_data_all.json contains the data set after processing to remove duplicates and non-english data points
2. Run the Core_developer_category.ipynp script to automatically classify the developers within te dataset into the Core group and Peripheral Group. The 'Answer' from the conversation between ChatGPT and the Core developers will be read into core_convo_1.json and the Prompts from the conversation will be read into core_prompt_1.json. The 'Answer' from the conversations between ChatGPT and the Peripheral developers will be read into peripheral_convo_1.json and the 'Prompts'  from the conversation will be read into Peripheral_prompt_1.json
