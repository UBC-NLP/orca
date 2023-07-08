


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
|**Task**| **Variation**     | **Metric**   | **URL**    | **Bibtex**   |
|---------|--------|--------|-------|------|
|[ANS Stance](https://aclanthology.org/2020.fever-1.2/)      |MSA      |  Macro F1 |       |    [Khouja, 2020](https://scholar.googleusercontent.com/scholar.bib?q=info:Dl2jkOr3b2IJ:scholar.google.com/&output=citation&scisdr=ChXrDqdnEOfk8gr2mYs:ABFrs3wAAAAAZKjwgYvKUQTr12NsJBP89r72L4U&scisig=ABFrs3wAAAAAZKjwgZBGKXv4I0rJEEVCFoE1WQ0&scisf=4&ct=citation&cd=-1&hl=en) | 
|[Baly Stance](https://aclanthology.org/N18-2004/)     |MSA      |  Macro F1 |       |    [Balyet al., 2018](https://scholar.googleusercontent.com/scholar.bib?q=info:WDtKxc5WLi4J:scholar.google.com/&output=citation&scisdr=ChXrDqdnEOfk8gr3PKc:ABFrs3wAAAAAZKjxJKftaQjEZEhOeQIkitiavGk&scisig=ABFrs3wAAAAAZKjxJFSQMJ2SNRGmYSqVZJAa_TY&scisf=4&ct=citation&cd=-1&hl=en) | 
|[XLNI](https://github.com/facebookresearch/XNLI)            |MSA      |  Macro F1 |       |    [Conneau et al., 2018](https://scholar.googleusercontent.com/scholar.bib?q=info:dwBo6WQBvtAJ:scholar.google.com/&output=citation&scisdr=ChXrDqdnEOfk8gr3fS0:ABFrs3wAAAAAZKjxZS3vB-TBD3C6uNciU5h8W2k&scisig=ABFrs3wAAAAAZKjxZbTeiO54_fLShkIoYea-zg4&scisf=4&ct=citation&cd=-1&hl=en) | 

###  (2) Question Answering (QA)
|**Task**| **Variation**     | **Metric**   | **URL**    | **Bibtex**   |
|---------|--------|--------|-------|------|
|[Question Answering](https://aclanthology.org/2021.acl-long.551/)      |MSA      |  Macro F1 |       |    [Abdul-Mageed et al., 2020](https://scholar.googleusercontent.com/scholar.bib?q=info:uFWu72s_lGoJ:scholar.google.com/&output=citation&scisdr=ChXrDqdnEOfk8gryx40:ABFrs3wAAAAAZKj0341kFthVkOGnDJC4ejq-vpc&scisig=ABFrs3wAAAAAZKj033a7zr7kd5xIyWs8qxvFs9E&scisf=4&ct=citation&cd=-1&hl=en) | 


###  (3) Semantic Textual Similarity and and Paraphrase (STSP)
|**Task**| **Variation**     | **Metric**   | **URL**    | **Bibtex**   |
|---------|--------|--------|-------|------|
|[Emotion Regression](https://aclanthology.org/S18-1001/)      |MSA      | Superman Correlation|       |    [Saif et al., 2018](https://scholar.googleusercontent.com/scholar.bib?q=info:-uBntHMpkRkJ:scholar.google.com/&output=citation&scisdr=ChXrDqdnEOfk8grzPbw:ABFrs3wAAAAAZKj1Jbyn0EIiXCipEq7rEqfpqYA&scisig=ABFrs3wAAAAAZKj1JQRX3fWvweGm8JjI13PDNow&scisf=4&ct=citation&cd=-1&hl=en) | 
|[MQ2Q](https://xxxx)     |MSA      |  Macro F1 |       |    [Balyet al., 2018](xx) | 
|[STS](https://aclanthology.org/S17-2001/)            |MSA      |  Macro F1 |       |    [Conneau et al., 2018](xxx) | 



###  (4) Sentence Classification (SC)
|**Task**| **Variation**     | **Metric**   | **URL**    | **Bibtex**   |
|---------|--------|--------|-------|------|
|[Abusive](https://aclanthology.org/2020.fever-1.2/)      |DA      |  Macro F1 |       |    [Khouja, 2020](x) | 
|[Adult](https://aclanthology.org/N18-2004/)     |DA      |  Macro F1 |       |    [Balyet al., 2018](xx) | 
|[Age](https://github.com/facebookresearch/XNLI)            |DA      |  Macro F1 |       |    [Conneau et al., 2018](xxx) | 
|[ANS Claim](https://aclanthology.org/2020.fever-1.2/)      |MSA      |  Macro F1 |       |    [Khouja, 2020](x) | 
|[Dialect at Binary Level	](https://aclanthology.org/N18-2004/)     |DA      |  Macro F1 |       |    [Balyet al., 2018](xx) | 
|[Dialect at Country Level](https://github.com/facebookresearch/XNLI)            |DA      |  Macro F1 |       |    [Conneau et al., 2018](xxx) | 
|[Dialect at Region Level](https://github.com/facebookresearch/XNLI)            |DA      |  Macro F1 |       |    [Conneau et al., 2018](xxx) | 
|[Emotion](https://aclanthology.org/N18-2004/)     |DA      |  Macro F1 |       |    [Balyet al., 2018](xx) | 
|[Gender](https://github.com/facebookresearch/XNLI)            |DA      |  Macro F1 |       |    [Conneau et al., 2018](xxx) | 
|[Hate Speech](https://github.com/facebookresearch/XNLI)            |DA      |  Macro F1 |       |    [Conneau et al., 2018](xxx) | 
|[Irony](https://aclanthology.org/N18-2004/)     |DA      |  Macro F1 |       |    [Balyet al., 2018](xx) | 
|[Machine Generation](https://github.com/facebookresearch/XNLI)            |MSA      |  Macro F1 |       |    [Conneau et al., 2018](xxx) | 
|[Offensive](https://github.com/facebookresearch/XNLI)            |DA      |  Macro F1 |       |    [Conneau et al., 2018](xxx) | 
|[Sarcasm](https://aclanthology.org/N18-2004/)     |DA      |  Macro F1 |       |    [Balyet al., 2018](xx) | 
|[Sentiment Analysis](https://github.com/facebookresearch/XNLI)            |DA      |  Macro F1 |       |    [Conneau et al., 2018](xxx) | 



###  (5) Structure Predictions (SP)
|**Task**| **Variation **     | **Metric**   | **URL**    | **Bibtex**   |
|---------|--------|--------|-------|------|
|[Aqmar NER](https://aclanthology.org/2020.fever-1.2/)      |MSA      |  Macro F1 |       |    [Khouja, 2020](x) | 
|[Arabic NER Corpus](https://aclanthology.org/N18-2004/)     |MSA      |  Macro F1 |       |    [Balyet al., 2018](xx) | 
|[Dialect Part Of Speech](https://github.com/facebookresearch/XNLI)            |DA      |  Macro F1 |       |    [Conneau et al., 2018](xxx) | 
|[MSA Part Of Speech](https://github.com/facebookresearch/XNLI)            |MSA      |  Macro F1 |       |    [Conneau et al., 2018](xxx) | 


###  (6) Topic Classification (TC)
|**Task**| **Variation **     | **Metric**   | **URL**    | **Bibtex**   |
|---------|--------|--------|-------|------|
|[Topic](https://aclanthology.org/2021.acl-long.551/)      |MSA      |  Macro F1 |       |    [Khouja, 2020](x) | 


###  Word Sense Disambiguation (WSD)
|**Task**| **Variation **     | **Metric**   | **URL**    | **Bibtex**   |
|---------|--------|--------|-------|------|
|[Word Sense Disambiguation]([https://aclanthology.org/2020.fever-1.2/](https://www.mdpi.com/2076-3417/11/6/2567)      |MSA      |  Macro F1 |       |    [Khouja, 2020](x) | 


# How to use

## Install Requirments
```shell
    pip install datasets transformers seqeval
```
## Fine-tuning a model on ORCA tasks
We provide a Google's Colab Notbook that has an instructions for fine-tunining any model on ORCA dtasks. <a href="https://colab.research.google.com/github/UBC-NLP/orca/blob/main/Finetuning_ORCA.ipynb.ipynb"><img alt="colab" src="https://colab.research.google.com/assets/colab-badge.svg">

## Submitting your results on ORCA test 
