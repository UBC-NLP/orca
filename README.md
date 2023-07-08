<p align="center">
    <br>
    <img src="https://orca.dlnlp.ai/assets/orca_logo.png" width="50%"/>
    <br>
<p>

<p align="center">
<a href="https://github.com/UBC-NLP/orca/releases">
        <img alt="GitHub release" src="https://img.shields.io/github/release/UBC-NLP/orca.svg">
    </a>

<a href="https://orca.dlnlp.ai/">
        <img alt="Documentation" src="https://img.shields.io/website.svg?down_color=red&down_message=offline&up_message=online&url=https://orca.dlnlp.ai">
    </a>
<a href="https://github.com/UBC-NLP/orca/blob/main/LICENSE"><img alt="GitHub license" src="https://img.shields.io/github/license/UBC-NLP/orca?logoColor=blue"></a>
<a href='https://orca.readthedocs.io/en/latest/?badge=latest'><img src='https://readthedocs.org/projects/orca/badge/?version=latest' alt='Documentation Status' /></a>
<a href="https://github.com/UBC-NLP/orca/stargazers"><img alt="GitHub stars" src="https://img.shields.io/github/stars/UBC-NLP/orca"></a>
<a href="https://github.com/UBC-NLP/orca/network"><img alt="GitHub forks" src="https://img.shields.io/github/forks/UBC-NLP/orca"></a>

</p>
 
<p> In this work, we introduce ORCA, a publicly available benchmark for Arabic language understanding evaluation. ORCA is carefully constructed to cover diverse Arabic varieties and a wide range of challenging Arabic understanding tasks exploiting 60 different datasets across seven NLU task clusters. To measure current progress in Arabic NLU, we use ORCA to offer a comprehensive comparison between 18 multilingual and Arabic language models.</p>


# ORCA Task Cluster  
###  (1) Natural Language Inference (NLI)
|**Task**| **Variation **     | **Metric**   | **URL**    | **Bibtex**   |
|---------|--------|--------|-------|------|
|[ANS Stance](https://aclanthology.org/2020.fever-1.2/)      |MSA      |  Macro F1 |       |    [(Khouja, 2020)](https://scholar.googleusercontent.com/scholar.bib?q=info:Dl2jkOr3b2IJ:scholar.google.com/&output=citation&scisdr=ChXrDqdnEOfk8gr2mYs:ABFrs3wAAAAAZKjwgYvKUQTr12NsJBP89r72L4U&scisig=ABFrs3wAAAAAZKjwgZBGKXv4I0rJEEVCFoE1WQ0&scisf=4&ct=citation&cd=-1&hl=en) | 
|[Baly Stance](https://aclanthology.org/N18-2004/)     |MSA      |  Macro F1 |       |    XX | 
|[XLNI](https://github.com/facebookresearch/XNLI)            |MSA      |  Macro F1 |       |    XX | 


# How to use

## Install Requirments
```shell
    pip install datasets transformers seqeval
```
## Fine-tuning a model on ORCA tasks
We provide a Google's Colab Notbook that has an instructions for fine-tunining any model on ORCA dtasks. <a href="https://colab.research.google.com/github/UBC-NLP/orca/blob/main/Finetuning_ORCA.ipynb.ipynb"><img alt="colab" src="https://colab.research.google.com/assets/colab-badge.svg">

## Submitting your results on ORCA test 
