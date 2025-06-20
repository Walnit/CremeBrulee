# CremeBrulee - The Creme-de-la-creme of my Notebooks
Learning AI is hard. Resources are often scattered, varying in quality, and sometimes outdated.  

That's why in this repository, I'm setting out to collate the best notebooks that I've written. Each notebook is *meticulously* handcrafted and, hopefully, easy to understand.  

If you want to support this, I guess you could drop a PR and a star! :D

## What can you expect?
Each notebook will:
- Come with loads of **explanation**,
- Contain **working code** with **no weird custom libraries**,
- Be **optimized for lazy people**,
- Have a README detailing **required prerequisite knowledge** and a **summary** of learning objectives,
- Totally not have odd, unintepretable pop culture references...?

## Usage
Simply browse the folders in the GitHub repo - I've tried my best to have some sort of organization. Each category should have an index with summaries of all notebooks within itself, so that you can browse through it and find what's worth reading. So far, the categories are:

| Folder Name | Description |
|-------------| ------------|
| General Skills | Techniques and frameworks that can be generalized across most models and use-cases. Currently has 2 notebooks. |
| Computer Vision | Notebooks relating to Computer Vision (CV), including explanations of various papers. Currently has 1 notebook, 1 WIP. |
| Natural Language Processing | Notebooks relating to Natural Language Processing (NLP). Currently empty :P |

The notebooks are meant for reading, not for execution. Thus I don't have any pinned library versions or even `pip install` commands in the notebook - which hopefully makes it easier to read.  

But if you want to cover most of your bases, try installing all of the libraries below - I won't use most of them though!
`pip install torch torchvision matplotlib pytorch-lightning einops tensorboard scikit-learn xgboost catboost transformers spacy nltk pandas numpy scipy opencv-python Pillow scikit-image seaborn plotly autoviz joblib datasets evaluate tqdm accelerate hf_xet torchinfo`

A disclaimer that I use **PyTorch Lightning** extensively, as it's a massive timesaver. I'll make a notebook for it shortly, but for now there's many resources you can use online.