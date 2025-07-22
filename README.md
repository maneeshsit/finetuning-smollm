# finetuning-smollm
Fine tuning a SmolLM-135M-Instruct-bnb-4bit Model locally for Ollama
# Google Collaboratory notebook
https://colab.research.google.com/drive/1WfQOdsVEJpp_aTnL6CxTbFpqGdM7YOAH#scrollTo=twEmkIrLZLtD
# Ollam commands for downloaded Model from Colab notebook
ollama create smollm-model -f Modelfile
# list the Model downloaded
ollama list
# Run and test the Model with input prompts
ollama run smollm-model:latest

