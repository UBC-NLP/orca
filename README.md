


<p align="center">
    <br>
    <img src="https://orca.dlnlp.ai/assets/orca_logo.png" width="55%"/>
    <br>
<p>

<p align="center">
<!-- <a href="https://github.com/UBC-NLP/orca/releases"> -->
<!--         <img alt="GitHub release" src="https://img.shields.io/github/release/UBC-NLP/orca.svg"> </a>-->

<a href="https://orca.dlnlp.ai/">
        <img alt="Documentation" src="https://img.shields.io/website.svg?down_color=red&down_message=offline&up_message=online&url=https://orca.dlnlp.ai">
    </a>
<!-- <a href="https://github.com/UBC-NLP/orca/blob/main/LICENSE"><img alt="GitHub license" src="https://img.shields.io/github/license/UBC-NLP/orca?logoColor=blue"></a> -->
<!-- <a href='https://orca.readthedocs.io/en/latest/?badge=latest'><img src='https://readthedocs.org/projects/orca/badge/?version=latest' alt='Documentation Status' /></a> -->
<a href="https://github.com/UBC-NLP/orca/stargazers"><img alt="GitHub stars" src="https://img.shields.io/github/stars/UBC-NLP/orca"></a>
<a href="https://github.com/UBC-NLP/orca/network"><img alt="GitHub forks" src="https://img.shields.io/github/forks/UBC-NLP/orca"></a>

</p>
 
