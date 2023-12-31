# Document Reader and 
# Chatbot using LangChain and OpenAI

## Summary
Simple implementation of a chatbot.


Python scripts to get started with building a multi document reader and chatbot.
`chatbot.py` can handle interacting with multiple different documents and document types (.pdf, .dox, .txt), 
and remembers the chat history and recent conversations.
It uses embeddings and vector stores to send the relevant information to the LLM prompt. Also provides a chat interface
via the terminal using stdin and stdout. Press `q` to escape the chat window.


## Getting started


Clone the repository, set up the virtual environment( Python 3.11), and install the required packages


## Store your OpenAI API key
Copy the key to the  env file
`OPENAI_API_KEY=sk-`

## Add Documents
Add documents for chat. Document types (.pdf, .dox, .txt)

### There are no additional requirements!


## Start chatting
Run chatbot, and start interacting with your files. 
Place any files you would like to interact with inside the `/docs` folder. 
Enter `q` to exit the prompt at any time.

```python
python3 chatbot.py
```
## web interface

The implementation is optimized for a single document.

Built using Streamlit,you can start the server by running:
 `streamlit run web\main2.py`  from the root folder.

You may need to run `pip install faiss-cpu or faiss-gpu` depending on your machine.




## -
Stay tuned for more updates!!

That's it. 

It's not production grade but will get you started.
