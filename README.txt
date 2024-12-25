For Data extraction:

1st run - doc_txt -> 
extracts all texts from .doc, .docx and .pdf file and converts them into txt file in output filepath

2nd run - summarisetxt ->
chunks txt file which are more than 7000 chars and higher and summarises using ollama

3rd run - llm_formatting ->
prompts ollama for extracting required data (change prompt as per requirement)
saves the output in an excel file along with filename and category extracted from filename
formats the saved excel file and cleans it up (2 steps)

4th run dataext ->
extracts the formatted data and creates another excel with multiple columns
according to the data.