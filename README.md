A query master is a tool or system that processes questions and generates responses, utilizing advanced language models like those from OpenAI or open-source alternatives available through Hugging Face. It leverages natural language processing (NLP) techniques to understand and produce accurate and contextually relevant answers.

**Step 1**: To access and utilize GPT models from OpenAI for your projects, generate an OpenAI API key. If you are using Hugging Face models, adjust the LLM pipeline accordingly.

After generating your API key, clone the git repository. Then, create a file named **.env** and store your key in it using the format 

```
OPENAI_API_KEY="your generated key".
```

**Step 2**: Create a virtual python envirnonment.
```
conda create -p venv python==3.9 -y
```
**Step 3**: Activate the virtual python envirnonment.
```
conda activate venv
```

**Step 4**: Install all the packages in the virtual envirnonment using the following command.
```
pip install requirements.txt
```

**Step 5**: After installing all necessary packages, use the command to launch your Streamlit application.
```
streamlit run app.py
```

Once your Streamlit application is running, you can interact with it through your web browser by navigating to the localhost URL displayed in your terminal. This completes the setup, allowing you to explore and interact with your project's features in a user-friendly web interface.
