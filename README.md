# Exercises for the AI Workshop held at FEI, VSB-TU Ostrava.

Feel free to [Radek](radek.svoboda@vsb.cz) or [Michal](michal.vasinek@vsb.cz) if you have any questions or want to discuss any topic from the workshop 😊

📌 [Slides presented at the workshop](https://github.com/rasvob/PopAI-FEI-Workshop/blob/main/presentations/ai-460-13-02-2024.pdf)

# Content of the workshop
The aim of the workshop is to get an overview of possibilities in the generative artificial intelligence (GenAI) domain.

We will use mainly [ChatGPT](https://chat.openai.com/) and [HuggingFace](https://huggingface.co/).

The workshop will cover these topics:
* How to use GenAI tools for image data using HuggingFace models (Stable Diffusion) in Python
* How to build simple interface for self-hosted LLM-based chatbot in Jupyter notebook

## Stable Diffusion as an AI Text-To-Image Generator 
> [Jupyter Notebook](https://github.com/rasvob/PopAI-FEI-Workshop/blob/main/ws_01.ipynb)

> [Google Colab](https://colab.research.google.com/github/rasvob/PopAI-FEI-Workshop/blob/main/ws_01.ipynb)

## Self-hosting LLMs using HuggingFace
* 💡Beware that free-tier Colab does not have enough resources

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