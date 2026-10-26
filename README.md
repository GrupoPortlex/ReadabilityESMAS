# Readability ESMAS

This repository contains the source code for the article [A Comparative Study of Feature Representations for Spanish L2 Text Complexity Across Pedagogical and Authentic Corpora](http://journal.sepln.org/sepln/ojs/ojs/index.php/pln/article/view/6904) published at SEPLN 2026.

This study investigates the effectiveness of three feature representations for Spanish L2 CEFR level prediction (traditional readability metrics, CEFR-based lexical overlap features, and unigram TF-IDF) on two types of datasets (authentic and learner corpora).

More details in the article.

# Project

The main files are:

- `preprocessing.ipynb`: downloads datasets and precomputes features.
- `cefr_prediction.ipnyb`: trains models and generates results.
- `curated_vocab.tsv`: curated list from [Instituto Cervantes](cvc.cervantes.es/ensenanza/biblioteca_ele/plan_curricular/).

# Bibtex
If you find this research useful, please consider citing:

```
@article{PLN6904,
	author = {Daniel Mora y María José Domínguez Vázquez y Iván Arias-Arias y Idalete Dias y Vítor Míguez-Rego y Carlos Valcárcel Riveiro},
	title = {A Comparative Study of Feature Representations for Spanish L2 Text Complexity Across Pedagogical and Authentic Corpora},
	journal = {Procesamiento del Lenguaje Natural},
	volume = {77},
	number = {0},
	year = {2026},
	issn = {1989-7553},
	url = {http://journal.sepln.org/sepln/ojs/ojs/index.php/pln/article/view/6904},
	pages = {467--483}
}
```

