


<p align="center">
    <br>
    <img src="https://orca.dlnlp.ai/assets/orca_logo.png" width="55%"/>
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
 
In this work, we introduce [**ORCA**](https://arxiv.org/abs/2212.10758), a publicly available benchmark for Arabic language understanding evaluation. ORCA is carefully constructed to cover diverse Arabic varieties and a wide range of challenging Arabic understanding tasks exploiting 60 different datasets across seven NLU task clusters. To measure current progress in Arabic NLU, we use ORCA to offer a comprehensive comparison between 18 multilingual and Arabic language models.


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
|[Question Answering](https://aclanthology.org/2021.acl-long.551/)      |MSA      |  Macro F1 |       |    [Abdul-Mageed et al., 2020a](https://scholar.googleusercontent.com/scholar.bib?q=info:uFWu72s_lGoJ:scholar.google.com/&output=citation&scisdr=ChXrDqdnEOfk8gryx40:ABFrs3wAAAAAZKj0341kFthVkOGnDJC4ejq-vpc&scisig=ABFrs3wAAAAAZKj033a7zr7kd5xIyWs8qxvFs9E&scisf=4&ct=citation&cd=-1&hl=en) | 


###  (3) Semantic Textual Similarity and and Paraphrase (STSP)
|**Task**| **Variation**     | **Metric**   | **URL**    | **Bibtex**   |
|---------|--------|--------|-------|------|
|[Emotion Regression](https://aclanthology.org/S18-1001/)      |MSA      | Superman Correlation|       |    [Saif et al., 2018](https://scholar.googleusercontent.com/scholar.bib?q=info:-uBntHMpkRkJ:scholar.google.com/&output=citation&scisdr=ChXrDqdnEOfk8grzPbw:ABFrs3wAAAAAZKj1Jbyn0EIiXCipEq7rEqfpqYA&scisig=ABFrs3wAAAAAZKj1JQRX3fWvweGm8JjI13PDNow&scisf=4&ct=citation&cd=-1&hl=en) | 
|[MQ2Q](https://aclanthology.org/2019.nsurl-1.1)     |MSA      |  Macro F1 |       |    [Seelawi al., 2019](https://scholar.googleusercontent.com/scholar.bib?q=info:qfTkZzI_lQ4J:scholar.google.com/&output=citation&scisdr=ChXrDqdnEOfk8grwP7w:ABFrs3wAAAAAZKj2J7w82mvzxbjso-nscARRjsY&scisig=ABFrs3wAAAAAZKj2J5Tle8i7Ky-IW3B4B4IRDxo&scisf=4&ct=citation&cd=-1&hl=en) | 
|[STS](https://aclanthology.org/S17-2001/)            |MSA      |  Macro F1 |       |    [Cer et al., 2017](https://scholar.googleusercontent.com/scholar.bib?q=info:Sa2jq4YiCs4J:scholar.google.com/&output=citation&scisdr=ChXrDqdnEOfk8grwTkg:ABFrs3wAAAAAZKj2Vkgj0LxgPCeJOzGZH5UUOxs&scisig=ABFrs3wAAAAAZKj2ViLdnSzljs_rRxxPVsQRNKs&scisf=4&ct=citation&cd=-1&hl=en) | 



###  (4) Sentence Classification (SC)
|**Task**| **Variation**     | **Metric**   | **URL**    | **Bibtex**   |
|---------|--------|--------|-------|------|
|[Abusive](https://aclanthology.org/W19-3512/)      |DA      |  Macro F1 |       |    [Mulki et al., 2019](https://scholar.googleusercontent.com/scholar.bib?q=info:rfEhXJdtqcgJ:scholar.google.com/&output=citation&scisdr=ChXrDqdnEOfk8gr9Gog:ABFrs3wAAAAAZKj7Aog3zIXv0eE5S7vtBl-1IAM&scisig=ABFrs3wAAAAAZKj7AoxDWAq2kYzqlddJwFHHD1o&scisf=4&ct=citation&cd=-1&hl=en) | 
|[Adult](https://aclanthology.org/2021.wanlp-1.14)     |DA      |  Macro F1 |       |    [Mubarak et al., 2021](https://scholar.googleusercontent.com/scholar.bib?q=info:-9T7luMQ9U0J:scholar.google.com/&output=citation&scisdr=ChXrDqdnEOfk8gr9z_E:ABFrs3wAAAAAZKj71_GxiCVJWByCOEwYNhYOo80&scisig=ABFrs3wAAAAAZKj718edY9Y__adh_COzeQ7LqHM&scisf=4&ct=citation&cd=-1&hl=en)| 
|[Age](https://www.aclweb.org/anthology/2020.osact-1.3)            |DA      |  Macro F1 |       |    [Abdul-Mageed et al., 2020b]( https://aclanthology.org/2020.osact-1.3/) | 
|[ANS Claim](https://aclanthology.org/2020.fever-1.2/)     |MSA      |  Macro F1 |       |   [Khouja, 2020](https://scholar.googleusercontent.com/scholar.bib?q=info:Dl2jkOr3b2IJ:scholar.google.com/&output=citation&scisdr=ChXrDqdnEOfk8gr2mYs:ABFrs3wAAAAAZKjwgYvKUQTr12NsJBP89r72L4U&scisig=ABFrs3wAAAAAZKjwgZBGKXv4I0rJEEVCFoE1WQ0&scisf=4&ct=citation&cd=-1&hl=en) | 
|[Dialect Binary	](https://aclanthology.org/N18-2004/)     |DA      |  Macro F1 |       |    [(Farha, 2020)](https://aclanthology.org/2020.osact-1.5/), [(Zaidan, 2014)](xx), [(Abdul-Mageed et al., 2020c)](xx), [(Bouamor et al., 2019)](xx), [(Abdelaliet al., 2020)](xx), [(El-Haj, 2020)](xx). | 
|[Dialect Country](https://github.com/facebookresearch/XNLI)            |DA      |  Macro F1 |       |   [(Farha, 2020)](https://aclanthology.org/2020.osact-1.5/), [(Zaidan, 2014)](xx), [(Abdul-Mageed et al., 2020c)](xx), [(Bouamor et al., 2019)](xx), [(Abdelaliet al., 2020)](xx), [(El-Haj, 2020)](xx). | 
|[Dialect Region](https://github.com/facebookresearch/XNLI)            |DA      |  Macro F1 |       | [(Farha, 2020)](https://aclanthology.org/2020.osact-1.5/), [(Zaidan, 2014)](xx), [(Abdul-Mageed et al., 2020c)](xx), [(Bouamor et al., 2019)](xx), [(Abdelaliet al., 2020)](xx), [(El-Haj, 2020)](xx). | 
|[Emotion](https://www.aclweb.org/anthology/2020.osact-1.3)            |DA      |  Macro F1 |       |    [Abdul-Mageed et al., 2020b]( https://aclanthology.org/2020.osact-1.3/) | 
|[Gender](https://www.aclweb.org/anthology/2020.osact-1.3)            |DA      |  Macro F1 |       |    [Abdul-Mageed et al., 2020b]( https://aclanthology.org/2020.osact-1.3/) | 
|[Hate Speech](https://www.aclweb.org/anthology/2020.osact-1.7)            |DA      |  Macro F1 |       |    [Mubarak et al., 2020](https://www.aclweb.org/anthology/2020.osact-1.7)| 
|[Irony](https://dl.acm.org/doi/10.1145/3368567.3368585)     |DA      |  Macro F1 |       |    [Ghanem al., 2019](https://dl.acm.org/doi/10.1145/3368567.3368585) | 
|[Machine Generation](https://aclanthology.org/2020.wanlp-1.7/)            |MSA      |  Macro F1 |       |    [Nagoudi et al., 2020](https://aclanthology.org/2020.wanlp-1.7/) | 
|[Offensive](https://aclanthology.org/2020.osact-1.8/)            |DA      |  Macro F1 |       |    [Mubarak et al., 2020](https://www.aclweb.org/anthology/2020.osact-1.7)| 
|[Sarcasm](https://aclanthology.org/N18-2004/)     |DA      |  Macro F1 |       |    [Farha and Magdy, 2020](https://aclanthology.org/2020.osact-1.5/) | 
|[Sentiment Analysis](https://aclanthology.org/2021.acl-long.551/)         |DA      |  Macro F1 |       |    [Abdul-Mageed et al., 2020c](https://aclanthology.org/2021.acl-long.551/) | 



###  (5) Structure Predictions (SP)
|**Task**| **Variation **     | **Metric**   | **URL**    | **Bibtex**   |
|---------|--------|--------|-------|------|
|[Aqmar NER](https://www.cs.cmu.edu/~ark/ArabicNER/)      |MSA      |  Macro F1 |       |    [Mohit, 2012](https://scholar.googleusercontent.com/scholar.bib?q=info:yAp4k3zwiUEJ:scholar.google.com/&output=citation&scisdr=ChXrDqdnEOfk8gsH__s:ABFrs3wAAAAAZKkB5_vSGkF_RBbXEJ6jQtj1QLE&scisig=ABFrs3wAAAAAZKkB51R-dpSL59TX-7pfhBpllYY&scisf=4&ct=citation&cd=-1&hl=en) | 
|[Arabic NER Corpus](http://www.dsic.upv.es/~prosso/resources/BenajibaRosso_IICAI07.pdf)     |MSA      |  Macro F1 |       |    [Benajiba and Rosso, 2007](https://scholar.googleusercontent.com/scholar.bib?q=info:7lzaX3LgFm0J:scholar.google.com/&output=citation&scisdr=ChXrDqdnEOfk8gsEZds:ABFrs3wAAAAAZKkCfdu54C_20sUBAs0qQl0T-MU&scisig=ABFrs3wAAAAAZKkCfRUtInM39LNKgqLZG7jAPs8&scisf=4&ct=citation&cd=-1&hl=en) | 
|[Dialect Part Of Speech](https://aclanthology.org/L18-1015.pdf)            |DA      |  Macro F1 |       |    [Darwish et al., 2018](https://aclanthology.org/L18-1015.pdf) | 
|[MSA Part Of Speech](https://arxiv.org/abs/2004.01401)            |MSA      |  Macro F1 |       |    [Liang et al., 2020](https://arxiv.org/abs/2004.01401) | 
 

###  (6) Topic Classification (TC)
|**Task**| **Variation**     | **Metric**   | **URL**    | **Bibtex**   |
|---------|--------|--------|-------|------|
|[Topic](https://aclanthology.org/2021.acl-long.551/)      |MSA      |  Macro F1 |       |    [(Abbas et al.,2011)](https://www.dline.info/fpaper/jdim/v9i5/1.pdf), [(Chouigui et al.,2017)](https://www.researchgate.net/publication/320871871_Poster_ANT_Corpus_An_Arabic_News_Text_Collection_for_Textual_Classification),  [(Saad, 2010)](http://site.iugaza.edu.ps/wp-content/uploads/mksaad-OSAC-OpenSourceArabicCorpora-EECS10-rev9(1).pdf). | 


###  Word Sense Disambiguation (WSD)
|**Task**| **Variation**     | **Metric**   | **URL**    | **Bibtex**   |
|---------|--------|--------|-------|------|
|[Word Sense Disambiguation](https://www.mdpi.com/2076-3417/11/6/2567)     |MSA      |  Macro F1 |       |    [El-Razzaz, 2021](https://www.mdpi.com/2076-3417/11/6/2567) | 


# How to use

## Install Requirments
```shell
    pip install datasets transformers seqeval
```
## Fine-tuning a model on ORCA tasks
We provide a Google's Colab Notbook that has an instructions for fine-tunining any model on ORCA dtasks. <a href="https://colab.research.google.com/github/UBC-NLP/orca/blob/main/Finetuning_ORCA.ipynb.ipynb"><img alt="colab" src="https://colab.research.google.com/assets/colab-badge.svg">

## Submitting your results on ORCA test 
