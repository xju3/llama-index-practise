
[🇨🇳readme cn version](README_CN.md)

## book intro:
* [building-data-driven-applicatinos-wth-llama-index](https://www.packtpub.com/en-us/product/building-data-driven-applications-with-llamaindex-9781835089507)

## runing environment:
- using .env to save some sensitive informations
- here are the variables you need to define in .env.
```sh
    OLLAMA_API=http://localhost:11434
    OLLAMA_MODEL=mistral:latest
    MONGO_URI=mongodb://root:root@localhost
    PG_URI=postgresql://yourname:password@localhost:5433/db_name
    LLAMA_CLOUD_API_KEY=
    OPENAI_API_KEY=
```
- you need to create a .env file under the source code directory.

## notifications
* the recommendions version of python is 3.11, otherwise it might has some incompatible issues.
* [env.py](env.py) is the basic settings for using local ollama
* [llama-index-reader-index.ipynb](llama-index-reader-index.ipynb) convered the knowledges of the book chapters from 1 to 5 , including:
    * reader, 
    * splitter, 
    * phaser, 
    * extractor, 
    * storage context 
    * doc & nodes & index persistence.