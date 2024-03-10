# Chat with PDF 
This Repo implements chat with your PDF via a GUI. This Code utilized OpenAI's LLM and Embedding models for information retreival from your documents. 


![ChatApp UI](https://github.com/PromtEngineer/PDF_Chat-GUI/assets/134474669/bba57a81-909f-4fe3-91cd-96ae14c17438)

## Clone the Repo:
Clone the repository. 
```shell
git clone https://github.com/PromtEngineer/PDF_Chat-GUI.git
```

## Environment Setup
In order to set your environment up to run the code here, first install all requirements:

```shell
pip install -r requirements.txt
```

## OpenAI API Key 

You will need the OpenAI API key to run this, get your OpenAI key from [here](https://platform.openai.com/account/api-keys)
In the `.env` set your API key. 

```shell
OPENAI_API_KEY=
```

## Run the WebApp:

```shell
streamlit run ChatPDF.py
```
