# YouTube Video Transcription with Q&A using LLM
### Author: Abhishek Dubey
### Linkedin: https://www.linkedin.com/in/abhishek-dubey96/
### Email: abhishekdb.1996@gmail.com
### Github: https://github.com/Abhiee8322

# Methodology followed:

#### 1. Install/Import necessary libraries, modules.
#### 2. Function creation of filtering out videos based on length.
# 3. Downloading the audio extracted from the output of the previous step and then storing it in a folder.
# 4. Deleting audio (optional)
# 5. Generated a function to split the input audio into small chunks due to token issue of whisper API and stored the processed audio into the folder.
# 6. Whisper API used to take input from previous step and then generate the transcriptions.
# 7. Document processing begins where recursive splitter is used to split the documents, then chroma is used as a vector db and openai embeddings are used and the resulting vector db is stored in the google drive.
# 8. Extracting the stored vector from the google drive and then querying is performed to get the desired output.

## Code description in detail in the ipynb notebook
