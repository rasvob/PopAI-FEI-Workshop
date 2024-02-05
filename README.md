# Exercises for the AI Workshop held at FEI, VSB-TU Ostrava.

Feel free to [Radek](radek.svoboda@vsb.cz) or [Michal](michal.vasinek@vsb.cz) if you have any questions or want to discuss any topic from the workshop 😊

All authorship is mentioned where possible.

# Content of the workshop
The aim of the workshop is to get an overview of possibilities in the generative artificial intelligence (GenAI) domain.

We will use mainly [ChatGPT](https://chat.openai.com/) and [Huggingface](https://huggingface.co/).

The exercise will cover these topics:
* GenAI tools for image data using Huggingface models
* Vector representation of text data and searching for similar words using vector distance 
* Design of own deep learning model for generating "Harry Potter"-like text using Keras framework from scratch

## Stable Diffusion as an AI Image Generator 
> [Jupyter Notebook](https://github.com/rasvob/PopAI-FEI-Workshop/blob/main/ws_01.ipynb)

> [Google Colab](https://colab.research.google.com/github/rasvob/PopAI-FEI-Workshop/blob/main/ws_01.ipynb)

## Self-hosting LLMs using Huggingface
> [Jupyter Notebook](https://github.com/rasvob/PopAI-FEI-Workshop/blob/main/ws_02.ipynb)

> [Google Colab](https://colab.research.google.com/github/rasvob/PopAI-FEI-Workshop/blob/main/ws_02.ipynb)

# 💡 Notes
## How to create a Python Virtual Enviroment named `venv`
### Create `venv`
```
python -m venv venv
```

### Activate `venv`

* Activate `venv` in **Windows**
```
.\venv\Scripts\Activate.ps1
```

* Activate `venv` in **Linux**
```
source venv/bin/activate
```


### Intall python packages

```
pip install jupyter "jupyterlab>=3" "ipywidgets>=7.6"
pip install pandas matplotlib requests seaborn scipy torch transformers accelerate bitsandbytes diffusers invisible_watermark safetensors
```