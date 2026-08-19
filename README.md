# Scripts to convert safetensor models into GGUF Format 

I have created this repo to convert safetensor models in GGUF format using colab and llama.cpp without installing anything on your local machine and you upload model in your Huggingface Account as well as can download locally.

---

## Tech Stack
- Google Colab
- llama.cpp
- HuggingFace
- Python

--- 

## Which problem its Solves?
Usually you may have to download llama cpp library, safetensor models locally and set the configs which sometime becomes so difficult, time consuming and resouce contraintations. so I created some scripts where you can convert safetensor weights into GGUF format and can also quantized them. It helps in faster development, easy to understand, and enough resource computation. Under the hood it uses llama for conversion.


---

## Models
- IBM Granite Embedding: [Link](https://huggingface.co/arshvir/granite-embedding-311m-multilingual-r2-GGUF)

- Microsoft Harrier: [Link](https://huggingface.co/arshvir/harrier-oss-v1-0.6b-GGUF)

---

Developed and Maintained by Arshvir :)