In this work, we introduce [**ORCA**](https://arxiv.org/abs/2212.10758), a publicly available benchmark for Arabic language understanding evaluation. ORCA is carefully constructed to cover diverse Arabic varieties and a wide range of challenging Arabic understanding tasks exploiting 60 different datasets across seven NLU task clusters. To measure current progress in Arabic NLU, we use ORCA to offer a comprehensive comparison between 18 multilingual and Arabic language models.


# ORCA's Task Clusters  
We arrange [**ORCA**](https://arxiv.org/abs/2212.10758), into seven NLU task clusters. These are (1) sentence classification, (2) structured prediction (3) semantic textual similarity and paraphrase, (4) text classification, (5) natural language inference, (6) word sense disambiguation, and (7) question answering.


###  (1) Natural Language Inference (NLI)
|**Task**| **Variation**     | **Metric**   | **Reference**   |
|---------|--------|--------|------|
|[ANS Stance](https://aclanthology.org/2020.fever-1.2/)      |MSA      |  Macro F1 |    [(Khouja, 2020)](https://aclanthology.org/2020.fever-1.2/)  | 
|[Baly Stance](https://aclanthology.org/N18-2004/)     |MSA      |  Macro F1 |    [(Balyet al., 2018)](https://aclanthology.org/N18-2004/) | 
|[XLNI](https://github.com/facebookresearch/XNLI)            |MSA      |  Macro F1 |    [(Conneau et al., 2018)](https://github.com/facebookresearch/XNLI)| 

###  (2) Question Answering (QA)
|**Task**| **Variation**     | **Metric**   | **Reference**   |
|---------|--------|--------|------|
|[Question Answering](https://aclanthology.org/2021.acl-long.551/)      |MSA      |  Macro F1 |    [(Abdul-Mageed et al., 2020a)](https://aclanthology.org/2021.acl-long.551/) | 


###  (3) Semantic Textual Similarity and  Paraphrase (STSP)
|**Task**| **Variation**     | **Metric**   | **Reference**   |
|---------|--------|--------|-------|
|[Emotion Regression](https://aclanthology.org/S18-1001/)      |MSA      | Spearman Correlation|    [(Saif et al., 2018)](https://aclanthology.org/S18-1001/)  | 
|[MQ2Q](https://aclanthology.org/2019.nsurl-1.1)     |MSA      |  Macro F1 |    [(Seelawi al., 2019)](https://aclanthology.org/2019.nsurl-1.1)   | 
|[STS](https://aclanthology.org/S17-2001/)            |MSA      |  Macro F1 |    [(Cer et al., 2017)](https://aclanthology.org/S17-2001/)  | 



### (4) Sentence Classification (SC)
|**Task**| **Variation**     | **Metric**   | **Reference**   |
|---------|--------|--------|-------|
|[Abusive](https://aclanthology.org/W19-3512/)      |DA      |  Macro F1 |    [(Mulki et al., 2019)](https://aclanthology.org/W19-3512/)  | 
|[Adult](https://aclanthology.org/2021.wanlp-1.14)     |DA      |  Macro F1 |    [(Mubarak et al., 2021)](https://aclanthology.org/2021.wanlp-1.14)  | 
|[Age](https://www.aclweb.org/anthology/2020.osact-1.3)            |DA      |  Macro F1 |    [(Abdul-Mageed et al., 2020b)]( https://aclanthology.org/2020.osact-1.3/) | 
|[ANS Claim](https://aclanthology.org/2020.fever-1.2/)     |MSA      |  Macro F1 |   [(Khouja, 2020)](https://aclanthology.org/2020.fever-1.2/)   | 
|[ANS Claim](https://aclanthology.org/2020.fever-1.2/)     |MSA      |  Macro F1 |   [(Khouja, 2020)](https://aclanthology.org/2020.fever-1.2/)   | 
|[Dangerous	](https://aclanthology.org/N18-2004/)     |DA      |  Macro F1 |    [(Alshehri et al., 2020)](https://www.aclweb.org/anthology/2020.osact-1.6)| 
|[Dialect Binary](https://github.com/facebookresearch/XNLI)            |DA      |  Macro F1|   [(Farha, 2020)](https://aclanthology.org/2020.osact-1.5/), [(Zaidan, 2014)](https://www.aclweb.org/anthology/J14-1006), [(Abdul-Mageed et al., 2020c)](https://aclanthology.org/2021.acl-long.551/), [(Bouamor et al., 2019)](https://www.aclweb.org/anthology/W19-4622), [(Abdelaliet al., 2020)](https://aclanthology.org/2021.wanlp-1.1), [(El-Haj, 2020)](https://aclanthology.org/2020.lrec-1.165/). | 
|[Dialect Country](https://github.com/facebookresearch/XNLI)            |DA      |  Macro F1 |   [(Farha, 2020)](https://aclanthology.org/2020.osact-1.5/), [(Zaidan, 2014)](https://www.aclweb.org/anthology/J14-1006), [(Abdul-Mageed et al., 2020c)](https://aclanthology.org/2021.acl-long.551/), [(Bouamor et al., 2019)](https://www.aclweb.org/anthology/W19-4622), [(Abdelaliet al., 2020)](https://aclanthology.org/2021.wanlp-1.1), [(El-Haj, 2020)](https://aclanthology.org/2020.lrec-1.165/). | 
|[Dialect Region](https://github.com/facebookresearch/XNLI)            |DA      |  Macro F1 |  [(Farha, 2020)](https://aclanthology.org/2020.osact-1.5/), [(Zaidan, 2014)](https://www.aclweb.org/anthology/J14-1006), [(Abdul-Mageed et al., 2020c)](https://aclanthology.org/2021.acl-long.551/), [(Bouamor et al., 2019)](https://www.aclweb.org/anthology/W19-4622), [(Abdelaliet al., 2020)](https://aclanthology.org/2021.wanlp-1.1), [(El-Haj, 2020)](https://aclanthology.org/2020.lrec-1.165/). | 
|[Emotion](https://www.aclweb.org/anthology/2020.osact-1.3)            |DA      |  Macro F1 |    [(Abdul-Mageed et al., 2020b)]( https://aclanthology.org/2020.osact-1.3/) | 
|[Gender](https://www.aclweb.org/anthology/2020.osact-1.3)            |DA      |  Macro F1 |    [(Abdul-Mageed et al., 2020b)]( https://aclanthology.org/2020.osact-1.3/) | 
|[Hate Speech](https://www.aclweb.org/anthology/2020.osact-1.7)            |DA      |  Macro F1 |    [(Mubarak et al., 2020)](https://www.aclweb.org/anthology/2020.osact-1.7)| 
|[Irony](https://dl.acm.org/doi/10.1145/3368567.3368585)     |DA      |  Macro F1 |    [(Ghanem al., 2019)](https://dl.acm.org/doi/10.1145/3368567.3368585) | 
|[Machine Generation](https://aclanthology.org/2020.wanlp-1.7/)            |MSA      |  Macro F1 |    [(Nagoudi et al., 2020)](https://aclanthology.org/2020.wanlp-1.7/) | 
|[Offensive](https://aclanthology.org/2020.osact-1.8/)            |DA      |  Macro F1 |    [(Mubarak et al., 2020)](https://www.aclweb.org/anthology/2020.osact-1.7)| 
|[Sarcasm](https://aclanthology.org/N18-2004/)     |DA      |  Macro F1 |    [(Farha and Magdy, 2020)](https://aclanthology.org/2020.osact-1.5/) | 
|[Sentiment Analysis](https://aclanthology.org/2021.acl-long.551/)         |DA      |  Macro F1 |    [(Abdul-Mageed et al., 2020c)](https://aclanthology.org/2021.acl-long.551/) | 



###  (5) Structure Predictions (SP)
|**Task**| **Variation**     | **Metric**   | **Reference**   |
|---------|--------|--------|-------|
|[Aqmar NER](https://www.cs.cmu.edu/~ark/ArabicNER/)      |MSA      |  Macro F1 |    [(Mohit, 2012)](https://www.cs.cmu.edu/~ark/ArabicNER/)  | 
|[Arabic NER Corpus](http://www.dsic.upv.es/~prosso/resources/BenajibaRosso_IICAI07.pdf)     |MSA      |  Macro F1 |    [(Benajiba and Rosso, 2007)](http://www.dsic.upv.es/~prosso/resources/BenajibaRosso_IICAI07.pdf)  | 
|[Dialect Part Of Speech](https://aclanthology.org/L18-1015.pdf)            |DA      |  Macro F1 |    [(Darwish et al., 2018)](https://aclanthology.org/L18-1015.pdf) | 
|[MSA Part Of Speech](https://arxiv.org/abs/2004.01401)            |MSA      |  Macro F1 |    [(Liang et al., 2020)](https://arxiv.org/abs/2004.01401) | 
 

###  (6) Topic Classification (TC)
|**Task**| **Variation**     | **Metric**   | **Reference**   |
|---------|--------|--------|-------|
|[Topic](https://aclanthology.org/2021.acl-long.551/)      |MSA      |  Macro F1 |    [(Abbas et al.,2011)](https://www.dline.info/fpaper/jdim/v9i5/1.pdf), [(Chouigui et al.,2017)](https://www.researchgate.net/publication/320871871_Poster_ANT_Corpus_An_Arabic_News_Text_Collection_for_Textual_Classification),  [(Saad, 2010)](http://site.iugaza.edu.ps/wp-content/uploads/mksaad-OSAC-OpenSourceArabicCorpora-EECS10-rev9(1).pdf). | 


###  (7) Word Sense Disambiguation (WSD)
|**Task**| **Variation**     | **Metric**   | **Reference**   |
|---------|--------|--------|-------|
|[Word Sense Disambiguation](https://www.mdpi.com/2076-3417/11/6/2567)     |MSA      |  Macro F1 |    [(El-Razzaz, 2021)](https://www.mdpi.com/2076-3417/11/6/2567) | 


# How to Use ORCA

### Install Requirments
```shell
    pip install datasets transformers seqeval
```
### Fine-tuning PLMs on ORCA tasks
We provide a Google Colab Notebook that includes instructions for fine-tuning any model on ORCA tasks. <a href="https://colab.research.google.com/github/UBC-NLP/orca/blob/main/Finetuning_ORCA.ipynb"><img alt="colab" src="https://colab.research.google.com/assets/colab-badge.svg">

### Submitting your results on the ORCA test 

We design a public leaderboard for scoring PLMs on ORCA. Our leaderboard is interactive and offers rich meta-data about the various datasets involved as well as the language models we evaluate. 

You can evalute your models using **ORCA** leaderboard: **[https://orca.dlnlp.ai](https://orca.dlnlp.ai/index_main.php)**


---

## Citation
If you use ORCA for your scientific publication, or if you find the resources in this repository useful, please cite our paper as follows (to be updated):
```
@inproceedings{elmadany-etal-2023-orca,
              title = "{ORCA}: A Challenging Benchmark for {A}rabic Language Understanding",
              author = "Elmadany, AbdelRahim  and Nagoudi, ElMoatez Billah  and Abdul-Mageed, Muhammad",
              booktitle = "Findings of the Association for Computational Linguistics: ACL 2023",
              month = jul,
              year = "2023",
              address = "Toronto, Canada",
              publisher = "Association for Computational Linguistics",
              url = "https://aclanthology.org/2023.findings-acl.609",
              pages = "9559--9586",
              
            }

```

---

## Acknowledgments
We gratefully acknowledge support from the Natural Sciences and Engineering Research Council  of Canada, the  Social  Sciences and  Humanities  Research  Council  of  Canada, Canadian  Foundation  for  Innovation,  [ComputeCanada](www.computecanada.ca) and [UBC ARC-Sockeye](https://doi.org/10.14288/SOCKEYE). We  also  thank  the  [Google TensorFlow Research Cloud (TFRC)](https://www.tensorflow.org/tfrc) program for providing us with free TPU access.


