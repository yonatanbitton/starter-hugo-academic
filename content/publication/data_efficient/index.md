---
abstract: Masked language modeling (MLM) is one of the key sub-tasks in vision-language pretraining. In the cross-modal setting, tokens in the sentence are masked at random, and the model predicts the masked tokens given the image and the text. In this paper, we observe several key disadvantages of MLM in this setting. First, as captions tend to be short, in a third of the sentences no token is sampled. Second, the majority of masked tokens are stop-words and punctuation, leading to under-utilization of the image. We investigate a range of alternative masking strategies specific to the cross-modal setting that address these shortcomings, aiming for better fusion of text and image in the learned representation. When pre-training the LXMERT model, our alternative masking strategies consistently improve over the original masking strategy on three downstream tasks, especially in low resource settings. Further, our pre-training approach substantially outperforms the baseline model on a prompt-based probing task designed to elicit image objects. These results and our analysis indicate that our method allows for better utilization of the training data.
slides: 
url_pdf: ""
publication_types:
  - "1"
authors:
  - admin
  - Gabriel Stanovsky
  - Michael Elhadad
  - Roy Schwartz
author_notes: []
publication: Findings of the Association for Computational Linguistics EMNLP 2021
summary: Masked language modeling (MLM) is one of the key sub-tasks in vision-language pretraining. In the cross-modal setting, tokens in the sentence are masked at random, and the model predicts the masked tokens given the image and the text. In this paper, we observe several key disadvantages of MLM in this setting. First, as captions tend to be short, in a third of the sentences no token is sampled. Second, the majority of masked tokens are stop-words and punctuation, leading to under-utilization of the image. We investigate a range of alternative masking strategies specific to the cross-modal setting that address these shortcomings, aiming for better fusion of text and image in the learned representation. Our pre-train masking strategy consistently improves over the baseline strategy in two evaluation setups.
url_dataset: ""
url_project: ""
publication_short: In *Findings of EMNLP 2021*
url_source: ""
url_video: ""
title: Data Efficient Masked Language Modeling for Vision and Language
doi: ""
featured: true
tags: []
projects:
  - data_efficient
image:
  caption: ""
  focal_point: ""
  preview_only: false
  filename: featured.png
date: 2021-09-05T16:17:07.654Z
url_slides: ""
publishDate: 2021-09-05T16:17:07.654Z
url_poster: ""
url_code: "https://github.com/yonatanbitton/data_efficient_masked_language_modeling_for_vision_and_language"
---
