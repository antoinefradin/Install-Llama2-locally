# Install-Llama2-locally

<p align="center">
    <img src="img.png" alt="Llama2-locally" width=850px style="text-align:center"/>
</p>

In this project, we are describing 3 ways to install Llama 2 locally with CPU.



&nbsp; 



## ⚙️ **Prerequisites and Installation**

To start working with the **Llama 2** notebooks, you need to set up your Python environment.  
  
In summary, this is what you will need:
- Python 3
- virtualenv

&nbsp; 

```bash
$ pip3 install virtualenv

#Test your installation:
$ virtualenv --version

# Create your virtual environment
$ python3 -m venv .venv

# you can activate the virtual environment by just input
source .venv/bin/activate

# then you can deactivate it by just type in deactivate.
source .venv/bin/deactivate

# If you want to delete that virtual env, simply do
rm -rf .venv
```

&nbsp; 

Once the `virtualenv` is activated, you can install the required dependencies.

```bash
$ pip3 install -r requirements.txt
```

&nbsp; 


## 🚀 **Starting**


1. Load LlaMA model with `llama-cpp-python` 
2. Load LlaMA model with `Langchain` 
3. Load LlaMA model with `Ollama` & `Langchain` 
4. Load LlaMA model with `Hugging Face` 



&nbsp; 

&nbsp; 

&nbsp; 

&nbsp; 

## **Reference:**
- Medium: [3-ways to Set up LLaMA 2 Locally on CPU (Part 1 — llama-cpp-python)](https://medium.com/@fradin.antoine17/3-ways-to-set-up-llama-2-locally-on-cpu-part-1-5168d50795ac)
