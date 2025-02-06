Clone this repository to your projects folder
Create an OpenAI account if you don't have one by visiting: https://platform.openai.com/
Create your API key in https://platform.openai.com/api-keys - and make a copy of it
Create `.env` file in the projct folder and add the API key in the form of
    OPENAI_API_KEY=<apikey>

on ubuntu 24.04:
`sudo apt install python3-dotenv`
`sudo apt install python3-openai`

run `python3 word_extractor.py`

the idea is to past in a url in a foreign language and get a vocabulary list translated
into English
