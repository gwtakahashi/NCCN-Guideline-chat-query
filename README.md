# NCCN-Guideline-chat-query

To use this code, you will need API keys from OpenAI and HuggingFace. 

Place all your NCCN guidelines PDF files in a folder called NCCN. (Don't use subfolders.)

This is my second version, which includes a fallback to an Internet search for answers, since many of my queries were coming back empty. If the answer to a question cannot be found in the NCCN
guidelines, then an answer will be sought by an Internet search. 

This code is built upon Ed Donner's excellent LLM Engineering Course (https://www.udemy.com/course/llm-engineering-master-ai-and-large-language-models/).
