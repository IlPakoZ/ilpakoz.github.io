---
layout: page
title: "DLRNA-BERTa: LLM model for Drug-RNA target binding affinity prediction"
description: with background image
img: assets/img/dlrnaberta/architecture.jpg
importance: 1
category: work
related_publications: true
---

DLRNA-BERTa is a Large Language Model (LLM) that can be used for predicting Drug-RNA target binding affinity (pKd). DLRNA-BERTa is a dual language model leveraging ChemBERTa-v2 MTR and our RNA-BERTa, two transformer models pretrained on large amount of SMILES data and RNA data (multi-task regression and masked-language-modeling, respectively).

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/dlrnaberta/architecture.jpg" title="dl-rnaberta_architecture" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    The overall DLRNA-BERTa architecture is presented here.
</div>

The project, which started as my master's thesis, was improved and is currently in <a href="https://www.biorxiv.org/content/10.1101/2025.09.05.674445v1"> preprint</a>. The project is available on <a href="https://github.com/IlPakoZ/dlrnaberta-dti-prediction">GitHub</a>. RNA-BERTa can also be easily integrated through the Python transformers library (for more information, read more <a href="https://huggingface.co/IlPakoZ/RNA-BERTa9700">here</a>) Feel free to test our model through the online interface at <a href="https://huggingface.co/spaces/IlPakoZ/DLRNA-BERTa">Hugging Face</a> — no installation required!

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/dlrnaberta/web_interface.jpg" title="web_interface" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Here an image of the Hugging Face interface to test the model. The model can be tested <a href="https://huggingface.co/spaces/IlPakoZ/DLRNA-BERTa">here</a>.
</div>
