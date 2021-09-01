---
abstract: 
Objective. In Hebrew online health communities, participants commonly write medical terms that appear as
transliterated forms of a source term in English. Such transliterations introduce high variability in text and challenge text-analytics methods. To reduce their variability, medical terms must be normalized, such as linking
them to Unified Medical Language System (UMLS) concepts. We present a method to identify both transliterated and translated Hebrew medical terms and link them with UMLS entities.    
Materials and Methods. We investigate the effect of linking terms in Camoni, a popular Israeli online health
community in Hebrew. Our method, MDTEL (Medical Deep Transliteration Entity Linking), includes (1) an
attention-based recurrent neural network encoder-decoder to transliterate words and mapping UMLS from
English to Hebrew, (2) an unsupervised method for creating a transliteration dataset in any language without
manually labeled data, and (3) an efficient way to identify and link medical entities in the Hebrew corpus to
UMLS concepts, by producing a high-recall list of candidate medical terms in the corpus, and then filtering the
candidates to relevant medical terms.    
Results. We carry out experiments on 3 disease-specific communities, diabetes, multiple sclerosis, and depression. MDTEL tagging and normalizing on Camoni posts achieved 99% accuracy, 92% recall, and 87% precision.
When tagging and normalizing terms in queries from the Camoni search logs, UMLS-normalized queries
improved search results in 46% of the cases.    
Conclusions. Cross-lingual UMLS entity linking from Hebrew is possible and improves search performance
across communities. Annotated datasets, annotation guidelines, and code are made available online.
slides: 
url_pdf: ""
publication_types:
  - "2"
authors:
  - admin
  - Yonatan Bitton
  - Raphael Cohen
  - Tamar Schifter
  - Eitan Bachmat
  - Michael Elhadad
  - Noemie Elhadad
author_notes: []
publication: In Hebrew online health communities, participants commonly write medical terms that appear as
transliterated forms of a source term in English. Such transliterations introduce high variability in text and challenge text-analytics methods. To reduce their variability, medical terms must be normalized, such as linking
them to Unified Medical Language System (UMLS) concepts. We present a method to identify both transliterated and translated Hebrew medical terms and link them with UMLS entities.
url_dataset: ""
url_project: ""
publication_short: In *JAMIA 2020*
url_source: ""
url_video: ""
title: Cross-lingual Unified Medical Language System entity linking in online health communities
doi: ""
featured: false
tags: []
projects:
  - cross_lingual_entity_linking
image:
  caption: ""
  focal_point: ""
  preview_only: false
  filename: ""
date: 2021-03-17T16:17:07.654Z
url_slides: ""
publishDate: 2020-09-10T16:17:07.654Z
url_poster: ""
url_code: "https://github.com/yonatanbitton/mdtel"
---
